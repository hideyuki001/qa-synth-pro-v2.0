# 📊 Pseudo BLEU/ROUGE Logic — QA Synth Pro v2.0

## 🎯 Purpose
This document defines the **pseudo scoring logic** used in QA Synth Pro v2.0 for lightweight translation evaluation.  
The goal is **structural fidelity + educational clarity**, rather than strict reproducibility.

---

## 🔹 BLEU (0–100)

BLEU is adapted here to reflect **structural fidelity** rather than n-gram overlap only.  
Each axis contributes +20 points (max 100):

1. **Lexical Overlap** (+20)  
   - Measures key word overlap between source and translation  
   - Prioritizes terminology consistency  

2. **Syntactic Stability** (+20)  
   - Checks if subject–predicate pairing remains intact  
   - Rewards stable sentence trunks  

3. **Word Order Fidelity** (+20)  
   - Evaluates logical preservation of phrase order  
   - Allows shifts if contextually justified  

4. **Error Correction** (+20)  
   - Rewards removal of MT errors (grammar, tense, unnatural phrases)  
   - Penalizes mistranslations or omissions  

5. **Structural Rationality** (+20)  
   - Evaluates flow, punctuation, and clause balance  
   - Rewards readability and logical cohesion  

**Example:**  
> BLEU ≈ 92/100 for a translation with full coverage and corrected word order.

---

## 🔹 ROUGE-L (0–1.00)

ROUGE-L is redefined to measure **informational + structural match**.  
Weights are distributed across structural fidelity and clarity:

- 0.3–0.5 → **Info Coverage**  
- 0.1–0.2 → **Causal/Temporal Match**  
- 0.1–0.2 → **Natural Dependencies** (syntax nodes, phrase alignment)  
- 0.05–0.1 → **Redundancy Removal**  
- 0.05–0.1 → **Focus Clarity**  

**Example:**  
> ROUGE-L ≈ 0.91 for a translation with clear causal/temporal flow and concise focus.

---

## 🧭 Scoring Guidelines

- 🔴 **Info Omission** → “Meaning Missing” (BLEU/ROUGE penalty)  
- 🔴 **Terminology Misuse** → “Term Caution”  
- 🟠 **Ambiguity** → “Interpretation Concern”  
- 🟠 **Tense/Logic Error** → “Structural Issue”  
- 🟡 **Style Mismatch** → “Register Concern”  
- 🟢 **Structural Limits** → Flag only with note  

---

## ✅ Summary

- **BLEU (0–100)** = 20 × (Overlap + Stability + Order + Error Correction + Rationality)  
- **ROUGE-L (0–1.00)** = Structural Info + Flow + Clarity weights  
- Purpose: **educational / QA training use**, not strict metric reproducibility.
