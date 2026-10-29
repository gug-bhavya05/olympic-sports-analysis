# Global Olympic Sports Performance Analysis

An interactive Tableau analysis of Olympic medals, athletes and sports investment (1992 to 2026), embedded in a Flask web app.

## Important note on the data
The dataset in `data/` is a **synthetic sample** created for this project. It has the structure of Olympic data but is not real Olympic results, so figures should not be read as historical facts.

## Contents
- `app.py`: Flask application with routes for Home, Dashboard 1, Dashboard 2 and the Story
- `templates/`: HTML pages (Arsha template from BootstrapMade, adapted)
- `static/`: CSS, JS and images for the template
- `data/`: `athletes.csv`, `medal_results.csv`, `country_investment.csv`

## Tableau work
- 2 dashboards, 1 story (6 scenes), KPI tiles, a world map, and a KPI Selector parameter
- Published on Tableau Public: https://public.tableau.com/app/profile/bhavya.1664/viz/olympic_analysis_17929912330030/OlympicPerformanceStory?publish=yes

## How to run locally
1. Install Python 3
2. `pip install flask`
3. `python app.py`
4. Open http://127.0.0.1:5000

## Pages
- `/` Home
- `/dashboard1` Olympic Performance and Regional Efficiency
- `/dashboard2` Investment and Host Advantage
- `/story` Olympic Performance Story

## Author
Bhavya
