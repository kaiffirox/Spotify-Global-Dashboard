# 🎧 Spotify Top-50 Global Dashboard — Power BI Project  
### **By: Mohammad Kaif Firoz**

An end-to-end Power BI dashboard analyzing Spotify’s *Top 50 Global* dataset.  
This project transforms raw ranking data into a complete analytics platform for playlist managers, music analysts, and marketing teams.

---

## 📂 Project Files Included

| File Name | Description |
|----------|-------------|
| **Spotify Dashboard Analysis KAIF FIROZ.pbit** | Power BI Template of the full dashboard |
| **Spotify Dashboard Analysis Kaif Firoz.pdf** | Full project documentation with screenshots |
| **Spotify Dashboard Analysis Kaif Firoz.docx** | Editable version of project documentation |
| **spotify-top-50-world.csv** | Dataset used in the dashboard |
| **Spotify Home Page Screenshot.png** | Screenshot of the Home page |
| **Spotify Overview Page Screenshot.png** | Screenshot of the Overview page |
| **Spotify Artist Page Screenshot.png** | Screenshot of the Artist page |
| **Spotify Songs Page Screenshot.png** | Screenshot of the Songs page |
| **Bussiness Requirements.docx** | Business requirement document |

---

## 📌 1. Business Requirement

Spotify stakeholders needed a centralized dashboard that provides:

- KPIs such as Total Songs, Distinct Artists, Avg Popularity, Avg Duration  
- Distribution: Album Type (single/album/compilation), Explicit vs Non-Explicit  
- Artist trends, Song trends, Yearly & Monthly analytics  
- Drill-down pages for artist-level & song-level deep insights  

The dashboard solves decision-making gaps by converting raw ranking data into **actionable insights**.

---

## 🎯 2. Analytical Goals

- Identify top-performing artists and songs  
- Compare explicit vs non-explicit songs  
- Analyze album-type dominance  
- Study popularity trends across months and years  
- Identify #1 hit-makers & consistent artists  
- Provide song-level metrics (release date, duration, popularity, positions)  

---

## 🧹 3. Data Preparation & Modeling

Dataset: **spotify-top-50-world.csv**  
Contains fields like:

`date`, `position`, `song`, `artist`, `popularity`, `duration_ms`,  
`album_type`, `total_tracks`, `release_date`, `is_explicit`, `album_cover_url`

### Steps Performed:

- Cleaned dataset  
- Converted dates to proper format  
- Created **Year**, **Month**, and time intelligence columns  
- Built a dedicated **_Measure table**  
- Created 30+ DAX calculations  
- Added ranking logic and hit-analysis measures (#1 hits)  
- Designed optimized star-like model  

---

## 📊 4. Dashboard Pages & Visuals

### 🏠 Home Page  
Minimalistic Spotify UI → Navigation to **Overview | Artist | Songs**  
*(See: Spotify Home Page Screenshot.png)*

---

### 📈 Overview Page  
*(See: Spotify Overview Page Screenshot.png)*

#### KPIs:
- Distinct Songs  
- Distinct Artists  
- Avg Popularity  
- Avg Duration  

#### Visuals:
- Songs by Album Type  
- Explicit vs Non-Explicit comparison  
- Songs by Year  
- Avg Popularity Trend (Month / Quarter)  
- Distinct Songs per Month  
- Top Artists & Top Songs  

---

### 🎤 Artist Page  
*(See: Spotify Artist Page Screenshot.png)*

Shows:

- Distinct songs per artist  
- Popularity by artist  
- #1 Hits per artist  
- Artist card visuals  
- Artist table with:
  - Song appearances  
  - Album count  
  - Avg popularity  
  - Popularity rank  
  - Best position / Worst position  

---

### 🎵 Songs Page  
*(See: Spotify Songs Page Screenshot.png)*

Shows:

- Song popularity  
- Song appearances  
- #1 hits  
- Release date  
- Album type  
- Avg popularity, Max popularity  
- Avg duration  

---

## 🧠 5. Key Insights

- Taylor Swift, Billie Eilish & SZA dominate in appearances  
- Singles dominate more than albums in chart presence  
- Explicit songs have similar popularity to non-explicit songs  
- 2024 has stronger popularity trend than 2023  
- Several artists show consistent #1 positions  
- Popularity trends show seasonal monthly fluctuations  

---

## ⚙️ 6. Tools & Techniques Used

- Power BI  
- 30+ DAX Measures  
- Time Intelligence  
- Data Modeling (star-like model)  
- Drill-through & Navigation UX  
- Custom Spotify-themed UI  
- Data Cleaning  
- Performance Optimization  

---

## 🧮 7. Major DAX Measures Created

- Distinct Songs  
- Distinct Artists  
- Avg Popularity  
- Avg Duration  
- Explicit %  
- Songs per Artist  
- Song Appearances  
- #1 Hits per Artist  
- Popularity Rank  
- YoY Popularity  
- Monthly Popularity Trend  

---

## 🎤 8. Interview Storytelling Summary

“I built an end-to-end Spotify Top-50 analytics dashboard in Power BI to provide Spotify teams with actionable insights.  
I created KPIs, monthly & yearly trends, #1 hit analysis, album-type distribution, and explicit content analysis.  
The dashboard includes separate pages for overview, artist insights, and song-level analysis.  
I used a dedicated measure table, 30+ DAX calculations, and a professional Spotify-themed UI.”

---

## 📂 9. Folder Structure

📁 Spotify-Dashboard-Analysis
│── README.md
│── Bussiness Requirements.docx
│── Spotify Dashboard Analysis Kaif Firoz.pdf
│── Spotify Dashboard Analysis Kaif Firoz.docx
│── Spotify Dashboard Analysis KAIF FIROZ.pbit
│── spotify-top-50-world.csv
│── Spotify Home Page Screenshot.png
│── Spotify Overview Page Screenshot.png
│── Spotify Artist Page Screenshot.png
│── Spotify Songs Page Screenshot.png
│── /assets  (optional - for future images, thumbnails)


---

## 👨‍💻 10. Author

**Mohammad Kaif Firoz**  
Data Analyst — SQL | Power BI | Excel | Tableau | Python  

📧 Email: **kaifsidd2003@gmail.com**  
🔗 LinkedIn: **https://www.linkedin.com/in/kaiffiroz/**  

---

⭐ *If you found this project useful, please consider giving the repository a star!* ⭐
