# 📧 Deep Learning for Email Spam Classification using LSTM and Word2Vec

This project focuses on building a deep learning model for classifying emails as **spam** or **ham (non-spam)** using an LSTM neural network and custom-trained Word2Vec embeddings.

## 🧠 Project Overview

We used:
- A labeled dataset of emails (ham/spam)
- Word2Vec to create word embeddings from email text
- A Keras LSTM model for classification
- Train/Validation/Test split (70/15/15)

### 🛠 Tech Stack
- Python
- TensorFlow / Keras
- Gensim (Word2Vec)
- NumPy / Pandas / scikit-learn

---

## 📊 Model Performance

| Metric         | Ham (0) | Spam (1) |
|----------------|---------|----------|
| **Precision**  | 0.93    | 0.66     |
| **Recall**     | 0.96    | 0.53     |
| **F1-Score**   | 0.94    | 0.58     |

**Overall Accuracy:** 90%

While the model performs well for non-spam detection, improvements are needed in spam detection (class imbalance may be a factor).

---

## 📁 Project Structure

```bash
├── Dataset.csv
├── email_classification_lstm_word2vec.ipynb
├── README.md
