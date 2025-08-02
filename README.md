# 💬 Social Media Sentiment Analysis & Visualization

This project analyzes and visualizes **sentiment patterns** in social media data to understand public opinion and user attitudes towards specific **topics** or **brands**. It leverages natural language processing techniques to classify sentiments and reveal insights through interactive visualizations.

---

## 🎯 Objective

To:
- Extract sentiment (positive, negative, neutral) from user-generated social media posts
- Understand public perception of topics/brands over time
- Visualize sentiment trends and keyword associations

---

## 📁 Dataset

- **Source**: https://www.kaggle.com/datasets/jp797498e/twitter- entity-sentiment-analysis
- **Format**: CSV/JSON with fields like:
  - `text` (post content)
  - `timestamp`
  - `user`
  - `location`

---

## 🛠️ Technologies Used

- Python
- NLP with **TextBlob** / **VADER** / **Transformers**
- **Pandas** and **NumPy** for data handling
- **Matplotlib** and **Seaborn** for static plots
- **Plotly** / **WordCloud** for interactive visuals
- Jupyter Notebook

---

## 🧠 Workflow

1. **Data Collection**
   - Load data from APIs or public datasets

2. **Preprocessing**
   - Clean text (remove URLs, emojis, stopwords, etc.)
   - Tokenization & normalization

3. **Sentiment Analysis**
   - Apply VADER/TextBlob for polarity scoring
   - Classify into Positive / Negative / Neutral

4. **Visualization**
   - Sentiment distribution bar charts
   - Time series plot of sentiment over time
   - Word clouds of common keywords

---

## 📊 Sample Visuals

- 📈 Sentiment Trend Over Time  
- 🧠 Most Frequent Positive/Negative Words  
- 📍 Sentiment by Location 



---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Sid-pr/CODECRAFT_DS_04.git
   cd social-media-sentiment-analysis

2. Install Dependencies:
   ```bash
   pip install -r requirements.txt
   
4. Run the jupiter notebook:
   ```bash
   jupyter notebook sentiment.ipynb
