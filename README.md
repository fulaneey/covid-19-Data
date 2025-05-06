# covid-19-Data
# COVID-19 Global Data Tracker

![Sample Visualization](sample_viz.jpg)  

## Project Description
This project analyzes global COVID-19 trends including cases, deaths, recoveries, and vaccination progress. The analysis is presented as a Jupyter Notebook with interactive visualizations and data-driven insights about the pandemic's progression across different countries.

## Objectives
- Import and clean real-world COVID-19 data from reliable sources
- Analyze time trends in cases, deaths, and vaccinations
- Compare metrics across countries and regions
- Visualize trends with various chart types
- Generate and communicate data-driven insights

## Tools & Libraries Used
- **Python 3** (with Jupyter Notebook)
- **Data Processing**: pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly Express
- **Geospatial Visualization**: Geopandas (optional)
- **Data Sources**: Our World in Data COVID-19 dataset

## How to Use This Project

### Prerequisites
- Python 3.8+
- Jupyter Notebook/Lab
- Required libraries (install via `pip install -r requirements.txt`)

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/fulaneey/covid-19-Data.git
   cd covid-19-Data

# Install dependencies:

bash
pip install -r requirements.txt
Download the dataset:

Option 1: Run data/download_data.py

Option 2: Manually download from Our World in Data

# Launch Jupyter Notebook:

bash
jupyter notebook covid_analysis.ipynb
Run all cells to generate the analysis and visualizations

# Alternative Viewing
For quick viewing without running the notebook:

View the static HTML export at docs/report.html

View sample visualizations in the visualizations/ folder

# Key Insights
Vaccination Disparities: Developed nations showed vaccination rates 3-5x higher than developing countries by Q2 2021.

Case Fatality Rates: Countries with robust healthcare systems maintained lower death rates despite high case numbers.

Wave Patterns: Most countries experienced distinct waves of infection approximately 4-6 months apart.

Vaccination Impact: Nations with early vaccination campaigns saw 40-60% reduction in subsequent case growth rates.

Data Quality: Reported cases strongly correlated with testing capacity, suggesting potential undercounting in resource-limited settings.

Reflections
This project provided valuable experience in:

Cleaning and processing real-world, messy epidemiological data

Creating effective time-series visualizations

Identifying meaningful patterns in global health data

Communicating data insights to non-technical audiences

The analysis revealed both expected patterns (like vaccination disparities) and surprising findings (like the nonlinear relationship between population density and transmission rates).

Future Enhancements
Add automated data updates via API

Implement interactive dashboards with Streamlit

Include machine learning for case predictions

Expand to subnational/state-level data