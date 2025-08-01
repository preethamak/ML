#  Social Media Sentiment Analysis Dashboard

A complete data analytics project combining Python and Power BI to explore emotions, engagement, and user behavior from real social media data. The project highlights how different sentiments influence likes, retweets, and platform dynamics.

---

##  Dataset Overview

- **File**: `Sentiment dataset.csv`
- **Columns**:
  - `timestamp`: When the post was made
  - `text`: Content of the social media post
  - `sentiment`: Emotion label (e.g., Joy, Frustration, Positive)
  - `likes`, `retweets`: Engagement metrics
  - `platform`, `country`, `user`: Metadata for context

---

##  Project Goals

- Visualize the **distribution of emotional tone** in posts
- Analyze **likes and retweets** across platforms
- Study **posting activity patterns** over time
- Use **NLP techniques** to find common words for each sentiment
- Build a clean and **interactive Power BI dashboard**

---

## 🧪 Python Preprocessing & NLP

All data preparation was performed using Python in Google Colab or Jupyter Notebook:

- Removed missing and duplicate entries
- Cleaned and standardized sentiment labels
- Tokenized and analyzed frequent words in post text
- Created:
  - `3) sentiment_cleaned.csv` – used in Power BI
  - Word clouds per sentiment
  - Bar charts showing top words by emotion

---

##  Power BI Visualizations

| Visual Type      | Description                                       |
|------------------|---------------------------------------------------|
| **Pie Chart**     | Overall sentiment distribution                   |
| **Bar Chart**     | Average likes per platform                       |
| **Line Chart**    | Sentiment trends by hour                         |
| **KPI Cards**     | Key metrics: max likes, avg tokens, total posts |
| **Slicers**       | Filters for platform and country                 |
| **Image Visuals** | Embedded word clouds (optional)                 |

---

##  Dashboard Title

> **Social Media Sentiment Analysis Dashboard**  
> *Tracking Emotions, Engagement & Patterns from User Posts*

---

##  How to Use

1. Open `3) sentiment_cleaned.csv` 
2. Rebuild visuals or import from a `.ipynb` file  
3. Add slicers for interactivity (platform, country)  
4. (Optional) Embed word clouds for deeper insight  

---

##  Tools & Technologies

- **Python** – `pandas`, `seaborn`, `wordcloud`, `matplotlib`
- **Jupyter / Google Colab** – Data cleaning, analysis, NLP

---

##  Created By

**Preetham AK**  
