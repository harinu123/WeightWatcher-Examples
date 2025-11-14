# WeightWatcher-Examples
A curated collection of real-world examples, notebooks, and experiments using **WeightWatcher**, the open‑source tool for analyzing layer-wise spectra, heavy‑tailed behavior, power‑law exponents (α), correlation traps, and model quality throughout training.

These examples span small MLPs, double descent, and billion-parameter LLMs.

---

## 📘 Core Examples
- **[SingleLayerWWExample.ipynb](SingleLayerWWExample.ipynb)**

---

## 🧠 MLP + MNIST Experiments

How varying the batch size and/or learning rates affect convergence
- **[WW-MLP3-BatchSizes.ipynb](WW-MLP3-BatchSizes.ipynb)**
- **[WW_MLP3_LearningRates.ipynb](WW_MLP3_LearningRates.ipynb)**

Explaining Epoc-wise Double Descent
- **[WW_MLP3_LearningRates.ipynb](WW_MLP3_LearningRates.ipynb)**

Comparing the inductive biases between AdamW and Muon
- **[MLP3-MNIST-AdamW.ipynb](MLP3-MNIST-AdamW.ipynb)**
- **[MLP3-MNIST-Muon.ipynb](MLP3-MNIST-Muon.ipynb)**


---

## 🧬 LLM + Fine-Tuning Examples
- **[OLMO1B.ipynb](OLMO1B.ipynb)**
- **[OLMO1B_Fine_Tuning_Results.csv](OLMO1B_Fine_Tuning_Results.csv)**
- **[WW_FIneTuned_Alphas.ipynb](WW_FIneTuned_Alphas.ipynb)**
- **[WW_Mistral_DragonKings.ipynb](WW_Mistral_DragonKings.ipynb)**
- **[WW_PEFT.ipynb](WW_PEFT.ipynb)**
- **[WW_SVDSMoothing_TinyLLaMAipynb.ipynb](WW_SVDSMoothing_TinyLLaMAipynb.ipynb)**

---

## 🧪 Miscellaneous
- **[random_labels/](random_labels/)**
- **[F_Vallet_Full.ipynb](F_Vallet_Full.ipynb)**
- **[WW_DoubleDesecent.ipynb](WW_DoubleDesecent.ipynb)**
- **[WW-MLP3-AdamW.ipynb] (WW-MLP3-AdamW.ipynb)**
---

## 🚀 What These Examples Demonstrate
- How α < 2 identifies overfitting & correlation traps  
- Spectral **phase transitions** during training  
- **Epoch-wise double descent** behavior  
- Optimizer differences (Muon vs AdamW vs SGD)  
- Fine‑tuning shifts between underfit → well‑fit → overfit  
- Diagnostics for memorization and rank collapse  

---

## 📦 Getting Started
```bash
git clone https://github.com/CalculatedContent/WeightWatcher-Examples.git
cd WeightWatcher-Examples
pip install weightwatcher
jupyter notebook
```

---

## 📜 License
MIT License — see **LICENSE**
