📰 Fake News Detection Using Machine Learning
This project uses natural language processing and machine learning to classify news articles as real or fake based on their content.

📁 Dataset
Source: Fake and Real News Dataset on Kaggle

Features used: text

Target: label (0 = Real, 1 = Fake)

🔧 Algorithm Used
Logistic Regression (TF-IDF based)

📊 Evaluation (on test set)
Accuracy: 0.96 (approx.)

Precision, Recall, and F1-Score: Provided via classification_report

📈 Visuals
Confusion Matrix Heatmap

Sample Predictions for custom input

🚀 How to Run
Open the notebook on Google Colab

Upload the dataset (Fake.csv, True.csv) or mount Google Drive

Run Fake News.ipynb

Try out your own news samples for prediction

✅ Future Work
Use advanced models like Random Forest, XGBoost, or Deep Learning (LSTM)

Add web interface using Flask or Streamlit

Integrate pre-trained word embeddings like GloVe or Word2Vec