# 🎧 Spotify Music Analytics Dashboard

## 📌 Project Overview

This project presents an interactive **Spotify Music Analytics Dashboard** developed using **Microsoft Excel**.

The objective of the project is to analyze Spotify track data and transform a large dataset into a clear and interactive dashboard. The analysis focuses on track popularity, artists, genres, danceability, energy, explicit content, and popularity distribution.

The project covers the complete Excel data analytics workflow, including **data importing, data cleaning and transformation, analysis using PivotTables, data visualization, KPI creation, and interactive dashboard development**.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze the overall characteristics of Spotify tracks.
- Identify top genres based on average popularity.
- Identify top artists based on average popularity.
- Compare the average popularity of explicit and non-explicit tracks.
- Analyze the distribution of tracks across different popularity categories.
- Summarize important metrics using KPI cards.
- Allow interactive filtering of the dashboard by music genre.

---

## 🛠️ Tools & Techniques Used

- **Microsoft Excel**
- **Power Query** – Data importing, cleaning, and transformation
- **PivotTables** – Data analysis and aggregation
- **PivotCharts** – Data visualization
- **Excel Formulas / Calculated Fields**
- **Slicers** – Interactive dashboard filtering
- **KPI Cards** – Displaying important summary metrics
- **Dashboard Design & Formatting**

---

## 📊 Dashboard KPIs

The dashboard contains four key performance indicators:

| KPI | Result |
|---|---:|
| Total Tracks | 89,740 |
| Average Popularity | 33.20 |
| Average Danceability | 0.56 |
| Average Energy | 0.63 |

**Popularity** is represented using a score from 0 to 100, while **Danceability** and **Energy** are represented on a scale from 0 to 1.

---

## 📈 Dashboard Visualizations

### 1. Top 10 Genres by Average Popularity
Displays the genres with the highest average popularity scores and makes it easy to compare popularity across genres.

### 2. Top 10 Artists by Average Popularity
Identifies artists with the highest average track popularity within the analyzed dataset.

### 3. Explicit vs Non-Explicit Track Popularity
Compares the average popularity score of explicit and non-explicit tracks.

In the dataset:
- `TRUE` represents an explicit track.
- `FALSE` represents a non-explicit track.

### 4. Popularity Category Breakdown
Groups tracks into **Low, Average, and Popular** categories based on their popularity scores.

The dashboard shows approximately:

- **Low:** 60%
- **Average:** 37%
- **Popular:** 3%

---

## 🎛️ Interactive Filtering

The dashboard includes a **Track Genre Slicer**.

Users can select a particular music genre, and the connected PivotCharts automatically update to display information relevant to the selected genre.

This makes the dashboard interactive and allows users to explore the dataset dynamically.

---

## 🔍 Key Insights

- The dataset contains **89,740 analyzed tracks**.
- The overall average popularity score is approximately **33.20**.
- Average danceability is approximately **0.56**.
- Average energy is approximately **0.63**.
- Explicit tracks have a higher average popularity score than non-explicit tracks in this dataset.
- Around **60% of tracks fall into the Low popularity category**, while only around **3% fall into the Popular category**.
- Popularity varies across different artists and music genres.

---

## 🧹 Data Preparation

Before performing the analysis, the dataset was prepared and cleaned using **Power Query in Excel**.

The data preparation process included reviewing the dataset, handling unnecessary or inconsistent data, preparing relevant columns for analysis, and creating additional fields such as **Duration Minutes** and **Popularity Category**.

The cleaned data was then used to create PivotTables, PivotCharts, KPIs, and the final dashboard.

---

## 📁 Project Structure

The Excel workbook contains three main worksheets:

- **Data** – Contains the cleaned Spotify track dataset.
- **Analysis** – Contains PivotTables and supporting analysis.
- **Dashboard** – Contains the final interactive Spotify analytics dashboard.

---

## 💡 Skills Demonstrated

This project demonstrates practical skills in:

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- Excel PivotTables
- PivotCharts
- KPI Development
- Interactive Filtering
- Data Visualization
- Dashboard Design
- Data Storytelling

---

## 📌 Conclusion

The Spotify Music Analytics Dashboard demonstrates how a large music dataset can be transformed into meaningful and easy-to-understand insights using Microsoft Excel.

The final dashboard provides a concise view of track popularity, artist and genre performance, audio characteristics, explicit content, and popularity distribution while allowing users to interact with the data through genre-based filtering.
