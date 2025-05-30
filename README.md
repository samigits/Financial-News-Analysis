# 📈 Financial News Dataset EDA & Analysis

This project performs **Exploratory Data Analysis (EDA)** and **Text & Time Series Analysis** on a large CSV file of financial news articles.  

The dataset includes the following fields:
- **headline**: Title of the news article (may include stock movements, earnings, etc.)
- **url**: Link to the full article
- **publisher**: Name or email of the article’s publisher
- **date**: Publication date and time (with timezone information)
- **stock**: Stock ticker symbol associated with the article

---

## 🔍 Analysis Roadmap

### 📊 1. Descriptive Statistics
- **Headline Lengths**: Calculate summary statistics (mean, median, max) for headline lengths.
- **Top Publishers**: Count articles per publisher and identify the most active sources.
- **Publication Trends**: Analyze publication frequency over time to detect spikes or market events.

### 📝 2. Text Analysis (Topic Modeling)
- **Common Keywords**: Use NLP techniques to extract frequent words or phrases (e.g. "price target", "earnings report").
- **Optional**: Perform LDA topic modeling to uncover major themes in headlines.

### 🕒 3. Time Series Analysis
- **Publication Frequency**: Visualize daily or weekly article volume to identify market patterns.
- **Publishing Times**: Analyze hours of day when most news is released (crucial for traders).

### 📰 4. Publisher Analysis
- **Top Publishers Over Time**: Examine trends of different publishers' contributions.
- **Email Domain Extraction**: Identify organizations contributing most frequently by extracting email domains from publisher fields.

---

## 🛠️ Tools & Libraries
- **Python** 🐍
  - `pandas`: Data manipulation and analysis
  - `matplotlib`, `seaborn`: Data visualization
  - `scikit-learn`: Feature extraction and NLP (e.g., `CountVectorizer`)
  - `nltk` or `spaCy`: Text preprocessing (optional)
- **Jupyter Notebook** or any Python environment

---

## 🚀 How to Run
1. **Clone this repository**:
    ```bash
    git clone https://github.com/yourusername/financial-news-eda.git
    cd financial-news-eda
    ```
2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Run analysis notebook**:
    ```bash
    jupyter notebook analysis.ipynb
    ```
4. **Replace `path_to_your_file.csv`** in the code with your actual CSV file path.

---

## 📈 Example Visualizations
- 📊 Headline length distribution
- 🏢 Top publishers by article count
- 📅 Articles published over time
- 🕒 Publication time by hour of day
- 🔑 Top keywords and phrases from headlines
- 📨 Publisher domains (if email addresses are present)

---

## 📂 Folder Structure
financial-news-eda/
├── data/
│ └── your_data.csv
├── notebooks/
│ └── analysis.ipynb
├── requirements.txt
└── README.md


## 📬 Contributions
Contributions, improvements, and ideas are welcome! Please open an issue or submit a pull request.

---

## 📜 License
This project is licensed under the MIT License.