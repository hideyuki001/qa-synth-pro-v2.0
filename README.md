# 🔁 QA Synth Pro v2.0 — Structural Translation Self-Review Template
# 🔁 QA Synth Pro v2.0 — Structural Translation Self-Review Template  

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![GitHub stars](https://img.shields.io/github/stars/hideyuki001/qa-synth-pro-v2.0?style=social)](https://github.com/hideyuki001/qa-synth-pro-v2.0/stargazers)  
[![Release](https://img.shields.io/github/v/release/hideyuki001/qa-synth-pro-v2.0)](https://github.com/hideyuki001/qa-synth-pro-v2.0/releases)  

🎯 **Intended Audience**  
Translators, translation trainees, educators, RLHF data curators

This repository provides a **structured and retrainable self-review template** for translation quality assurance, focusing on **sentence-level structural fidelity** and **AI-alignment suitability**.

---

## 📐 Evaluation Axes (5D + Optional)

1. **Semantic Layout** – Semantic core retention, syntax node mapping  
2. **Structural Flow** – Syntactic trunk stability, punctuation, conjunction usage  
3. **Spacetime Dynamics** – Temporal, causal, and emotional sequencing  
4. **FPE Standards** – Post-editing corrections, style appropriateness, register consistency  
5. **Neural Alignment** – Syntactic reproducibility, parallel corpus suitability  

💭 **Optional**: Translation Resonance – Rhythm, imagery, poetic cadence

---

## 📘 Documentation

- `docs/system_instructions.md` → Full specification (8000 chars, transparency & reproducibility)  
- `docs/scoring_logic.md` → Pseudo BLEU/ROUGE structural scoring logic  
- `docs/self_review_axes.md` → Five-axis evaluation guide  
- `docs/examples.md` → Sample reviews with revision proposals  

---

## 🧪 Examples

- `examples/en-ja_review.md` → English→Japanese review case  
- `examples/cn-ja_review.md` → Chinese→Japanese review case  
- `examples/en-fr_review.md` → English→French review case  

---

## 📂 Repository Structure

- `docs/` → Full specifications & guides  
- `examples/` → Case studies (EN→JA, CN→JA, EN→FR, …)  
- `templates/` → Self-review forms for Notion, Google Docs, Word (planned)  

---

## ⚙️ Deployment

✅ Usable as a self-review sheet in **Notion / Google Docs / Word**  
✅ Compatible with BLEU/ROUGE auto-scores (comparative comments)  
✅ Exportable to JSON/CSV for **RLHF training and translation QA education**

---

## 🚀 Usage

Example self-review workflow:

```bash
# Evaluate a translation draft with pseudo scoring
python evaluate.py --input my_translation.txt --axes 5 --output review.json
