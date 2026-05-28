# 🏠 King County Real Estate Market Intelligence Dashboard

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

An interactive Tableau dashboard analyzing house sales data in King County, Washington. Built as a portfolio project to demonstrate advanced data visualization and dashboard design skills.

---


## 📸 Dashboard Preview

![Dashboard Preview](dashboard-preview.png) *(add your screenshot here)*

---

## 📌 Project Overview

This project connects Tableau to a real-world Excel dataset of King County house sales. The goal was to transform raw data into meaningful, interactive visualizations that help users explore price trends, geographic patterns, and property distributions.

---

## ✨ Features

- 📅 **Interactive Calendar Filter** — Select month and day to filter all charts dynamically
- 📈 **Daily Average House Sales Price** — Line chart showing price trends over time
- 🗺️ **Map Visualization** — Geographic sales patterns using zip codes
- 📊 **Distribution of House Prices** — Histogram for price range analysis
- 🛏️ **Distribution of Bedrooms** — Histogram analyzing bedroom counts
- 🛁 **Distribution of Bathrooms** — Histogram analyzing bathroom counts
- 🔥 **View vs Condition Heatmap** — Comparing view quality against property condition
- 🎚️ **Slider Filters** — Filter by Year Built, Sqft Living, and Sqft Lot

---

## 🗂️ Dataset

| Property | Details |
|----------|---------|
| Source | [((https://mavenanalytics.io/))] |
| Format | Excel (.xlsx) |
| Rows | 21,060 |
| Columns | 16 fields |

### Key Fields
`id` · `date` · `price` · `bedrooms` · `bathrooms` · `sqft_living` · `sqft_lot` · `floors` · `waterfront` · `view` · `condition` · `grade` · `yr_built` · `zipcode` · `lat` · `long`

---

## 🛠️ Data Preparation

- Connected Tableau to the Excel dataset
- Converted the `date` field from **string (ABC)** format to **Date** format
- Created **bins** for Price, Bedrooms, and Bathrooms for histogram analysis
- Built calculated fields and applied filters for interactivity

---

## 📐 Dashboard Design

| Element | Choice |
|---------|--------|
| **Color Palette** | Midnight Navy & Champagne Gold |
| **Background** | Dark Navy `#0D1B2A` |
| **Charts Color** | Gold/Amber |
| **Tool** | Tableau Public (Desktop) |
| **Layout** | Tiled — Filters left, Charts right |

---

## 🚀 How to Run Locally

1. Download and install [Tableau Public](https://public.tableau.com/en-us/s/download) (free)
2. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/king-county-real-estate-dashboard
   ```
3. Open the `.twbx` file in Tableau Public
4. The dashboard will load with all charts and filters ready

---

## 📁 Repository Structure

```
king-county-real-estate-dashboard/
│
├── KingCountyHouseSales.twbx       # Tableau workbook file
├── HouseData.xlsx                  # Excel dataset
├── dashboard-preview.png           # Dashboard screenshot
└── README.md                       # Project documentation
```

---

## 💡 Key Insights

- The majority of house sales fall in the **$300K–$600K** price range
- Properties with **Excellent view** and **Very Good condition** command the highest average prices
- Sales activity peaks in **mid-2014** based on daily average trends
- Most homes have **3–4 bedrooms** and **1.5–2 bathrooms**

---

## 🙋 Author

**Rumaisa Fatima**

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with ❤️ using Tableau Public*
