# Ai-language-recognition-translation

An AI-powered project that detects and recognizes the language of input text using a Naive Bayes classifier, and seamlessly translates it into the user’s preferred language with Googletrans.

Designed to run easily in **Google Colab**.

---

## 🚀 Features
- Detects text language using **scikit-learn (MultinomialNB)**  
- Translates text with **Googletrans (v4.0.0-rc1)**  
- Lightweight and simple to run in Colab  

---

## 🛠️ Requirements
- Python (preinstalled in Colab)  
- NumPy  
- Pandas  
- scikit-learn  
- Googletrans (install manually in Colab)  

---

## ▶️ Usage in Google Colab
1. Upload your dataset file (`language.csv`) to Colab.  
2. Install Googletrans in your notebook:  
   ```python
   !pip install googletrans==4.0.0-rc1
3.Run all cells in the notebook step by step.
4.Enter text when prompted → The model detects the language → Translates into your chosen target language.

---

**📖 Example**
Enter a text: Bonjour
Detected Language: French
Enter target language code (e.g., en, hi, fr): en
Translated Text: Hello
