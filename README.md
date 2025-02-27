# Arabic Sentiment Analysis Using Deep Learning  

## 📌 Project Overview  
This project is part of the **Orange Digital Hub Egypt** training program, where I developed a **sentiment analysis model** for Arabic text using **deep learning and NLP techniques**. The goal is to classify the sentiment of Arabic reviews using various neural network architectures.  

## 🚀 Key Features  
- **Preprocessing**:  
  - Cleaned **330K+ Arabic reviews** (removed emojis, punctuation, stopwords).  
  - Applied **AraBERTv02 preprocessor** to remove **Tashkeel & Tatweel**.  
  - Used **BERT-based embeddings** for feature extraction.  
- **Model Development**:  
  - Implemented and evaluated four models:  
    - ✅ **RNN**  
    - ✅ **LSTM**  
    - ✅ **Bi-RNN**  
    - ✅ **Bi-LSTM**  
  - Fine-tuned **GPT-2** for sentiment classification.  
- **Evaluation**: Compared model performances to optimize accuracy.  

## 🛠️ Technologies Used  
- **Python**  
- **TensorFlow, Keras**  
- **Hugging Face Transformers**  
- **AraBERT (BERT-based Arabic Model)**  
- **GPT-2 Fine-Tuning**  

## 📂 Dataset  
The dataset used is **[330K Arabic Sentiment Reviews Dataset (Kaggle)]([https://www.kaggle.com/datasets/](https://www.kaggle.com/datasets/abdallaellaithy/330k-arabic-sentiment-reviews))**. (You may replace this with the actual dataset link.)  

## 🔧 How to Run the Project  
### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Aliha7ish/arabic-sentiment-analysis.git
cd arabic-sentiment-analysis

## Install Dependencies
```bash
pip install -r requirements.txt

## Run the Model
```bash
python sentiment-analysis.ipynb

