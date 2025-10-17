# paris-socioeconomic-analysis
# 🏙️ Socio-Economic Disparities in Île-de-France (Paris)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Data](https://img.shields.io/badge/Data-INSEE-orange)
![Visualization](https://img.shields.io/badge/Geo-Maps-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 🎯 Project Overview
This project analyzes open municipal data from **INSEE (data.gouv.fr)** to measure and visualize **social and economic inequalities** in the Île-de-France region (Paris metropolitan area).

The objective was to verify the commonly held assumption of a **“Rich West – Poor East”** divide within the Paris region.

---

## 📊 Methodology
- Collected socio-economic indicators from **INSEE** and **Eurostat (GDP per capita)** (2000–2025)
- Focus variables:
  - Population
  - Median disposable income
  - Unemployment rate
  - High school graduation rate
- Normalized each variable using **Z-score normalization**
- Constructed a composite **Social Score**:
Total_Score = Z(Income) + Z(Education) – Z(Unemployment)

---

## 🗺️ Results
- Western Paris shows **higher income, lower unemployment, and higher education** → highest social scores.
- Eastern Paris shows **lower income, higher unemployment, and lower education** → lowest scores.
- The **“Rich West / Poor East”** hypothesis is **empirically confirmed**.
- **GDP alone** does not reflect real living standards — education and employment matter equally.

---

## 💡 Insights
1. Socio-economic polarization in Paris is both **spatially and statistically measurable**.  
2. **Education and employment** are tightly correlated with income distribution.  
3. Policy recommendations:  
 - Improve access to education in the East.  
 - Encourage regional employment programs to balance growth.  
 - Promote data-driven urban planning using open data.

---

## 📂 Repository Structure
  📁 paris-socioeconomic-analysis/
  ├── data/ # INSEE datasets
  ├── notebooks/ # Jupyter Notebooks
  ├── maps/ # GeoJSON + Choropleth maps
  ├── results/ # Plots, ranking tables
  ├── presentation.pdf # Project report (Big Data shorter version)
  └── README.md # Documentation

---

## 🧰 Tech Stack
- **Python:** pandas, geopandas, matplotlib, seaborn, folium  
- **Data Source:** INSEE, Eurostat  
- **Tools:** Jupyter Notebook, QGIS  

---


## 🚀 How to Use
```bash
# Clone this repository
git clone https://github.com/toanvoduc27/paris-socioeconomic-analysis.git
cd paris-socioeconomic-analysis

# Install dependencies (if needed)
pip install pandas geopandas matplotlib seaborn folium

# Open the notebook
jupyter notebook notebooks/paris_analysis.ipynb
```
---

##👨‍💻 Authors
- Ngọc Liên
- Đức Toàn (@toanvoduc27)
- 👨‍🏫 Supervisor: Sylvain Barthélémy
- 📊 Université Paris 1 Panthéon-Sorbonne
- 📝 License
    This project is licensed under the MIT License.
- 📈 “Paris is not only the ‘City of Light,’ but also a mirror reflecting the growing economic inequality.”
```
