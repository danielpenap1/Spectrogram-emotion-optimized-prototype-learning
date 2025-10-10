# 📄 Explainable Audio Emotion Recognition Using High-Resolution Autoencoder and Prototype-Based Deep Learning
### Daniel Peña Porras, Esteban García-Cuesta

---

This repository accompanies the journal paper:

> **Explainable Audio Emotion Recognition Using High-Resolution Autoencoder and Prototype-Based Deep Learning**  
> *Authors:* Daniel Peña, Esteban García-Cuesta.  
> *Journal:* [Name of the Journal], [Year]
> *DOI:* [DOI]  

The repository complements and extends the material included in the article. It also provides the necessary code to run the experiments as well as the explainability results: the learned **prototypes** as spectrograms and as audio signals.

---

## ⚙️ Repository Structure and Usage

The repository includes both **Jupyter notebooks** (`.ipynb`) and equivalent **Python scripts** (`.py`) for the entire experimental pipeline.  
You can execute either version depending on your workflow preference.

### 🧪 Run the Pipeline (Jupyter Notebooks)

The project is organized into **four main stages**. Each notebook can be executed independently by simply setting the appropriate dataset path.

1. **`0_preprocess.ipynb`** – Data loading and spectrogram generation.
2. **`1_autoencoders_training_and_evaluation.ipynb`** – Train and evaluate the high-resolution autoencoders for the different speakers.
3. **`2_prototype_classifiers_training_and_evaluation.ipynb`** – Train the prototype-based deep learning classifiers.
4. **`3_prototype_analysis.ipynb`** – Analyze learned prototypes and generate visualizations.

> 💡 *Tip:* These notebooks are self-contained and can be adapted for different datasets by modifying the dataset path at the beginning of each notebook.

---

## 🌐 Complementary Webpage

An interactive GitHub Page is provided:

🔗 **[https://danielpenap1.github.io/Spectrogram-emotion-optimized-prototype-learning/](https://danielpenap1.github.io/Spectrogram-emotion-optimized-prototype-learning/)**

The page provides the reproducible prototypes foldable sections for each dataset and speaker. It allows:
- Visualization of **learned spectrogram prototypes** per emotion
- Reproduction of **audio prototypes**  

---

## ⚙️ Setup and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/danielpenap1/Spectrogram-emotion-optimized-prototype-learning.git

cd Spectrogram-emotion-optimized-prototype-learning
