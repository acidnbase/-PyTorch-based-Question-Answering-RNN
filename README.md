# 🧠 Simple RNN-based Question Answering System

A minimal PyTorch project that implements a Question Answering (QA) system using a simple RNN model. It learns to predict single-word answers based on questions from a custom dataset.

---

## 📁 Dataset

The dataset should be a CSV file (`100_Unique_QA_Dataset.csv`) with the following structure:

'''csv
question,answer
"What is the capital of France?", "Paris"
"What is 2 + 2?", "4"
''' 


🔧 Features:
Custom tokenizer and vocabulary builder
Index-based encoding for questions and answers
PyTorch Dataset and DataLoader integration
RNN model with an embedding layer and linear output
Simple training loop using cross-entropy loss
Softmax-based prediction function

📌 Limitations: 
Only predicts single-token answers.
No attention or transformer-based mechanisms.
Simple tokenizer (no punctuation handling or lemmatization).
