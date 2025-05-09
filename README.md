# COVID-19 Global Data Tracker

## Description
This project analyzes global COVID-19 trends for Kenya, USA, India, and Brazil using the Our World in Data dataset. It includes data cleaning, exploratory data analysis (EDA), vaccination progress visualization, and interactive choropleth maps, all presented in a Jupyter Notebook.

## Objectives
- Import and clean the global COVID-19 dataset from Our World in Data.
- Analyze trends in cases, deaths, and death rates over time.
- Visualize vaccination rollouts and compare progress across countries.
- Create interactive maps to show global case and vaccination distributions.
- Summarize findings in a well-documented Jupyter Notebook with insights.

## Tools and Libraries
- **Python**: Core programming language.
- **Jupyter Notebook**: Interactive environment for analysis and reporting.
- **pandas**: Data manipulation and analysis.
- **matplotlib & seaborn**: Line, bar, pie charts, and heatmaps.
- **plotly.express**: Interactive choropleth maps.
- **VS Code**: Development environment.

## How to Run or View the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/andrewCHUI01/CovidTracker.git
   cd CovidTracker

   python -m venv venv
.\venv\Scripts\activate  # Windows
# or source venv/bin/activate  # Mac/Linux

pip install pandas matplotlib seaborn plotly

Download the Dataset:
Download owid-covid-data.csv from Our World in Data and place it in the CovidTracker folder.

Run the Notebook:
Open CovidTracker.ipynb in VS Code or Jupyter Notebook.

Run all cells to see data processing, visualizations (charts, maps), and insights.

View Interactive Maps:
Open total_cases_map.html and percent_vaccinated_map.html in a web browser.

Insights and Reflections
Key Insights
High Case Counts in USA and India: The USA and India led with millions of cases, driven by large populations and early pandemic waves (Segment 4 line charts).

Brazil’s High Death Rate: Brazil’s death rate (total_deaths / total_cases) was notably high, indicating severe outcomes (Segment 4 summary).

USA’s Vaccination Success: The USA reached 70% fully vaccinated, outpacing India (50%) and Kenya (~20%) (Segment 5 charts).

Kenya’s Vaccination Lag: Kenya’s ~20% vaccination rate highlighted access challenges (Segment 5 pie charts).

Global Trends: Choropleth maps (Segment 6) showed case hotspots in North America, Europe, and South Asia, with lower cases in Africa, possibly due to underreporting.

Anomalies
India’s 2021 Delta wave caused a sharp spike in new cases (Segment 4).

Early vaccination data was missing, requiring careful handling (Segment 5).

Cases and deaths had a ~0.9 correlation, as expected (Segment 4 heatmap).

Reflections
Working with real-world data taught me to handle missing values and time-series challenges.

Creating interactive maps with Plotly was a highlight—visualizing global trends was eye-opening.

Learning Git and GitHub was a new adventure, and pushing my project online felt rewarding!

Files
CovidTracker.ipynb: Main Jupyter Notebook with all code, visuals, and narrative.

cleaned_covid_data.csv, eda_covid_data.csv, vaccination_covid_data.csv, choropleth_covid_data.csv: Processed datasets.

total_cases_map.html, percent_vaccinated_map.html: Interactive choropleth maps.

