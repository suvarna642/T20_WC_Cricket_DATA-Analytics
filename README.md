# 🏏 T20 Cricket Data Analytics

An end-to-end cricket data analytics project using **Web Scraping, JavaScript, Python, Pandas, and Power BI** to collect, clean, transform, analyze, and visualize T20 World Cup data.

## 📌 Project Overview

This project analyzes T20 World Cup cricket data to understand **match results, player performance, batting statistics, and bowling performance**.

The project follows a complete data analytics workflow:

**Web Scraping → Raw JSON Data → Data Cleaning & Transformation → CSV Data → Power BI → Insights**

The objective is to convert publicly available cricket data into structured datasets and an interactive Power BI dashboard that can be used to compare players and teams and identify key performance patterns.

---

## 🎯 Objectives

* Collect T20 World Cup cricket data through web scraping.
* Extract match, player, batting, and bowling information.
* Convert scraped data into structured JSON and CSV datasets.
* Clean and transform the data using Python and Pandas.
* Create meaningful analytical measures using Power BI and DAX.
* Build an interactive dashboard for exploring cricket performance.
* Identify useful insights from batting, bowling, and match-level data.

---

## 🛠️ Tools & Technologies

| Tool / Technology    | Purpose                                   |
| -------------------- | ----------------------------------------- |
| **JavaScript**       | Web scraping and data extraction          |
| **Python**           | Data processing and analysis              |
| **Pandas**           | Data cleaning and transformation          |
| **Jupyter Notebook** | Python-based analysis workflow            |
| **Power BI**         | Interactive dashboard and visualization   |
| **DAX**              | Measures and calculated metrics           |
| **CSV / JSON**       | Data storage and intermediate datasets    |
| **GitHub**           | Project version control and documentation |

---

## 🔄 Project Workflow

### 1. Web Scraping

Cricket data was collected from publicly available web pages using JavaScript-based web scraping.

The scraped information includes:

* Match results
* Player information
* Batting performance
* Bowling performance

The extracted data was initially stored in **JSON format**.

### 2. Data Preparation

The scraped JSON data was converted into structured datasets and prepared for analysis.

The datasets were cleaned and transformed to make them suitable for analytical use.

### 3. Python & Pandas

Python and Pandas were used for:

* Reading and inspecting datasets
* Data cleaning
* Handling missing values
* Data transformation
* Structuring analytical tables
* Preparing data for Power BI

### 4. Power BI

The prepared datasets were imported into Power BI to build an interactive cricket analytics dashboard.

The dashboard focuses on:

* Team performance
* Player performance
* Batting statistics
* Bowling statistics
* Match results
* Key performance indicators

---

## 📊 Dataset Structure

The project contains structured datasets such as:

### Match Summary

Contains match-level information including teams, match results, and related match details.

### Player Information

Contains information about players participating in the tournament.

### Batting Summary

Contains batting-level statistics used to analyze player performance.

### Bowling Summary

Contains bowling-level statistics used to analyze bowling performance.

---

## 📁 Repository Structure

```text
T20_WC_Cricket_DATA-Analytics/
│
├── T20_csv_files/
│   ├── dim_match_summary.csv
│   ├── dim_players.csv
│   ├── fact_bating_summary.csv
│   └── fact_bowling_summary.csv
│
├── T20_json_files/
│   ├── t20_wc_batting_summary.json
│   ├── t20_wc_bowling_summary.json
│   ├── t20_wc_match_results.json
│   └── t20_wc_player_info.json
│
├── T20_web_scraping/
│   ├── t20_wc_batting_summary.js
│   ├── t20_wc_bowling_summary.js
│   ├── t20_wc_match_results.js
│   └── t20_wc_player_info.js
│
├── T20_python/
│   └── [Jupyter Notebook]
│
├── T20_powerbi/
│   └── [Power BI Dashboard]
│
├── T20_screenshots/
│   └── [Dashboard Screenshots]
│
└── README.md
```

---

## 📈 Key Analysis Areas

The dashboard is designed to answer questions such as:

* Which players have the strongest batting performances?
* Which players have the strongest bowling performances?
* How do teams compare in terms of overall performance?
* What are the major batting and bowling statistics?
* How do individual players perform across matches?
* Which players stand out based on selected performance metrics?

---

## 💡 Key Skills Demonstrated

This project demonstrates practical experience in:

* **Web Scraping**
* **Python**
* **Pandas**
* **Data Cleaning**
* **Data Transformation**
* **Exploratory Data Analysis**
* **Power BI**
* **DAX**
* **Data Modeling**
* **Data Visualization**
* **Dashboard Development**

---

## 🚀 How to Explore the Project

### Step 1 — Explore the Scraped Data

Start with the files in:

```text
T20_json_files/
```

These contain the data collected during the web-scraping stage.

### Step 2 — Explore the Processed Data

The structured datasets are available in:

```text
T20_csv_files/
```

### Step 3 — Review the Python Analysis

The Python/Jupyter Notebook is available in:

```text
T20_python/
```

### Step 4 — Explore the Power BI Dashboard

The Power BI project is available in:

```text
T20_powerbi/
```

Dashboard screenshots are available in:

```text
T20_screenshots/
```

---

## 📷 Dashboard Preview

Dashboard screenshots will be added here after the Power BI dashboard files are uploaded.

---

## 🔎 Project Highlights

* Built an end-to-end cricket analytics pipeline from **data collection to visualization**.
* Used **web scraping** to collect raw cricket data.
* Used **Python and Pandas** for data preparation and transformation.
* Used **Power BI and DAX** to create an interactive analytical dashboard.
* Organized raw and processed data into structured datasets for reporting.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in building a complete data analytics workflow—from collecting raw web data and transforming it into analysis-ready datasets to developing an interactive Power BI dashboard.

The project also strengthened my understanding of **data cleaning, data modeling, analytical measures, and visualization**.

---

## 👤 Author

**Suvarna**

Civil Engineering | Data Analytics Enthusiast

**Skills:** Python • Pandas • SQL • Power BI • Excel • Data Visualization

---

⭐ If you find this project useful, feel free to explore the repository and the dashboard files.

