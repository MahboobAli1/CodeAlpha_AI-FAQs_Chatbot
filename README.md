# AI FAQs Chatbot 

This project is an AI-based FAQ chatbot developed using Python.  
It uses Natural Language Processing (NLP) techniques and TF-IDF with cosine similarity
to match user queries with the most relevant AI-related FAQ.

## 🚀 Features
- TF-IDF vectorization
- Cosine similarity-based matching
- Text preprocessing (lowercasing, stopword removal, stemming)
- Tkinter-based GUI chatbot
- 150+ AI-related FAQs supported
- Single-file implementation

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn
- NLTK
- Tkinter

## 📂 Dataset
The chatbot uses an Excel file:
- `ai_faqs.xlsx`
- Columns required: `question`, `answer`

## ▶️ How to Run
1. Install required libraries:
   ```bash
   pip install pandas scikit-learn nltk openpyxl
