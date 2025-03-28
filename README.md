# NYC Property Sales Analysis (2017–2023)

**Author:** Abdulla Saleh  
**Tech Stack Used:** Python, Pandas, Folium, Seaborn, Matplotlib, Plotly

---

## Project Overview

This project explores property sale trends across all five boroughs of New York City using publicly available citywide sales data from 2017 to 2023.

The analysis includes:
- 📍 An interactive **map** with dynamic choropleths and tooltips by borough/year
- 📊 Cleanly formatted **line and bar charts** showing price trends and sales volume
- 📋 Summary tables displaying median and average sale prices by year and borough

---

## 📂 Folder Structure
nyc-property-sales-analysis/
├── NYC_Property_Sales_Analysis.ipynb       # Jupyter notebook with full analysis
├── NYC_Median_Prices_By_Year.html          # Exported interactive map from Folium (optional)
├── README.md                               # Project overview and instructions
├── data/                                   # Raw input data files
│   ├── 2017_citywide_sale.xlsx
│   ├── 2018_citywide_sale.xlsx
│   ├── 2019_citywide_sale.xlsx
│   ├── 2020_citywide_sale.xlsx
│   ├── 2021_citywide_sale.xlsx
│   ├── 2022_citywide_sale.xlsx
│   ├── 2023_citywide_sale.xlsx
│   └── nyc_boroughs.geojson



---

## How to Run

1. Clone the repository or upload the files to Google Colab or Jupyter.
2. Place all `.xlsx` data files and the `.geojson` file in the `data/` folder.
3. Open the notebook and run all cells from top to bottom.
4. The final interactive map will be saved as `NYC_Median_Prices_By_Year.html`.

---

## Data Sources

- NYC Property Sales:  
  https://data.cityofnewyork.us/Housing-Development/NYC-Rolling-Sales-Data/5ebm-myj7

- NYC Borough Boundaries (GeoJSON):  
  https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm

---

## Insights and Observations

- Manhattan consistently had the highest median and average sale prices.
- Sale volumes dipped during the COVID-19 pandemic years (2020–2021) but began recovering in 2022.
- Brooklyn and Queens showed more steady growth across the years.
- The borough-level mapping allows visual comparison of pricing dynamics across the city.

---

## License

This project is for educational and portfolio use only. Data is publicly available via NYC Open Data.



