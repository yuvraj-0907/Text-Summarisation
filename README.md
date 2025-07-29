# 📝 Text Summarisation Web App

This is a simple web application for **extractive text summarization** built using **Flask**, **spaCy**, and **Bootstrap**. The app takes user-inputted text and generates a concise summary, helping users get the key points quickly and efficiently.

---

## 🚀 Features

- Accepts any raw English text
- Extractive summarization using NLP (spaCy)
- Displays original text, summary, and word counts
- Responsive UI built with Bootstrap

---

## 🧠 How it Works

This app uses a frequency-based extractive summarization algorithm implemented with the help of **spaCy**:

1. Tokenizes the input text and removes stopwords/punctuation.
2. Calculates the frequency of each important word.
3. Scores each sentence based on the frequency of words it contains.
4. Selects the top ~30% highest-scoring sentences to form the summary.

---

## 🗂️ Project Structure

