# Texas Education Analytics
### Power BI Dashboard · TEA STAAR Data 2023–2025

An interactive Power BI dashboard analyzing student academic performance across **1,200+ Texas school districts** using publicly available data from the Texas Education Agency (TEA).

---

## 📊 Dashboard Overview

### Page 1 — Overview
High-level performance metrics for the state of Texas:
- **Total STAAR Tests**, Overall Passing Rate, Meets Grade Level, Masters Grade Level, Did Not Meet
- Year-over-Year comparison with trend indicators
- Performance Level Distribution (donut chart)
- Passing Rate by Subject (Reading, Math, Science, Social Studies)
- Top 10 Performing Districts

### Page 2 — School Progress
Deep dive into district-level growth and accelerated learning:
- **4 KPI cards**: Annual Growth and Accelerated Learning scores for Math and Reading (with YoY)
- **Custom Python heatmap**: Points by Grade (Grades 4–8) for Annual Growth and Accelerated Learning
- Bar charts comparing performance by grade level
- District improvement tracker: % of districts that improved vs declined year-over-year

---

## 🛠️ Technical Stack

| Tool | Usage |
|------|-------|
| Power BI Desktop | Dashboard development |
| Power Query (M) | Data transformation and modeling |
| DAX | KPI measures, YoY calculations, conditional formatting |
| Python (matplotlib) | Custom heatmap visual |

---

## 📁 Data Sources

All data is publicly available from the **Texas Education Agency (TEA)**:
- [STAAR School Progress Report](https://tea.texas.gov)
- School Years: **2023–24** and **2024–25**
- Scope: District-level, All Students

> ⚠️ Masked values (-1, -3) in the original TEA files are treated as null.

---

## 📥 How to Use

1. Download `Texas_Education_Analytics.pbix`
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. If prompted about data sources, update the file paths to your local data folder
4. Python visual requires Python 3.x with `matplotlib`, `pandas`, `numpy`

---

## 👩‍💻 Author

**Fernanda Borsari**  
Data Analyst · [LinkedIn](https://www.linkedin.com/in/fernanda-borsari-miguel) · [Portfolio](https://fernandaanalytics.com/)
