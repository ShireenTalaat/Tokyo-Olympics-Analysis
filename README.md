# Tokyo Olympics Analysis Dashboard

## 📊 Overview

This repository contains a **Tokyo Olympics Analysis Dashboard** built with **Microsoft Power BI**. The dashboard provides a comprehensive breakdown of medal counts, country performance, and medal distribution across the participating nations in the Tokyo Olympics.

The project visualizes data for **93 countries**, tracking Gold, Silver, and Bronze medals to identify top-performing nations and overall trends.

**Author:** Shireen Talaat

---

## 🖼️ Dashboard Preview

![tokoyo.jpg](https://github.com/ShireenTalaat/Tokyo-Olympics-Analysis/blob/main/tokoyo.jpg)

---

## 📈 Key Performance Indicators (KPIs)

The dashboard tracks the following aggregate metrics at the top level:

| Metric | Value |
| :--- | :--- |
| **Total Countries** | 93 |
| **Total Gold Medals** | 340  |
| **Total Silver Medals** | 338 🥈 |
| **Total Bronze Medals** | 402 🥉 |
| **Total Medals** | 1,080 |

---

##  Dashboard Components

### 1. Top 10 Countries By Total Medals
A horizontal bar chart ranking the nations with the highest overall medal counts.
*   **Leader:** **United States** takes the top spot with over 100 medals.
*   **Runners Up:** People's Republic (China), ROC (Russian Olympic Committee), Great Britain, and Japan follow closely.
*   **Others:** Australia, Italy, Germany, Netherlands, and France round out the top 10.

### 2. Medal Category By Country (Performance Tiers)
A donut chart classifying countries into performance tiers (likely based on medal count thresholds).
*   **Developing / Lower Tier (Green):** The largest segment, representing **68 countries (73.12%)**.
*   **High Performers / Medium Tier:** Smaller segments representing the top-tier nations.
*   **Top Tier (Yellow):** The smallest segment (5 countries, 5.38%), representing the elite medal winners.

### 3. Bronze to Total Ratio
A gauge chart visualizing the proportion of Bronze medals won.
*   **Value:** **402** Bronze medals out of a total **1,080** medals.
*   **Insight:** Bronze medals are the most frequently awarded medal type in this dataset (402 vs 340 Gold and 338 Silver).

### 4. Medal Distribution by Type (Top 15)
A stacked bar chart showing the breakdown of Gold (Yellow), Silver (Grey), and Bronze (Orange) for the top 15 countries.
*   **United States:** Shows a balanced distribution with a high volume of all three types.
*   **People's Republic:** Strong showing in Gold and Silver.
*   **Trend:** Most top countries have a relatively even split, though some lean heavier towards Bronze or Silver.

---

##  Key Insights

1.  **US Dominance:** The United States is the clear leader in total medal count.
2.  **Bronze Frequency:** There are more Bronze medals (402) than Gold (340) or Silver (338), which makes sense as many events award two bronze medals (e.g., in combat sports) or there are more events overall.
3.  **Performance Gap:** The "Top Tier" (yellow slice in donut chart) represents only ~5% of the countries, highlighting a significant gap between the elite medal-winning nations and the rest of the field.

---

## 🛠️ Tools & Technologies

*   **Microsoft Power BI:** Dashboard development and visualization.
*   **DAX:** Used for calculating totals and ratios.
*   **Data Modeling:** Structuring country and medal data for analysis.

---

## 👤 Author

**Shireen Talaat**
*Data Analyst | Power BI Developer*
