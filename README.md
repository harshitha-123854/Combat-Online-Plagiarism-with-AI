AI-Based Plagiarism Detection System

Overview -

This project is an AI-powered plagiarism detection system that identifies similarity between textual documents using Natural Language Processing (NLP) techniques.
It helps detect copied or paraphrased content by analyzing text patterns and computing similarity scores

🚀 Features

Detects similarity between two text documents
Uses NLP preprocessing (tokenization, stopword removal)
Converts text into numerical vectors using TF-IDF
Calculates similarity using cosine similarity
Outputs plagiarism percentage

🧠 Tech Stack

Python
NLTK
Scikit-learn
TF-IDF Vectorizer
Cosine Similarity

⚙️ How It Works

Input two text documents
Preprocess text (cleaning, tokenization, stopword removal)
Convert text into vectors using TF-IDF
Calculate cosine similarity
Display similarity score (plagiarism %)

▶️ How to Run

git clone https://github.com/harshitha-123854/Combat-Online-Plagiarism-with-AI
cd Combat-Online-Plagiarism-with-AI
pip install -r requirements.txt
python main.py

📊 Example Output

Input 1: "Machine learning is a subset of AI"

Input 2: "AI includes machine learning techniques"

Output: Similarity Score → 78%

🔥 Key Highlights

Applied NLP techniques for real-world problem solving
Implemented TF-IDF and cosine similarity for text comparison
Designed efficient preprocessing pipeline
