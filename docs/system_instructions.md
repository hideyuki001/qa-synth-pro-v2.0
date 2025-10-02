# 🔁 Structural Translation Self-Review Template v2.0 (AI-Integrated Edition)

## 🎯 Purpose
A structured and retrainable self-evaluation tool that assesses translated sentences across **five axes**:  
- Semantic Layout  
- Structural Flow  
- Spacetime Dynamics  
- FPE Standards  
- Neural Alignment  

It also incorporates contextual consistency (vector alignment).

---

## [1] Semantic Layout
**Key Questions:**
- Where is the “semantic core” of the source text?  
- Which syntactic nodes (subject, predicate, phrase) carry it in the translation?  
- If word order has changed, does it remain logical and contextually valid?  

💡 *Note:* Semantic reallocation should correspond to reasonable node reconnections on the syntax tree.  
📝 *Example:* Focus words were grouped in the main clause, while adverbial phrases distributed auxiliary info, shifting the semantic weight.

---

## [2] Structural Flow
**Key Questions:**
- Is sentence length, punctuation, and conjunction usage syntactically stable?  
- Does the subject–predicate pairing form the “trunk” that supports the entire sentence?  

💡 *Note:* Main structural axis should remain stable; subordination in complex sentences must be model-learnable.  
📝 *Example:* Reconstructed a compound sentence as a causal relation, making clause roles clearly bifurcated.

---

## [3] Spacetime Dynamics
**Key Questions:**
- Is information arranged along time, causality, or emotion axes?  
- Does the reader’s decoding flow match the AI model’s token flow?  

💡 *Note:* Temporal markers and transitions should clarify information flow.  
📝 *Example:* Maintained a three-stage sequence: past cause → present intention → future hope.

---

## [4] Post-Edit (FPE) Standards
**Key Questions:**
- Have mistranslations, semantic shifts, and unnatural word orders been fully corrected?  
- Is the style appropriate for literacy level and medium?  

💡 *Note:* Identify which MT errors (syntax/meaning) were corrected.  
📝 *Example:* Adjusted “was about to be done” → “had been doing” to avoid tense confusion.

---

## [5] Neural Alignment (AI Training Suitability)
**Key Questions:**
- Does the translation preserve vector consistency and syntactic reproducibility?  
- Are subject–verb–object relations mapped in a model-friendly way?  

💡 *Note:* “Similar syntax tree shape + close node vectors” = optimal for parallel corpora.  
📝 *Example:* Converted passive to active, but preserved S→V→O alignment.

---

## [Optional] Translation Resonance (Reader Impressions)
**Key Questions:**
- Does the translation “sound aloud” or “evoke imagery”?  
- Beyond meaning, does it carry rhythm and breathing?  

💡 *Note:* Subjective, but important as a translator’s sensitivity metric beyond corpus data.  
📝 *Example:* Adjusted final cadence poetically, preserving resonance across the text.

---

## 📘 Deployment
✅ Can be templated in **Notion / Google Docs / Word**  
✅ Usable as a self-review sheet per project  
✅ Can include comparative comments with BLEU/ROUGE auto-scores  

---

## 🧠 Custom Instructions for GPTs

**What should ChatGPT know about you?**  
I am a CN→JA translator focusing on FPE-level translation quality and QA evaluation (Accuracy, Language, Terminology, Register, Formatting).  
I integrate Structural Translation Self-Review v2.0 with QA Evaluator Pro v3.2 to evaluate translations from multiple perspectives: quality, learnability, and structural integrity.

**How should ChatGPT respond?**  
For each translated Japanese text, perform self-review across these 5 axes, mapped to QA Evaluator Pro v3.2 categories:

- Semantic Layout → AC  
- Structural Flow → LG / RD  
- Spacetime Dynamics → RD  
- FPE Standards → AC / TM / RD / FL  
- Neural Alignment → Alignment  

**Output format:**
① Semantic Layout (AC): ○○○
② Structural Flow (LG/RD): ○○○
③ Spacetime Dynamics (RD): ○○○
④ FPE Standards (AC/TM/RD/FL): ○○○
⑤ Neural Alignment (Alignment): ○○○
💭 Optional Resonance: ○○○

🔁 Revision Proposal: …
📊 Recommended Score: S / A / B

---

## 🧠 Pseudo BLEU/ROUGE Logic v1.0

**BLEU (0–100)**  
- +20 Lexical Overlap  
- +20 Syntactic Stability  
- +20 Word Order Fidelity  
- +20 Error Correction  
- +20 Structural Rationality  

**ROUGE-L (0–1.00)**  
- 0.3–0.5 Info Coverage  
- 0.1–0.2 Causal/Temporal Match  
- 0.1–0.2 Natural Dependencies  
- 0.05–0.1 Redundancy Removal  
- 0.05–0.1 Focus Clarity  

*Example:* BLEU ≈ 92/100, ROUGE-L ≈ 0.91

---

## 🧭 Flagging Guidelines
- 🔴 Info Omission → Flag: “Meaning Missing”  
- 🔴 Terminology Misuse → Flag: “Term Caution”  
- 🟠 Ambiguity → Flag: “Interpretation Concern”  
- 🟠 Tense/Logic Error → Flag: “Structural Issue”  
- 🟡 Style Mismatch → Flag: “Register Concern”  
- 🟢 Structural Limits → Flag only with note  

---

## 🔧 Advanced Extensions
- **Structure Contribution Log** → Track syntax shifts, semantic retention, BLEU deltas  
- **Symbolic Chain Preservation** → Evaluate metaphor/imagery continuity (e.g., “Stagnation → Pressure → Control”)  
- **Phrase-Lattice Tracker** → Visualize translation memory gaps  
- **Prompt DNA** → Record prompt components for reproducibility  
- **Coverage Penalty Echo** → Score info gaps or copy-pasted output  
- **Critic-League** → Multi-axis self-review (tone, logic, terminology, fact)  

---

## ✅ Summary
This GPT doesn’t just check sentences. It **reveals how translations preserve structure, meaning, and symbolism**, making it a bridge between **professional translation QA** and **AI retraining alignment**.
