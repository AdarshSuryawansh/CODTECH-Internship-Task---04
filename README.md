# CODTECH-Internship-Task---04
 
---

## Features and Workflow

### 1. Data Loading
- Imported a tweets dataset with sentiment labels.

### 2. Data Preprocessing
- Removed mentions (@user), URLs, hashtags, punctuation, and stopwords.
- Converted text to lowercase for normalization.

### 3. Exploratory Data Analysis (EDA)
- Visualized class distribution using count plots.
- Created WordClouds for positive and negative sentiments.

### 4. Text Vectorization
- Used **TF-IDF Vectorizer** to convert text into numerical format.

### 5. Model Implementation
- Applied **Logistic Regression** for sentiment classification.

### 6. Model Evaluation
- Evaluated using accuracy, classification report, and confusion matrix.

### 7. Insights
- Calculated the percentage of positive and negative tweets.

---

## Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- NLTK  
- WordCloud  

---

## Dataset

You can use any sentiment-labeled text dataset. A sample tweets dataset is used in this project.  
Suggested alternatives:

- Twitter US Airline Sentiment Dataset:  
  https://www.kaggle.com/crowdflower/twitter-airline-sentiment  
- Amazon Reviews Dataset:  
  https://www.kaggle.com/datasets/bittlingmayer/amazonreviews

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/sentiment-analysis-nlp.git
cd sentiment-analysis-nlp
