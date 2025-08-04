# Predicting SpaceX Falcon 9 Landing Success

![SpaceX Falcon 9 Landing](https://science.nasa.gov/wp-content/uploads/2023/10/KSC-20231013-PH-SPX01_0006-scaled-1.jpg)

## Project Overview
This data science project predicts SpaceX Falcon 9 first-stage landing success with **94% accuracy** using:
- Launch history data from SpaceX API
- Machine learning (Decision Trees, SVM, Logistic Regression)
- Interactive geospatial analytics

## Key Features
✅ **Data Pipeline**
- Automated data collection via SpaceX REST API
- Web scraping for booster specifications
- Advanced feature engineering

✅ **Analytics**
- Interactive Folium maps of launch sites
- Plotly Dash dashboard with real-time filters
- SQL analysis of 120+ launch records

✅ **Modeling**
- Best model: Decision Tree (94% test accuracy)
- Identified optimal payload range: 4,200-6,700kg
- Explainable AI with feature importance

## Technical Stack
| Component | Technologies |
|-----------|--------------|
| Data Collection | Python, BeautifulSoup, SpaceX API |
| Analysis | Pandas, SQL, Plotly |
| Visualization | Folium, Matplotlib, Plotly Dash |
| Modeling | Scikit-learn, SHAP |


## Getting Started
1. Clone repository:
   ```bash
   git clone https://github.com/SalehSuliman/Predicting-SpaceX-Falcon-9-Landings-using-Data-Science.git

2. Install dependencies:

   ```bash
   pip install -r requirements.txt

3. Run Jupyter notebooks in order.
