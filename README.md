# 🔁 QA Synth Pro v2.0 — Structural Translation Self-Review Template

🎯 **Intended Audience**  
Translators, translation trainees, educators, RLHF data curators

This repository provides a **structured and retrainable self-review template** for translation quality assurance, focusing on **sentence-level structural fidelity** and **AI-alignment suitability**.

---

## 📐 Evaluation Axes (5D + Optional)
1. **Semantic Layout** – Semantic core retention, node mapping  
2. **Structural Flow** – Syntactic trunk stability, punctuation, conjunctions  
3. **Spacetime Dynamics** – Temporal/causal/emotional sequencing  
4. **FPE Standards** – Post-edit corrections, natural style, register consistency  
5. **Neural Alignment** – Syntactic reproducibility, vector suitability for AI corpora  
💭 Optional: **Translation Resonance** – Rhythm, imagery, poetic cadence

---

## 📘 Documentation
- `docs/system_instructions.md` → Full framework specification (8000 chars)  
- `docs/scoring_logic.md` → Pseudo BLEU/ROUGE logic (structural fidelity scoring)  
- `docs/self_review_axes.md` → Five-axis evaluation guide  
- `docs/examples.md` → Sample reviews with revision proposals  

---

## 🧪 Examples
- `examples/cn-ja_review.md` → Chinese→Japanese translation self-review  
- `examples/en-ja_review.md` → English→Japanese QA case  
- `examples/en-fr_review.md` → French QA case  

---

## ⚙️ Deployment
✅ Usable as self-review sheets in **Notion / Google Docs / Word**  
✅ Compatible with BLEU/ROUGE auto-scores (comparative comments)  
✅ Exportable to JSON/CSV for **RLHF training and QA education**

---

## 🚀 Usage
```bash
# Example: Self-review evaluation (pseudo logic)
python evaluate.py --input my_translation.txt --axes 5 --output review.json
