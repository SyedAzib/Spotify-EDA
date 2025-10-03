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
## 📈 Sample Insights
- Identified the most frequent artists in the **Top 200 charts**.  
- Discovered trends in **song popularity distribution**.  
- Compared how **audio features** (danceability, energy, valence) vary across genres.  
- Visualized **global contribution of countries** to the top charts.  
- Analyzed characteristics of **explicit vs non-explicit songs**.  

---

## 📊 Example Visualizations
1. **Bar Chart** → Top 10 artists by number of chart appearances
![Bar chart](Visualization/spotify.1.png)

3. **Heatmap** → Correlation between audio features (danceability, energy, valence, tempo, loudness)
![Heatmap](Visualization/spotify.4.png)

4. **Line Chart** → Popularity trend over time
![Line chart](Visualization/spotify.5.png)    


---



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
