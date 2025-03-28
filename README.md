# NYC Property Sales Analysis (2017–2023)

**Author:** Abdulla Saleh  
**Tech Stack Used:** Python, Pandas, Folium, Seaborn, Matplotlib, Plotly

---

## Project Overview

This project explores property sale trends across all five boroughs of New York City using publicly available citywide sales data from 2017 to 2023.

The analysis includes:
-  An interactive **map** with dynamic choropleths and tooltips by borough/year
- Cleanly formatted **line and bar charts** showing price trends and sales volume
- Summary tables displaying median and average sale prices by year and borough

---

## Folder Structure

```
nyc-property-sales-analysis/
├── NYC_Property_Sales_Analysis.ipynb       # Jupyter notebook with full analysis
├── README.md                               # Project overview and instructions
├── data/                                   # Raw data files
│   ├── 2017_citywide_sale.xlsx
│   ├── 2018_citywide_sale.xlsx
│   ├── 2019_citywide_sale.xlsx
│   ├── 2020_citywide_sale.xlsx
│   ├── 2021_citywide_sale.xlsx
│   ├── 2022_citywide_sale.xlsx
│   ├── 2023_citywide_sale.xlsx
│   └── nyc_boroughs.geojson
```




---

## How to Run

1. Clone the repository or upload the files to Google Colab or Jupyter.
2. Remove all the `.xlsx` data files and the `.geojson` file from the `data/` folder and upload them to google colab.
3. Open the notebook and run all cells from top to bottom.


---

## Data Sources

- NYC Property Sales:  
 https://www.nyc.gov/site/finance/property/property-annualized-sales-update.page?

- NYC Borough Boundaries (GeoJSON):  
https://www.nyc.gov/site/planning/data-maps/open-data/districts-download-metadata.page

---

## Insights and Observations

- Manhattan consistently had the highest median and average sale prices.
- Sale volumes dipped during the COVID-19 pandemic years (2020–2021) but began recovering in 2022.
- Brooklyn and Queens showed more steady growth across the years.
- The borough-level mapping allows visual comparison of pricing dynamics across the city.

---

## License

This project is for educational and portfolio use only. Data is publicly available via NYC Open Data.



