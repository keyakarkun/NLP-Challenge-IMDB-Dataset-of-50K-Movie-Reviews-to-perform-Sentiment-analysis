# NLP-Challenge-IMDB-Dataset-of-50K-Movie-Reviews-to-perform-Sentiment-analysis

# IMDB Sentiment Analysis

## 📌 Project Overview
This project performs **Sentiment Analysis** on the **IMDB 50K Movie Reviews** dataset using **Deep Learning (LSTM)**. It classifies reviews as **positive** or **negative** using Natural Language Processing (NLP) techniques.

## 🚀 Features
- **Data Preprocessing:** Tokenization, padding, and text cleaning.
- **LSTM Model:** Used for better contextual understanding of text.
- **Model Training & Evaluation:** Trained using TensorFlow/Keras.
- **Deployment:** Built a Streamlit-based web app for real-time predictions.

## 📂 Dataset
- **Source:** [IMDB 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Structure:** CSV file with two columns:
  - `review`: The text of the movie review.
  - `sentiment`: Label (positive/negative), converted to binary (1, 0).

## ⚙️ Installation
### **1. Clone the Repository**
```bash
git clone https://github.com/keyakarkun/NLP-Challenge-IMDB-Dataset-of-50K-Movie-Reviews-to-perform-Sentiment-analysis
cd NLP-Challenge-IMDB-Dataset-of-50K-Movie-Reviews-to-perform-Sentiment-analysis
```

## 🏗️ Model Training
1. **Run the Jupyter Notebook (Colab)** to preprocess data and train the model:
   ```bash
   python train_model.py
   ```
2. **Saved Outputs:**
   - `sentiment_analysis_model.h5`: Trained LSTM model.
   - `tokenizer.pkl`: Tokenizer for text preprocessing.

## 🌐 Web App (Streamlit)
### **Run Locally**
```bash
streamlit run app.py
```
### **Deploy Online (Optional)**
Using LocalTunnel:
```bash
npx localtunnel --port 8501
```

## 📊 Model Performance
- **Loss & Accuracy:** Evaluated using binary cross-entropy.
- **Metrics:** Accuracy, Precision, Recall, F1-score.

## 🔮 Future Improvements
- Implement **BERT or Transformer models** for better accuracy.
- Deploy using **Flask/FastAPI with cloud hosting**.

## 🤝 Contributing
Feel free to submit **pull requests** or **open issues** to improve this project.

## 📜 License
This project is open-source under the **MIT License**.

---

## Video link: https://youtu.be/wMxJ84yffco
💡 **Made by [Keya Karkun]** 🚀

