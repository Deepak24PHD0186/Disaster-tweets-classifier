# disaster-tweet-classifier
A classifier that detects real disaster tweets using NLP

# 🧠 Disaster Tweet Classifier

This project is a submission for the Kaggle competition [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started/overview). The goal is to classify whether a tweet is about a real disaster or not.

---

## 📂 Project Structure


---

## 📊 Dataset

The dataset contains 10,000+ tweets labeled as:
- `1` - tweet refers to a **real disaster**
- `0` - tweet is **not** about a real disaster

Provided by Kaggle:
- [train.csv](https://www.kaggle.com/competitions/nlp-getting-started/data)
- [test.csv](https://www.kaggle.com/competitions/nlp-getting-started/data)
- [sample_submission.csv](https://www.kaggle.com/competitions/nlp-getting-started/data)

---

## 🧹 Preprocessing

- Lowercased text
- Removed URLs, mentions, hashtags, punctuation, numbers
- Tokenization & TF-IDF vectorization

---

## 🤖 Model

We used **Logistic Regression** with TF-IDF features as a baseline model.

### Evaluation Metric
The competition uses the **F1 Score** as the primary evaluation metric.

### Validation Score
Achieved a validation F1 score of **`{0.7085}`**.

---

## 📈 Kaggle Submission

- Public Score on Kaggle: **`{468}`**
- Screenshot of leaderboard position is included in the submission.

---

## 🚀 Future Work

- Implement more advanced models (e.g., LSTM, BERT)
- Improve preprocessing with lemmatization, stemming
- Perform hyperparameter tuning and ensemble models

---

## 🔗 GitHub Repository

All code and files are available in this public repository:  
[https://github.com/your-username/disaster-tweet-classifier](https://github.com/your-username/disaster-tweet-classifier)

---

## 📬 Contact

If you have any questions or feedback, feel free to reach out via GitHub issues!

