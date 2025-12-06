# 🎧 Spotify Top-50 Global Dashboard — Power BI Project  
### **By: Mohammad Kaif Firoz**

An end-to-end Power BI dashboard analyzing Spotify’s *Top 50 Global* dataset.  
This project transforms raw ranking data into a complete analytics platform for playlist managers, music analysts, and marketing teams.

---

## 📌 1. Business Requirement

Spotify stakeholders needed a centralized dashboard that provides:

- KPIs (Total Songs, Distinct Artists, Avg Popularity, Avg Duration)
- Explicit vs Non-Explicit performance comparison  
- Album Type distribution (single, album, compilation)  
- Popularity & Song trends across months and years  
- Artist-level intelligence (consistency, #1 hits, popularity rank)  
- Song-level insights (release date, duration, popularity, positions)  

The raw dataset provided only rankings, making trend analysis slow and inefficient.  
This dashboard solves that problem by providing **clarity, insights, and decision-making power**.

---

## 🎯 2. Analytical Goals

The dashboard answers key business questions:

- Which artists dominate the global charts?
- What type of music performs best (single, album, compilation)?
- Do explicit songs perform differently than non-explicit ones?
- Who are the consistent hit-makers (#1 position holders)?
- What are the monthly and yearly trends in popularity and distinct songs?
- Which songs and artists show the strongest audience engagement?

---

## 🧹 3. Data Preparation & Modeling

Dataset fields included:

`date`, `position`, `song`, `artist`, `popularity`, `duration_ms`,  
`album_type`, `total_tracks`, `release_date`, `is_explicit`, `album_cover_url`

### Steps taken:

- Cleaned dataset & standardized column formats  
- Converted date fields to proper types  
- Created **Year** and **Month** columns for time intelligence  
- Built a separate **_Measure table** for all DAX metrics  
- Created 30+ custom DAX measures  
- Added ranking logic, hit analysis, and popularity trends  
- Designed a high-performance data model

---

## 📊 4. Dashboard Pages & Key Insights

---

### 🏠 **Home Page**
- Spotify-themed UI  
- Simple navigation → *Overview | Artist | Songs*  
- App-like clean interface  

---

### 📈 **Overview Page**

#### **KPIs**
- Distinct Songs  
- Distinct Artists  
- Avg Duration  
- Avg Popularity  

#### **Visuals**
- Songs by Album Type  
- Explicit vs Non-Explicit comparison  
- Songs by Year (2023 vs 2024)  
- Avg Popularity Trend (Month / Quarter toggle)  
- Distinct Songs by Month  
- Top Artists & Top Songs  

Provides a complete **macro-level** understanding of music trends.

---

### 🎤 **Artist Page**

#### Visuals include:
- Distinct Songs per Artist  
- Popularity by Artist  
- #1 Hits per Artist  
- Artist Cards with album art  

#### Artist Table includes:
- Song Appearances  
- Album Count  
- Avg Popularity  
- Popularity Rank  
- Best & Worst Position  

Helps identify:
- Consistent hit-makers  
- Most popular artists  
- Artists with strong upward trends  

---

### 🎵 **Songs Page**

#### Shows:
- Song Popularity  
- Song Appearances  
- #1 Hits per Song  
- Release Date  
- Album Type  
- Avg Popularity, Max Popularity  
- Avg Duration  

Supports playlist curation, marketing, & audience understanding.

---

## 🧠 5. Key Insights

- Taylor Swift, Billie Eilish, SZA among highest-appearing artists  
- Explicit songs perform strongly and are widely present  
- Singles dominate over albums in total track appearances  
- 2024 songs show higher average popularity vs 2023  
- Some artists consistently achieve top (#1) positions  
- Popularity trends show seasonal shifts across months  

---

## ⚙️ 6. Tools & Techniques

- Power BI  
- DAX (30+ optimized measures)  
- Time Intelligence Functions  
- Ranking Logic  
- Drill-through Navigation  
- Customized Spotify-Themed UI  
- Performance Optimization (measure table, fewer calculated columns)

---

## 🧮 7. Important DAX Measures

- Distinct Songs  
- Distinct Artists  
- Avg Popularity  
- Avg Duration  
- Explicit Percentage  
- Songs per Artist  
- Song Appearances  
- #1 Hits per Artist  
- Popularity Rank  
- YoY Popularity  
- Monthly Popularity Trend  

---

## 📘 8. Final Storytelling Summary (Interview-Friendly)

“I built an end-to-end Spotify Top-50 analytics dashboard in Power BI.  
The goal was to convert raw ranking data into actionable insights for playlist curators and marketing teams.  
I created KPIs, trend analysis, ranking logic, and drill-down views for artists and songs.  
The dashboard replicates Spotify’s UI for a clean experience, includes a measure table, and uses 30+ DAX measures.  
It reveals insights on popularity trends, album types, explicit content behavior, and artist consistency.”

---

## 📁 9. Repository Structure


---

## 👨‍💻 10. Author

**Mohammad Kaif Firoz**  
Data Analyst — SQL | Power BI | Excel | Tableau | Python  

📧 Email: kaifsidd2003@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/kaiffiroz/  

---

⭐ *If you found this project useful, please consider giving the repository a star!* ⭐
