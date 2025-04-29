# 🎧 Top 1000 Most Played Spotify Songs — Data Science Project

This project explores a dataset of the **Top 1000 Most Played Songs on Spotify**, applying the full data science workflow: from **data preprocessing** and **exploratory data analysis (EDA)** to **predictive modeling**. The goal is to uncover insights from music streaming data and build a model to predict specific attributes.

---

## 📁 Dataset

- **Source:** `top-1000-most-played-spotify-songs.csv`
- **Size:** 1000 songs
- **Attributes include:** Title, Artist, Genre, Popularity, Release Date, Duration, BPM, Energy, Danceability, and more.

---

## 🔧 Preprocessing Steps

- Converted date columns to datetime format
- Handled missing and invalid values
- Converted duration to minutes
- Removed irrelevant or redundant columns
- Encoded categorical features for modeling

---

## 📊 Exploratory Data Analysis (EDA)

- **Distribution plots** for numeric columns like `popularity`, `duration`, `danceability`, etc.
- **Correlation heatmap** to identify relationships between variables
- **Scatter plots** showing relationships (e.g. duration vs popularity)
- **Bar plots** for top artists and genres
- **Pie charts** to analyze categorical distributions like genres or release decades

---

## 🤖 Predictive Modeling

A **Logistic Regression model** was developed to **predict the genre** of a song based on its numerical attributes, such as:

- Duration
- Popularity
- Danceability
- Energy
- BPM
- Loudness

### ✅ Modeling Steps:

- Label encoding for the target (`genre`)
- One-hot encoding for applicable categorical features
- Feature scaling using `StandardScaler`
- Train-test split
- Model training and evaluation using:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix

---

## 🛠️ Tools & Libraries Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn** for visualization
- **Scikit-learn** for preprocessing and modeling
- **Jupyter Notebook** for implementation

---

## 🔎 Key Insights

- Certain artists appear multiple times in the top 1000 list.
- Higher danceability and energy scores often correlate with popularity.
- Genre prediction from acoustic features shows moderate accuracy — can be improved with more advanced models or textual/audio data.

---




