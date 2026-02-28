# PolariSense--IMDB-Sentiment-Intelligence

📌 Project Overview

PolariSense is a sentiment analysis system built on the IMDB 50K movie reviews dataset.

This project compares traditional machine learning techniques with deep learning models to analyze and classify movie reviews as positive or negative.

The goal was to understand:

- The effectiveness of TF-IDF based models.
- The performance of LSTM and Bidirectional LSTM architectures.
- The impact of preprocessing and sequence length in NLP tasks.

📂 Dataset

- IMDB 50,000 Movie Reviews Dataset
- Balanced dataset (25,000 positive / 25,000 negative reviews)

⚙️ Models Implemented:

1️⃣ TF-IDF + Logistic Regression

- Unigram & Bigram features
- max_features = 5000
- Logistic Regression classifier

2️⃣ LSTM

- Embedding layer
- LSTM (128 units)
- Dropout regularization
- max_len = 200

3️⃣ Bidirectional LSTM

- Embedding layer
- Bidirectional LSTM (128 units)
- Dropout regularization
- max_len = 200

📊 Final Model Performance

Model	                       Accuracy
TF-IDF	                        89.29%
LSTM	                        86.40%
Bidirectional LSTM	            86.77%

🧠 Key Learnings

- Classical ML models like TF-IDF can outperform deep learning on structured sentiment datasets.
- Sequence length significantly affects LSTM performance.
- Removing whitespace incorrectly can completely break NLP pipelines.
- Debugging preprocessing steps is as important as model tuning.

🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- TensorFlow / Keras
- Matplotlib / Seaborn

🚀 Future Improvements

- Pretrained embeddings (GloVe / FastText)
- Hyperparameter tuning
- Transformer-based models (BERT)
- Deployment using Streamlit

📎 How to Run

- Clone the repository
- Install dependencies
- Run the notebook CineSentix_AI_IMDB_Sentiment_Analysis.ipynb

📌 Conclusion

This project demonstrates that traditional machine learning models like TF-IDF with Logistic Regression can perform extremely well on structured sentiment datasets, achieving the highest accuracy of 89.29%.
While LSTM and Bidirectional LSTM models provided strong contextual learning capabilities, they required careful preprocessing and sequence length tuning to reach competitive performance. Overall, this project highlights the importance of data preprocessing, baseline comparison, and systematic experimentation in NLP workflows.

Author: Pulkit Chhabra
Aspiring Data Scientist & AI Developer