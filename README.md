# Hate-Speech-Detection-ML
Comparison of TF-IDF and DistilBERT for detecting hate speech. 

# Hate Speech Detection: TF-IDF vs DistilBERT

## Project Overview
[cite_start]This capstone project evaluates different machine learning approaches to differentiate between hate speech, offensive language, and neutral content on social media[cite: 12]. [cite_start]We compared traditional models using TF-IDF text representation against the state-of-the-art **DistilBERT** transformer model[cite: 10, 11].

## Authors
* [cite_start]**Marialena Georgiou** 
* [cite_start]**Nayat Kortun** 
* [cite_start]**Nina Dimovska** 

## Dataset
We utilized the **Davidson et al. (2017) [cite_start]Hate Speech and Offensive Language Dataset**, which contains 24,783 labeled tweets. 
- **Dataset Source:** [GitHub Link](https://github.com/t-davidson/hate-speech-and-offensive-language)

## Models Evaluated
1. [cite_start]**Traditional ML:** Logistic Regression, Support Vector Machine (SVM), and Multinomial Naive Bayes[cite: 10].
2. [cite_start]**Deep Learning:** DistilBERT[cite: 11].

## Key Files
- [cite_start]`CAPSTONE_PROJECT_FINAL.ipynb`: Full Python code for data preprocessing, EDA, and model training.
- [cite_start]`Capstone Project Report.pdf`: Detailed research paper covering our methodology and findings.

## Libraries Used
- Transformers (HuggingFace)
- Scikit-learn
- PyTorch
- Pandas/NumPy
- [cite_start]Matplotlib/Seaborn
