# Customer-Sentiment-Analysis-Using-NLP
Developed an end-to-end Customer Sentiment Analysis system using Natural Language Processing (NLP) to analyze and classify customer reviews and feedback into positive, negative, and neutral sentiments. The project focused on extracting meaningful insights from large volumes of unstructured textual data to understand customer opinions 

Features :
Text preprocessing & sentiment classification

Trained ML model loaded using Joblib

Streamlit web app for real-time sentiment prediction

Supports user-entered text input


Python

Scikit-learn

NumPy

Joblib

NLP techniques (TF-IDF, text cleaning)


Project Files

├── Sentiment analysis using NLP.ipynb   # Model training & analysis

├── main.py                              # Streamlit app

├── model.pkl                            # Trained model

├── requirements.txt                    # Dependencies

How to Run
pip install -r requirements.txt
streamlit run main.py

Output :
User enters text
Model predicts sentiment as Positive / Negative / Neutral

Future Scope:
Improve accuracy using deep learning (LSTM / BERT)
Add sentiment visualization dashboard
Deploy as a web application
