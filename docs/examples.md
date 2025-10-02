# 🧪 Examples — QA Synth Pro v2.0

## 🎯 Purpose
This document provides **sample self-reviews** of translations using QA Synth Pro v2.0.  
Each case demonstrates how the **5-axis evaluation** and optional resonance are applied.

---

## 🔹 Example 1: EN→JA (Policy Text)
**Source (EN):**  
> "The new policy aims to reduce energy consumption while maintaining economic growth."

**Candidate Translation (JA):**  
> 「新しい政策は、経済成長を維持しつつ、エネルギー消費を削減することを目的としている。」

**Highlights:**  
- Semantic Layout preserved (policy → aims → reduce consumption / maintain growth)  
- Structural Flow stable via 「つつ」 conjunction  
- No FPE errors, style appropriate for policy documents  
- Neural alignment (SVO mapping) intact  
- Score: BLEU ≈ 95 / ROUGE-L ≈ 0.92 / **Rating: S**

📄 Full file: [`examples/en-ja_review.md`](../examples/en-ja_review.md)

---

## 🔹 Example 2: CN→JA (Instructional Text)
**Source (CN):**  
> "请在提交之前仔细检查文件格式。"

**Candidate Translation (JA):**  
> 「提出する前に、ファイル形式をよく確認してください。」

**Highlights:**  
- Semantic Layout: Core meaning (submit + check format) correctly mapped  
- Structural Flow: Imperative maintained with 丁寧体  
- Spacetime Dynamics: Clear sequence (before → action)  
- FPE Standards: Smooth, no unnatural word order  
- Neural Alignment: Verb-object mapping (检查 → 確認する) preserved  
- Score: BLEU ≈ 93 / ROUGE-L ≈ 0.90 / **Rating: S**

📄 Full file: `examples/cn-ja_review.md` (to be added)

---

## 🔹 Example 3: EN→FR (Marketing Copy)
**Source (EN):**  
> "Experience a new way of connecting with your audience."

**Candidate Translation (FR):**  
> « Découvrez une nouvelle façon de communiquer avec votre public. »

**Highlights:**  
- Semantic Layout: Core meaning retained (experience → discover)  
- Structural Flow: Smooth clause balance  
- Spacetime Dynamics: Present tense imperative consistent  
- FPE Standards: Correct register for marketing  
- Neural Alignment: Verb-object mapping reproducible  
- Resonance: Natural cadence, stylistic appeal  
- Score: BLEU ≈ 91 / ROUGE-L ≈ 0.89 / **Rating: A**

📄 Full file: `examples/en-fr_review.md` (to be added)

---

## ✅ Summary
These examples illustrate:
- How to apply the **5-axis review** + optional resonance  
- How BLEU/ROUGE pseudo scores align with qualitative judgments  
- How QA Synth Pro v2.0 serves both **translation education** and **practical QA**  
