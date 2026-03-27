# 🎭 Sitcom Presentism — Jupyter Notebook Tutorial 

🧠 *A lightweight, code-only release demonstrating how sitcom episode summaries are preprocessed, fine-tuned, and analyzed for stylistic modernization.*

---

## 📂 Repository Contents

| Notebook                         | Description                                                                              |
| -------------------------------- | ---------------------------------------------------------------------------------------- |
| 🧩 **load_storylab.ipynb**       | Loads and preprocesses CC-licensed Wikipedia episode summaries into structured data.     |
| 🤖 **FT_Predict_storylab.ipynb** | Fine-tunes and evaluates language models to generate and assess modernized sitcom plots. |

---

## ⚙️ Setup

1️⃣ **Create a Python environment**

python -m venv .venv
source .venv/bin/activate    # macOS/Linux
.venv\Scripts\activate       # Windows
pip install -r requirements.txt

2️⃣ **Launch Jupyter**

jupyter lab

3️⃣ **Run notebooks in order**

* Open **load_storylab.ipynb** → run all cells to create cleaned dataset (e.g., episodes_clean.jsonl)
* Then open **FT_Predict_storylab.ipynb** → fine-tune model and generate evaluation plots

💡 Both notebooks are designed for reproducibility with only public Wikipedia summaries.

---

## 📊 Outputs

* Cleaned dataset with entity and structure extraction
* Fine-tuning logs and evaluation metrics
* Generated “modernized” plot outlines
* Visualization cells (loss curves, text outputs)

All generated text is **machine-created** and **transformative** for research purposes.

---

## 📚 Data & Copyright

“Episode summaries were sourced from the public Wikipedia page under the CC BY-SA 4.0 license.
No original scripts, media, or copyrighted material from *Seinfeld* were used.
All modernized plots are machine-generated, transformative outputs created for research and analysis.”

✅ Reproducible with Wikipedia data or small synthetic samples.
🚫 Do not include proprietary scripts, original show material, or commercial model weights.

---

## 🔐 GDPR & Ethics

* No personal data processed.
* All entities are fictional or public (e.g., character names).
* Notebooks contain no usernames, paths, or API keys.
* For academic and non-commercial purposes only.

---

## 🧩 Recommended Order

1️⃣ load_storylab.ipynb → preprocessing
2️⃣ FT_Predict_storylab.ipynb → fine-tuning and evaluation

---

## 🪪 License

**MIT License**
Copyright (c) 2025 Anonymous Authors
Permission is hereby granted, free of charge, to any person obtaining a copy of this code and associated documentation files, to deal in the code without restriction, including without limitation the rights to use, copy, modify, merge, and distribute.
THE CODE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.


---

✅ **Summary**

* Uses CC-licensed Wikipedia summaries
* Contains no personal or copyrighted data
* Fully GDPR-compliant
* Supports reproducible, transformative research

📘 *Prepared for DH Benelux 2026
