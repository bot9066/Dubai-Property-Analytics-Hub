# 🕌 Dubai Property Analytics Hub – Power BI Dashboard

A complete Power BI project analyzing real estate trends across **Urban**, **Suburban**, and **Rural** areas of Dubai. This repository includes the raw dataset, enriched data columns, an interactive Power BI `.pbix` dashboard, and a detailed project report in PDF format.

---

## 📊 Project Overview

This project delivers actionable insights into Dubai’s real estate market by analyzing:
- Property pricing
- Size and layout configurations
- Age of construction
- Luxury vs non-luxury segmentation
- Neighborhood-based investment potential

The dashboard helps buyers, investors, and developers explore listings across price tiers: **Budget**, **Mid-Range**, and **High-End** — with interactive filters for better decision-making.

---

## 📁 Repository Contents

| File                            | Description                                      |
|---------------------------------|--------------------------------------------------|
| `housing_price_dataset.csv`     | Raw dataset of Dubai housing listings            |
| `DUBAI House Price.pdf`         | Full project report with insights & visuals      |
| `Dubai Property Dashboard.pbix` | Final Power BI dashboard file                    |
| `README.md`                     | This file                                        |

---

## 📌 Key Dashboard Features

-  Neighborhood-wise analysis (Urban, Suburban, Rural)  
-  Dynamic filtering by Bedrooms, Bathrooms, Property Age, and Luxury  
-  Price per Sqft and Property Age insights  
-  Buyer segmentation by BHK and listing category  
-  Investment strategy section for different buyer types

---

## 📈 Data Enrichment Summary

The original dataset was enhanced using Power BI's Power Query and DAX features to add key calculated columns:

- `PricePerSqft` = `Price` ÷ `SquareFeet`  
- `PropertyAge` = 2025 − `YearBuilt`  
- `ListingCategory` = Classified as Budget / Mid-Range / High-End using percentiles  
- `Luxury` = Based on high `PricePerSqft`, square footage, and `ListingCategory`  
- `PropertyAgeBucket` = Grouped age ranges for simplified insights

---

## 📆 Data Time Range

The dataset covers Dubai properties built between **1950 and 2021**, enabling multi-decade insights.

- Earliest property: **1950**
- Latest property: **2021**
- Calculated `PropertyAge` ranges from **4 to 75 years** (as of 2025)

This wide age range provides meaningful insights into how **property age affects price**, **luxury status**, and **investment value**. Property age is also used extensively in slicers and trend visuals throughout the dashboard.

---

## 📄 Dashboard Pages Overview

1. **Main Dashboard**: Key KPIs, price trends, and luxury distribution  
2. **Urban Analysis**: Insights into high-end properties and compact spaces  
3. **Suburban Overview**: Value-for-money homes and mid-range segments  
4. **Rural Breakdown**: Budget-dominated listings and age-heavy properties  
5. **Investment Strategy Page**: Buyer personas and opportunity mapping  
6. **Interaction Guide**: Slicer strategies and how to explore key segments

---

## 💼 Investment Insights

| Area      | Target Buyer Type              | Key Highlights                                        |
|-----------|--------------------------------|-------------------------------------------------------|
| **Urban** | Luxury buyers & expats         | Newer, compact, premium homes with highest price/sqft |
| **Suburb**| Families & mid-range investors | Larger 3–4BHK homes with strong value                 |
| **Rural** | Budget buyers, land investors  | Older homes, low cost, potential for redevelopment    |

---

## 🚀 How to Use the Dashboard

1. Clone or download the repository
2. Open `Dubai Property Dashboard.pbix` in Power BI Desktop
3. Use slicers to filter by:
   - `Neighborhood` (Urban, Suburb, Rural)
   - `Bedrooms` / `Bathrooms`
   - `Luxury` (Yes/No)
   - `PropertyAge` or `PropertyAgeBucket`
4. Navigate between pages to explore area-specific insights
5. Refer to the PDF report for a full breakdown and investment commentary

---

## 🛠 Tools Used

- Power BI Desktop  
- Power Query
