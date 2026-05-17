# Twitter Sentiment Analysis Using Machine Learning

## Project Overview
This project focuses on Twitter sentiment analysis using Natural Language Processing (NLP) and Machine Learning techniques. The system classifies Twitter text into sentiment categories using TF-IDF feature extraction and supervised machine learning models.

---

## Objectives
- Perform text preprocessing on Twitter data
- Convert text into numerical vectors using TF-IDF
- Train machine learning models
- Compare model performances
- Evaluate sentiment classification accuracy

---

## Dataset
The dataset used in this project:
- twitter_training.csv
- twitter_validation.csv

The dataset contains:
- Tweet ID
- Topic
- Sentiment Label
- Tweet Text

---

## Data Preprocessing
The following preprocessing techniques were applied:
- Lowercasing text
- Removing URLs
- Removing usernames and hashtags
- Removing punctuation and special characters
- Removing stopwords
- Lemmatization
- Removing duplicate records

---

## Feature Extraction
TF-IDF (Term Frequency–Inverse Document Frequency) was used to convert textual data into numerical feature vectors.

---

## Machine Learning Models
The following models were implemented:
1. Naive Bayes
2. Support Vector Machine (SVM)
3. Logistic Regression

---

## Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve

---

## Project Visualizations
The project includes:
- Accuracy Comparison Graph
- Confusion Matrix Heatmap
- Classification Report Heatmap
- ROC Curve Analysis

---

## Technologies Used
- Python
- Jupyter Lab
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn

---

## Results
The machine learning models successfully classified Twitter sentiments using TF-IDF features and supervised learning algorithms.

---

## Future Improvements
Possible future improvements include:
- Deep Learning Models (LSTM, CNN)
- Transformer Models (BERT)
- Word Embeddings
- Larger Balanced Datasets

---

## Results

The following machine learning models were evaluated for Twitter sentiment classification:

| Model | Accuracy |
|-------|-----------|
| Naive Bayes | 0.69 |
| SVM | 0.73 |
| Logistic Regression | 0.72 |

### Final Observation
- Support Vector Machine (SVM) achieved the highest classification accuracy.
- TF-IDF feature extraction improved text representation performance.
- Machine learning models successfully classified Twitter sentiments with strong performance.
- SVM performed best for sparse textual feature vectors.

### Visualizations Included
- Accuracy Comparison Graph
- <img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/c6922b51-f00b-4c24-9875-63857897b29c" />

- Confusion Matrix Heatmap
- <img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/e1420547-00d9-4f93-85b0-a4290ad03f3d" />

- Classification Report Heatmap
- <img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/c031c391-9ff5-43dc-ab41-3b871b3930f7" />

- ROC Curve Analysis
- <img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/47c8c376-0a8e-4093-9b00-db651358395d" />
