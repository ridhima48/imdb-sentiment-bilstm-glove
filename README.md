# 🎬 IMDb Sentiment Analysis using BiLSTM + GloVe

This project performs binary sentiment classification (positive/negative) on IMDb movie reviews using a deep learning model with a Bidirectional LSTM (BiLSTM) and pre-trained GloVe embeddings.

---

## 📂 Dataset

- **IMDb Movie Review Dataset** (from Kaggle)  
  - 50,000 reviews labeled as **positive** or **negative**  
  - Balanced dataset: 25k positive / 25k negative  
  - [🔗 Download from Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

---

## 🧠 Model Architecture

- **Text Preprocessing**: HTML removal, tokenization, padding  
- **Embeddings**: Pre-trained [GloVe.6B.100d](https://nlp.stanford.edu/data/glove.6B.zip)  
- **Model**:  
  - Embedding Layer (frozen or trainable)  
  - Bidirectional LSTM (64 units)  
  - Dropout  
  - Dense (Sigmoid)  

---

## 📈 Results

| Metric        | Score     |
|---------------|-----------|
| Training Acc  | ~91.1%    |
| Test Acc      | ~88.1%    |

---

## 🚀 How to Run

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/imdb-sentiment-bilstm-glove.git
cd imdb-sentiment-bilstm-glove
