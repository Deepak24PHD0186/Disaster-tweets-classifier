# 🧠 Tweet Classification Using NLP and BERT

This project applies **Natural Language Processing (NLP)** techniques to classify tweet data based on features like keywords, location, and sentiment. Leveraging transformer models (such as **BERT**), the goal is to accurately categorize tweets—particularly for disaster-related classification—by processing and analyzing large-scale textual data.

---

## 📌 Features

- ✅ Text preprocessing: HTML cleaning, lowercasing, stopword removal  
- ✅ TF-IDF vectorization and word embedding techniques  
- ✅ BERT-based model fine-tuning using TensorFlow/Keras  
- ✅ Evaluation with classification report and confusion matrix

---

## 📂 Dataset

This project works with tweet data labeled as real or not real (e.g., whether a tweet is about a real disaster). A common dataset used is:

> **[Real or Not? NLP with Disaster Tweets - Kaggle](https://www.kaggle.com/competitions/nlp-getting-started)**

Make sure the dataset includes columns such as `text`, `target`, `location`, and `keyword`.

---

## 🛠️ Installation


Install all the requirements using pip codes.

**### Download required NLTK resources:**

import nltk
nltk.download('stopwords')

🧪 Usage
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Week-04_NLP_tweets.ipynb
Ensure GPU is enabled for faster training (especially for BERT):

python
Copy
Edit
import torch
print(torch.cuda.is_available())  # True means GPU is available
📈 Output
Cleaned and preprocessed tweet text


Tokenized sequences



BERT-based classification model

Confusion matrix and classification report with precision, recall, and F1 score

## Results and Analysis

### Results:
The Naive Bayes model achieved an accuracy of 83% on the test data. The confusion matrix shows that the model performs well on Class A but struggles with Class B.

### Analysis:
The model performed well on the majority class, but its performance on the minority class could be improved. We plan to try different hyperparameters and other models, such as Logistic Regression, to improve performance.


📎 Dependencies

transformers

tensorflow

keras

torch

nltk

scikit-learn

pandas

matplotlib

spacy

beautifulsoup4

👤 Author
Your Name
GitHub: @Deepak24PHD0186

📄 License
This project is licensed under the MIT License.
---




