# 🚦 Drive Safe India: Road Accident Insights using Power BI

An interactive Power BI dashboard analysing road accidents in India from 2020 to 2024, using official data from the Ministry of Road Transport and Highways (MoRTH).

The dashboard explores **where** accidents happen, **who** is most at risk, and **why** they occur, to highlight key areas for improving road safety.

---

## 📊 Dashboard Pages

### 1. State-wise Accident Analysis
- Total accidents (2020–2024) and year-over-year (YoY) change
- Top 5 states with the most and the least accidents
- Top 5 states with the highest % increase and % reduction (2023–24)
- Yearly accident trend

### 2. City Analysis
- Total road deaths in million-plus cities (2024)
- Top 5 cities with the most road deaths
- Road deaths by road user type, with a road user slicer

### 3. Road User Analysis
- Total deaths and two-wheeler deaths, filterable by year
- Deaths by road user (two-wheelers, pedestrians, cars, trucks, etc.)
- % change in deaths from 2023 to 2024 by road user

### 4. Violations Analysis
- Accidents, injuries, and deaths by traffic violation
- Slicers to switch between years and between Accidents / Injured / Killed

---

## 💡 Key Insights

## 💡 Key Insights

- 🚗 Road accidents rose from **3.72 lakh in 2020** to **4.88 lakh in 2024**, with a **1.48% increase** from 2023 to 2024.
- 🗺️ **Tamil Nadu** recorded the most accidents from 2020–2024, with about **3.04 lakh accidents**.
- 📈 **Meghalaya** had the biggest rise in accidents from 2023 to 2024 (**+21%**).
- 💀 **1,77,180 people** were killed in road accidents in India in 2024.
- 🏍️ **Two-wheeler riders** were the most affected road users, with **81,780 deaths** in 2024, followed by **pedestrians** with **36,530 deaths**.
- ⚡ **Over-speeding** caused **1,24,520 deaths** in 2024, the highest of all traffic violations.
- 🏙️ Million-plus cities recorded **17,200 road deaths** in 2024, and **Delhi** had the most, with **1,551 deaths**.
---

## 🛠️ Tools & Techniques

- **Power BI Desktop**: dashboard design and visualisation
- **Power Query**: data cleaning and transformation
  - Removed null rows, footnotes and serial number columns
  - Replaced "NA" values with null
  - Fixed data types and number formats
  - Unpivoted year-wise columns into a long format for year filtering
- **DAX**: calculated measures, for example:
  - Year-over-Year (YoY) % change
  - State with the most accidents
  - Total deaths, two-wheeler deaths, and violation-wise totals
- **Visuals**: bar charts, line chart, KPI cards, tile slicers, page navigation

---

## 📁 Repository Contents

| File | Description |
|---|---|
| `Drive_Safe_India.pbix` | Power BI dashboard file |
| `Drive_Safe_India.pdf` | PDF export of all dashboard pages |


---

## ▶️ How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only).
2. Download `Drive_Safe_India.pbix` from this repository.
3. Open it in Power BI Desktop.

No Power BI? Open [powerbi_project.pdf](https://github.com/user-attachments/files/32871080/powerbi_project.pdf)
 to view the dashboard pages.



## 📚 Data Source

Ministry of Road Transport and Highways (MoRTH), Government of India, *Road Accidents in India 2024*.
Accessed via OpenCity: https://data.opencity.in/dataset/road-accidents-in-india-2024

---

## 👤 Author

**[Gagan K. Moolya]**
[linkedin/in/gaganmoolya] | [gaganmolya03@gmail.com]
