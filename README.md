# Spotify Performance Analysis & Segmentation

An end-to-end Exploratory Data Analysis (EDA) and Machine Learning (ML) pipeline designed to analyze Spotify track metrics, uncovering the dynamics between daily streaming velocity and lifetime catalog accumulation[cite: 1]. 

By applying data preprocessing, exploratory visual analytics, and unsupervised K-Means clustering, this project categorizes songs into distinct commercial performance tiers to automate the identification of high-potential tracks[cite: 1].

---

## Project Structure

* **Data Cleaning & Engineering:** Standardized column formatting, stripped trailing whitespaces, handled missing values via mean/removal strategies, split composite artist/track strings, and cast numeric parameters[cite: 1].
* **Exploratory Data Analysis:** Conducted visual correlation analyses using Seaborn heatmaps and bar charts to evaluate cross-platform metrics (Spotify, YouTube, TikTok, Pandora, Deezer)[cite: 1].
* **Machine Learning Pipeline:** Feature scaling via `StandardScaler` followed by K-Means clustering to segment tracks into four commercial performance profiles[cite: 1].

---

## Commercial Track Tiers

* **Quiet Catalog:** Tracks with lower daily velocity and minimal playlist placement[cite: 1].
* **Steady Performers:** Mid-tier songs maintaining consistent stream accumulation over time[cite: 1].
* **Legacy Giants:** Historical tracks with massive lifetime streams and deep playlist reach[cite: 1].
* **Elite Hits:** High-velocity tracks demonstrating peak daily momentum and maximum platform exposure[cite: 1].

---

## Key Findings

* **Momentum Correlation:** Identified a strong positive correlation ($r = 0.56$) between daily streaming velocity and long-term catalog retention[cite: 1].
* **Automated Asset Categorization:** Constructed a scalable framework to transform raw cross-platform streaming statistics into clear indicators of lifetime accumulation potential[cite: 1].

