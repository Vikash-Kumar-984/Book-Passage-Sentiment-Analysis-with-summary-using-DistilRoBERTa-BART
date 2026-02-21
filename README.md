# 📘 Book Passage Analysis using NLP & Transformers

An AI-powered Book Passage Analyzer built using Python and Transformer-based NLP models.

This project analyzes a given text passage and provides:

- ✅ Total Word Count
- ✅ Predominant Emotion Detection
- ✅ 2–3 Possible Book Suggestions
- ✅ 2–3 Sentence AI Generated Summary

---

## 🚀 Features

- 📊 Word count using Regex
- 😊 Emotion detection using Transformer model
- 📚 Context-based book suggestions
- 📝 Abstractive summarization using BART
- 🧠 HuggingFace Transformers integration
- 🧩 Modular OOP-based implementation

---

## 🛠️ Tech Stack

- Python 3.x
- PyTorch
- HuggingFace Transformers
- Regex (re module)
- Google Colab / Local Environment

---

## 🤖 Models Used

### 1️⃣ Emotion Detection
Model: j-hartmann/emotion-english-distilroberta-base

- Pretrained DistilRoBERTa model
- Classifies Joy, Sadness, Anger, Disgust, Neutral, etc.
- Loaded using HuggingFace pipeline

### 2️⃣ Text Summarization
Model: facebook/bart-large-cnn

- Transformer-based encoder-decoder architecture
- Generates meaningful 2–3 sentence summaries
- Uses abstractive summarization approach

---

## 📂 Project Structure

Book-Passage-Analyzer/
│
├── book_analyzer.py
├── README.md
└── requirements.txt

---

## ⚙️ Installation

Install required libraries:

pip install torch transformers tf-keras

---

## ▶️ How to Run

Run the script:

python book_analyzer.py

Then paste the passage when prompted:

Paste the book passage here:

The system will generate:

1. Total Word Count
2. Predominant Emotion
3. Possible Book Suggestions
4. AI Generated Summary

---

## 📊 Sample Output

Book Passage Analysis Report

1. Total Word Count: 42  
2. Predominant Emotion: Joy  
3. Possible Books: The Alchemist, Man’s Search for Meaning  
4. Summary: The passage highlights the importance of following one's dreams and discovering purpose in life.

---

## 🧠 How It Works

• Word Count → Regex pattern matching  
• Emotion Detection → Transformer classification pipeline  
• Book Suggestion → Keyword-based thematic logic  
• Summary Generation → BART transformer model  

---

## 📈 Future Improvements

- Add Streamlit Web App
- Convert into REST API
- Improve book suggestion using embeddings
- Add multi-language support
- Deploy to cloud

---

## 👨‍💻 Author

Vikash Kumar  
AI/ML Developer  

LinkedIn: https://www.linkedin.com/in/vikash-kumar-a071a0205/  
GitHub: https://github.com/Vikash-Kumar-984  

---

## ⭐ Acknowledgment

Developed as part of an AI Engineer assignment demonstrating practical NLP, Transformers, and modular Python architecture.
