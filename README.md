# 🧠 Neural Responses to Emotion in Music – EEG Analysis

Welcome! This project explores how brain activity—recorded via EEG—relates to emotional responses to music, using the [OpenNeuro BCMI-MIdAS dataset](https://openneuro.org/datasets/ds002721/versions/1.0.1). Our focus is on investigating whether certain brainwave frequencies (like alpha or beta bands) can predict how "happy" a song makes someone feel.

> ⚠️ **For the full analysis, deep-dive statistics, and conclusions, please refer to**:> 📄 `Analysis of Neural Data - Final Report.pdf`

---

## 📦 How to Install and Connect the Dataset

1. **Clone or download this repo** (including the Jupyter notebook `AnalysisofNeuralData.ipynb` and the report PDF).

2. **Download the EEG dataset from OpenNeuro**:

   - Go to [this OpenNeuro page](https://openneuro.org/datasets/ds002721/versions/1.0.1)
   - Click the **"Download"** button (you can choose the full dataset or individual subjects)
   - The dataset will come in BIDS format (structured folder system)

3. **Place the dataset in the correct directory**:

   - Make sure the path inside the notebook matches where you've saved the data. You might need to edit file paths in `AnalysisofNeuralData.ipynb` to point to your local dataset.
   - For example:
     ```python
     data_path = "/your/local/path/ds002721"
     ```

4. **Run the Jupyter Notebook**:

   - Open `AnalysisofNeuralData.ipynb` with JupyterLab or VS Code
   - Step through the cells to reproduce the results or modify them for your own experiments!

---

## 🧪 What You'll Find in the Notebook

- How we extract emotional ratings (e.g. "happy", "angry") from event codes
- How power spectral density (PSD) is computed from EEG signals
- How we normalize and analyze EEG band data (alpha, beta, gamma, etc.)
- Statistical models like t-tests, ANOVA, multinomial regression, and even bootstrapping
- Visualizations of how brain signals relate (or don’t!) to music-induced emotion

---

## 📖 For Deeper Insights

The `Analysis of Neural Data Final Report.pdf` includes:

- Full methodology and rationale
- Data preparation, cleaning, and feature extraction
- Statistical results and interpretations
- Key findings and limitations

If you're here for scientific analysis, modeling techniques, or want to understand how EEG can (or can't) reveal musical emotional states—this is your go-to document.

---

## ✨ Bonus Tips

- If you're new to EEG data or the BIDS format, OpenNeuro's documentation is a helpful resource.
- The notebook is built to be modular—feel free to swap in your own emotion ratings or add more frequency bands.
- Curious about the songs used in the study? Unfortunately, they're not included—but the method is generalizable to other emotional music datasets.

---
