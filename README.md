# Tweet Sentiment Analysis using GloVe Embeddings and BiLSTMs  

This project performs sentiment analysis on tweets using **GloVe word embeddings** and a **Bidirectional LSTM (BiLSTM) model**. It also explores **non-finetuned BERT embeddings** to analyze whether finetuning improves performance. The results show that **finetuning embeddings is essential** for achieving high accuracy in sentiment classification.

---

## 📌 Features  
- **Pretrained GloVe embeddings** with finetuning for improved sentiment classification.  
- **Comparison with non-finetuned BERT embeddings**, demonstrating poor performance.  
- **BiLSTM architecture** to capture contextual dependencies in tweets.  
- **Comprehensive preprocessing**, including tokenization, stopword removal, and sequence padding.  
- **Evaluation using accuracy, precision, recall, and F1-score.**  

---

## 📂 Dataset  
- The dataset consists of tweets labeled as ** extremely positive (4),positive(3),neutral (0), negatiave(1), extremely negative (2)**.  
- Preprocessing steps include:  
  - Removing stopwords and special characters.  
  - Tokenizing and padding sequences.  
  - Converting words into embeddings using GloVe/BERT.

---

## 🚀 Key Findings  

| Embedding Type      | Accuracy | Precision | Recall | F1-score |
|--------------------|----------|-----------|--------|----------|
| **Non-Finetuned BERT** | Low | Low | Low | Low |
| **Finetuned GloVe** | High | High | High | High |

- **Non-finetuned BERT embeddings performed poorly**, suggesting that domain-specific finetuning is crucial.  
- **Finetuned GloVe embeddings outperformed BERT**, proving the importance of fine-tuning word representations in NLP tasks.  

---


