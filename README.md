# 🎶 Spotify Top 200 Charts 2020 - Exploratory Data Analysis

## 📌 Project Overview
In the age of digital music streaming, platforms like **Spotify** have transformed how people listen to music.  
This project explores Spotify’s **Top 200 Charts (2020)** dataset to uncover insights about:
- Listening habits  
- Artist popularity  
- Genre distribution  
- Relationships between audio features and song popularity  
- Global music trends  

Dataset Link: [Spotify Top 200 Charts 2020 (Kaggle)](https://www.kaggle.com/datasets/iamsumat/spotify-top-200-charts-2020)

---

## ❓ EDA Questions
1. How many unique artists are in the dataset?  
2. What is the distribution of song popularity scores?  
3. Which artists appear most frequently in the Top 200?  
4. What are the most common genres?  
5. What is the average duration of songs?  
6. How do audio features like **danceability, energy, valence** vary across genres?  
7. Which countries contribute the most to the top charts?  

---

## 📊 Visualizations
1. **Bar Chart** → Top 10 artists by number of chart appearances  
2. **Histogram** → Distribution of song popularity scores  
3. **Boxplot** → Danceability across different genres  
4. **Heatmap** → Correlation between audio features (danceability, energy, valence, tempo, loudness)  
5. **Line Chart** → Popularity trend over time  
6. **Scatter Plot** → Energy vs Loudness (colored by genre)  
7. **Pie Chart** → Explicit vs Non-explicit songs  

---

## 📈 Sample Insights
- Identified the most frequent artists in the **Top 200 charts**.  
- Discovered trends in **song popularity distribution**.  
- Compared how **audio features** (danceability, energy, valence) vary across genres.  
- Visualized **global contribution of countries** to the top charts.  
- Analyzed characteristics of **explicit vs non-explicit songs**.  

---

## 🚀 Tech Stack
- **Python**  
- **Pandas, NumPy** – Data analysis  
- **Matplotlib, Seaborn** – Visualization  
- **Jupyter Notebook**  

---

## 📂 Project Structure
```
Spotify-EDA/
│── notebooks/
│   └── Spotify_EDA.ipynb        # Analysis & plots
│── data/
│   └── spotify_top200.csv       # Dataset (not uploaded if large)
│── images/                      # Saved plots for README
│── requirements.txt             # Dependencies
│── README.md                    # Project documentation
```

---

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Spotify-EDA.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Spotify-EDA
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/Spotify_EDA.ipynb
   ```

---

## 📜 License
This project is for **educational purposes** only.
