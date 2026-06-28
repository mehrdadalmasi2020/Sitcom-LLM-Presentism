# 🎭 Sitcom Presentism — Jupyter Notebook Tutorial

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19250947.svg)](https://doi.org/10.5281/zenodo.19250947)

🧠 *A lightweight, code-only release demonstrating how sitcom episode summaries are preprocessed, fine-tuned, and analyzed for stylistic modernization.*

---

## 📄 Paper / Dataset

This repository accompanies the paper:

**Rewriting the Past for the Present: A Computational Study of Sitcom Presentism using Fine-Tuned Language Models**

Authors: **Mehrdad ALMasI** and **Tugce Karatas**

📦 Zenodo archive: https://zenodo.org/records/19250947  
🔗 DOI: https://doi.org/10.5281/zenodo.19250947

If you use this work, please cite:

```bibtex
@misc{almasi2026sitcompresentism,
  title={Rewriting the Past for the Present: A Computational Study of Sitcom Presentism using Fine-Tuned Language Models},
  author={{ALMasI}, Mehrdad and Karatas, Tugce},
  year={2026},
  publisher={Zenodo},
  doi={10.5281/zenodo.19250947},
  url={https://doi.org/10.5281/zenodo.19250947}
}
```

---

## 📂 Repository Contents

| Notebook | Description |
| --- | --- |
| 🧩 **load_storylab.ipynb** | Loads and preprocesses CC-licensed Wikipedia episode summaries into structured data. |
| 🤖 **FT_Predict_storylab.ipynb** | Fine-tunes and evaluates language models to generate and assess modernized sitcom plots. |

---

## ⚙️ Setup

### 1️⃣ Create a Python environment

```bash
python -m venv .venv
```

Activate the environment:

```bash
# macOS / Linux
source .venv/bin/activate
```

```bash
# Windows
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### 2️⃣ Launch Jupyter

```bash
jupyter lab
```

### 3️⃣ Run notebooks in order

1. Open **load_storylab.ipynb** and run all cells to create the cleaned dataset, such as `episodes_clean.jsonl`.
2. Open **FT_Predict_storylab.ipynb** to fine-tune the model and generate evaluation outputs.

💡 Both notebooks are designed for reproducibility using public Wikipedia summaries.

---

## 📊 Outputs

The notebooks can produce:

- Cleaned dataset files with entity and structure extraction
- Fine-tuning logs and evaluation metrics
- Generated modernized plot outlines
- Visualization cells, including loss curves and text-output comparisons

All generated text is **machine-created** and **transformative** for research purposes.

---

## 📚 Data & Copyright

Episode summaries were sourced from public Wikipedia pages under the CC BY-SA 4.0 license.

No original scripts, media files, or copyrighted material from *Seinfeld* are included in this repository.

All modernized plots are machine-generated, transformative outputs created for research and analysis.

✅ Reproducible with Wikipedia data or small synthetic samples.  
🚫 Do not include proprietary scripts, original show material, or commercial model weights.

---

## 🔐 GDPR & Ethics

- No personal data is intentionally processed.
- Entities are fictional characters or public encyclopedic references.
- The notebooks contain no usernames, private paths, passwords, or API keys.
- This release is intended for academic and non-commercial research purposes.

---

## 🧩 Recommended Workflow

1. **load_storylab.ipynb** → preprocessing and dataset preparation  
2. **FT_Predict_storylab.ipynb** → fine-tuning, generation, and evaluation

---

## 🪪 License

This repository is released under the **MIT License**.

Copyright (c) 

Permission is hereby granted, free of charge, to any person obtaining a copy of this code and associated documentation files, to deal in the code without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the code.

THE CODE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.

---

## ✅ Summary

- Uses CC-licensed Wikipedia summaries
- Contains no personal data
- Contains no original copyrighted show scripts or media
- Supports reproducible, transformative research
- Prepared for **DH Benelux 2026**

📘 *Prepared for DH Benelux 2026.*
