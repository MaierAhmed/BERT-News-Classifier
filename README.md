📰 BERT News Classifier

An end-to-end Natural Language Processing (NLP) project that fine-tunes **BERT (Bidirectional Encoder Representations from Transformers)** for multi-class news classification and deploys it using a Flask web application.

This project demonstrates practical implementation of transformer-based models for real-world text classification tasks.

---

## 🧠 Project Overview

News articles are categorized into different topics such as:

- Politics
- Sports
- Business
- Technology
- Entertainment

This project uses a **fine-tuned BERT model** to automatically classify news headlines or content into their respective categories with high accuracy.

The system includes:

- Model training notebook
- Saved model artifacts (excluded from Git due to size)
- Label mapping
- Flask deployment app

---

## ✨ Key Features

- Fine-tuned BERT for text classification
- Multi-class prediction
- Confusion matrix evaluation
- Flask-based deployment
- Lightweight and clean repository
- Easy-to-extend architecture

---

## ⚙️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Flask
- Jupyter Notebook

---

## 📂 Project Structure

BERT-News-Classifier/
│
├── app.py
├── bert-news.ipynb
├── label_mapping.json
├── requirements.txt
├── .gitignore
└── README.md


> **Note:** Model files (`model.safetensors`) are not included due to GitHub size limits. See instructions below.

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/BERT-News-Classifier.git
cd BERT-News-Classifier
2️⃣ Create a virtual environment
python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate  # Mac/Linux
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Run Flask App
python app.py
Open in your browser:

http://127.0.0.1:5000/
📥 Download Pre-trained Model
Due to GitHub file size limits, the model is not included.
Download the fine-tuned model here:

[Hugging Face / Google Drive Link]

Place the downloaded model in:

bert-news-classifier/
🧪 Example Input
The government announced new economic reforms today.
The football team secured a dramatic victory in the final minutes.
📊 Model Details
Pretrained Model: bert-base-uncased

Fine-tuned for multi-class news classification

Optimizer: AdamW

Evaluation Metric: Accuracy & Confusion Matrix

🚀 Future Improvements
Deploy on cloud (Render / AWS / Railway)

Add REST API endpoints

Add Docker support

Implement batch prediction

Improve UI design

👩‍💻 Author
AI/ML Enthusiast focused on building practical NLP applications using transformer-based models.
