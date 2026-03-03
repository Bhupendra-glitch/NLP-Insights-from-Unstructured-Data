# 📊 NLP Insights from Unstructured Data  
## Sentiment Analysis using Python, VADER & Transformers

---

## 🚀 Project Overview

This project performs **Sentiment Analysis on unstructured text data** using multiple Natural Language Processing (NLP) techniques.

The objective is to classify customer reviews into:
- ✅ Positive  
- ❌ Negative  
- ➖ Neutral  

The project compares traditional lexicon-based methods with modern transformer-based deep learning models.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Hugging Face Transformers
- PyTorch

---

## 📂 Project Structure



---

## 📊 Dataset

- **Amazon Fine Food Reviews Dataset**
- Contains customer review text and ratings
- Used to evaluate sentiment prediction models

---

## 🔎 Project Workflow

### 1️⃣ Data Loading & Exploration
- Load dataset using Pandas
- Perform basic Exploratory Data Analysis (EDA)
- Visualize rating distribution

### 2️⃣ Text Preprocessing
- Lowercasing text
- Removing special characters
- Tokenization
- Stopword removal

### 3️⃣ Sentiment Analysis Techniques

#### ✅ Method 1: VADER (Lexicon-Based Approach)
- Rule-based sentiment analyzer
- Outputs:
  - Positive score
  - Negative score
  - Neutral score
  - Compound score

#### ✅ Method 2: RoBERTa Pretrained Transformer
- Context-aware sentiment analysis
- Better handling of sarcasm and complex sentences
- Uses Hugging Face Transformers

#### ✅ Method 3: Hugging Face Pipeline
- Simplified high-level API
- Quick sentiment predictions

---

## 📈 Results & Insights

- Transformer-based models outperform lexicon-based methods in contextual understanding.
- VADER works well for simple, short reviews.
- RoBERTa provides more accurate sentiment classification for complex text.

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/NLP_Insights_from_Unstructured_Data.git

Kaggle - https://www.kaggle.com/code/robikscube/sentiment-analysis-python-youtube-tutorial/notebook
