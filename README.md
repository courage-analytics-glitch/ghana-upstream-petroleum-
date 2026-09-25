# Ghana Upstream Petroleum Analysis, 2024 to 2026

Ghana's Petroleum Commission publishes upstream data across web tables, Excel files, a permit register and PDF reports, in inconsistent formats. This project pulls the public sources together with Python, cleans and reconciles them, and analyses output, gas use, liftings, licences, permits and procurement.

## Key findings

1. Oil output fell 22.7% in 2025 and recovered 11.7% in the first half of 2026.
2. TEN declined for a second year and flares the highest share of its gas.
3. Flaring fell from about 27.3 billion cubic feet in 2024 to a 2026 pace near 8.5.
4. About 1% of OCTP gas is unaccounted for in every year.
5. 89% of licensed acreage produces no oil.
6. One in five planned contracts goes to a single or sole source.
7. 25 data quality issues logged, from unit clashes to a register showing no active permit for the main operator.

## Contents

1. petrocom-analysis.ipynb: full pipeline, from extraction to charts
2. clean: cleaned CSV files and the data quality log
3. charts: six charts

## Tools

Python, pandas, requests, BeautifulSoup, pdfplumber, matplotlib, Jupyter

## Data

Kaggle dataset: https://www.kaggle.com/datasets/setorcourage/ghana-upstream-petroleum-data-2024-to-2026

## Sources

Petroleum Commission Ghana (petrocom.gov.gh) and Ghana Petroleum Register (ghanapetroleumregister.com). Public data. Independent analysis, not endorsed by the Commission.

## Author

Richard Courage Cobbinah, Courage Analytics Glitch
