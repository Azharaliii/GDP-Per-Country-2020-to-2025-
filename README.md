 # 🌍 GDP Per Country (2020–2025) — Tracking Global Economic Growth

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-20BEFF?logo=kaggle&logoColor=white)
![License](https://img.shields.io/badge/License-Apache%202.0-blue)

An end-to-end Exploratory Data Analysis (EDA) on the GDP Per Country dataset (2020–2025) — covering global economic trends, country comparisons, time-series growth tracking, Pakistan's specific GDP journey, and outlier detection among the world's top economies. Built using only **Pandas**, **NumPy**, and **Matplotlib**.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Dataset](#-dataset)
- [Notebook Sections](#-notebook-sections)
- [Analysis Highlights](#-analysis-highlights)
- [🇵🇰 Pakistan Focus](#-pakistans-gdp-2020-to-2025)
- [Visualizations](#-visualizations)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [How to Run](#-how-to-run)
- [Key Insights](#-key-insights)
- [Author](#-author)

---

## 🌐 Overview

This project tracks and analyzes the **Gross Domestic Product (GDP)** of countries around the world from **2020 to 2025** — a particularly significant period covering the COVID-19 pandemic recovery, global inflation, and post-pandemic economic growth.

The analysis goes from basic data exploration all the way to time-series trend analysis, bivariate relationships, and a dedicated deep-dive into **Pakistan's economic performance** over this 5-year window.

**Goal:** Clean the data, understand its structure, visualize important patterns, and extract meaningful economic insights using only core Python libraries.

---

## 📂 Dataset

- **Source:** [GDP Per Country Dataset — Kaggle](https://www.kaggle.com/)
- **Coverage:** Global — all major countries, 2020 to 2025
- **Format:** CSV
- **License:** Apache 2.0

### Dataset Columns

| Column | Description |
|--------|-------------|
| `Country` | Name of the country |
| `Year` | Year of the GDP record (2020–2025) |
| `GDP (USD)` | GDP value in US Dollars |
| `GDP Growth (%)` | Annual GDP growth rate percentage |
| `GDP Per Capita` | GDP divided by population |
| `Region` | Geographic region/continent |
| `Population` | Country population for that year |

---

## 📓 Notebook Sections

The notebook is structured into 9 clearly defined sections:

| # | Section | Description |
|---|---------|-------------|
| 1 | 📝 Introduction & Dataset Description | Project goals, dataset overview, and context |
| 2 | 📦 Import Libraries & Load Dataset | Importing pandas, numpy, matplotlib; loading CSV |
| 3 | 📊 GDP EDA Report | Full overview report of the dataset |
| 4 | 🔍 Basic Exploration | Shape, dtypes, nulls, `.info()`, `.describe()` |
| 5 | 📈 Univariate Analysis | One column at a time — distributions, value counts |
| 6 | 🔗 Bivariate Analysis | Relationships between columns — GDP vs growth, etc. |
| 7 | 📅 Time-Series / Trend Analysis | How GDP changed year over year globally |
| 8 | 🇵🇰 Pakistan's GDP (2020–2025) | Dedicated section tracking Pakistan's economy |
| 9 | 🔎 Correlation & Outlier Detection | Top 20 countries — correlations and anomalies |
| 10 | ✅ Conclusion & Insights | Summary of all findings and key takeaways |

---

## 🔍 Analysis Highlights

### 🧹 Data Cleaning
- Checked for missing values and null entries across all columns
- Fixed incorrect data types (year as integer, GDP as float)
- Removed duplicates and standardized country/region names

### 📊 Basic Exploration
- Dataset shape, column descriptions, and statistical summaries
- Distribution of GDP values across all countries and years
- Identifying the highest and lowest GDP countries

### 📈 Univariate Analysis
- GDP distribution — highly skewed, dominated by USA and China
- GDP growth rate distribution — most countries between -5% and +10%
- Per capita GDP spread across countries and regions

### 🔗 Bivariate Analysis
- GDP vs GDP Growth Rate — do bigger economies grow faster?
- GDP vs Population — does population size predict total GDP?
- Regional comparisons — how do continents differ in economic performance?

### 📅 Time-Series / Trend Analysis
- Global GDP trend from 2020 (pandemic dip) through 2025 (recovery)
- Top 10 economies tracked year-by-year
- Countries with fastest growth over the 5-year period
- Countries that shrunk or stagnated post-COVID

### 🔎 Correlation & Outlier Detection
- Correlation matrix among top 20 countries' GDP values
- Outlier detection — USA and China as extreme outliers
- Heatmap of GDP correlations between major economies

---

## 🇵🇰 Pakistan's GDP (2020 to 2025)

A dedicated analysis section tracks **Pakistan's economic journey** specifically:

- GDP value each year from 2020 to 2025
- Growth rate changes — impact of COVID-19, political instability, IMF program
- Pakistan vs regional neighbors (India, Bangladesh, Sri Lanka)
- Per capita GDP trend for Pakistan
- Where Pakistan ranks globally in each year

This makes the project uniquely relevant to a Pakistani audience and demonstrates real-world local context in data analysis.

---

## 📉 Visualizations Used

| Chart Type | Used For |
|---|---|
| Line Charts | GDP trends over time — global and per country |
| Bar Charts | Top/bottom GDP countries, regional comparisons |
| Horizontal Bar Charts | Country rankings by GDP and growth rate |
| Scatter Plots | GDP vs Growth Rate, GDP vs Population |
| Heatmaps | Correlation matrix of top 20 economies |
| Box Plots | Outlier detection in GDP distribution |
| Area Charts | Cumulative global GDP growth 2020–2025 |

---

## 🛠️ Tech Stack

```
Python 3.x
├── pandas        # Data loading, cleaning, groupby, time-series operations
├── numpy         # Numerical calculations, outlier detection
└── matplotlib    # All charts — line, bar, scatter, heatmap, box plots
```

> No external ML libraries used — pure data analysis with core Python stack.

---

## 📁 Project Structure

```
GDP-Per-Country-2020-to-2025-/
│
├── gdp-per-country-2020-to-2025.ipynb   # Full EDA notebook
│                                         # 10 sections · complete analysis
│
├── LICENSE                               # Apache 2.0 License
└── README.md                             # Project documentation
```

> **Note:** Dataset CSV is not included. Download from [Kaggle](https://www.kaggle.com/) and place in root directory before running.

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/Azharaliii/GDP-Per-Country-2020-to-2025-.git
cd GDP-Per-Country-2020-to-2025-
```

### 2. Install Dependencies
```bash
pip install pandas numpy matplotlib jupyter
```

### 3. Download the Dataset
- Search for **"GDP Per Country 2020–2025"** on [Kaggle](https://www.kaggle.com/)
- Download the CSV and place it in the project root

### 4. Launch the Notebook
```bash
jupyter notebook gdp-per-country-2020-to-2025.ipynb
```

---

## 💡 Key Insights

- 🌍 **COVID-19 Impact** — 2020 saw the sharpest global GDP decline since World War II, with most countries recording negative growth
- 🔄 **Recovery Trend** — Global GDP rebounded strongly in 2021–2022, with developing economies recovering at different speeds than developed ones
- 🇺🇸🇨🇳 **USA & China Dominance** — These two economies are extreme outliers, making them important to isolate in outlier analysis
- 🇵🇰 **Pakistan's Challenges** — Pakistan's GDP growth faced significant headwinds including inflation, currency devaluation, and IMF program constraints across this period
- 📊 **GDP ≠ Growth** — Larger economies don't always grow faster; some smaller developing economies showed higher % growth rates
- 🌏 **Regional Patterns** — Asia-Pacific showed the fastest overall recovery; parts of Africa and Latin America lagged behind

---

## 🔮 Future Improvements

- 🗺️ Interactive world map using `folium` or `plotly` choropleth
- 📊 Streamlit dashboard for real-time country comparisons
- 🤖 GDP forecasting model using Linear Regression or ARIMA
- 🔗 Merging with inflation, unemployment, and trade data for richer analysis
- 📱 Mobile-friendly interactive notebook with `ipywidgets`

---

## 👤 Author

**Azhar Ali Soomro**
BS Computer Science — AI Specialization, Sukkur IBA University

[![GitHub](https://img.shields.io/badge/GitHub-Azharaliii-181717?logo=github&logoColor=white)](https://github.com/Azharaliii)
[![Kaggle](https://img.shields.io/badge/Kaggle-azharalisoomro-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/azharalisoomro)

---

## 📄 License

This project is licensed under the [Apache 2.0 License](LICENSE).

---

⭐ **If this analysis helped you understand global economics better, give it a star!**
