# 📘 Book Passage Analysis using NLP & Transformers

An AI-powered Book Passage Analyzer built using Python and Transformer-based NLP models.  
This project analyzes a given text passage and provides:

- ✅ Total Word Count  
- ✅ Predominant Emotion Detection  
- ✅ 2–3 Possible Book Suggestions  
- ✅ 2–3 Sentence AI Generated Summary  

---

## 🚀 Features

- 📊 Accurate word count using regex
- 😊 Emotion detection using a transformer classification model
- 📚 Context-based book suggestion logic
- 📝 Abstractive summarization using BART
- 🧠 Transformer-based NLP pipeline
- 🧩 Modular and clean OOP-based Python implementation

---

## 🛠️ Tech Stack

- Python 3.x  
- PyTorch  
- HuggingFace Transformers  
- Regex (re module)  
- Google Colab  

---

## 🤖 Models Used

### 1️⃣ Emotion Detection
Model: `j-hartmann/emotion-english-distilroberta-base`

- Pretrained DistilRoBERTa model
- Classifies emotions like Joy, Sadness, Anger, Disgust, Neutral, etc.
- Loaded using HuggingFace pipeline

### 2️⃣ Text Summarization
Model: `facebook/bart-large-cnn`

- Transformer-based encoder-decoder model
- Generates meaningful 2–3 sentence summaries
- Abstractive summarization approach

---

## 📂 Project Structure
