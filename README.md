COVID-19 Global Data Tracker
Project Overview
The COVID-19 Global Data Tracker is a data analysis project by Joseph Onyango that explores global COVID-19 trends, including cases and deaths, using the Johns Hopkins University (JHU) CSSE COVID-19 dataset. Built in a Jupyter Notebook, the project performs data cleaning, exploratory data analysis (EDA), visualizations, and narrative reporting to uncover insights about the pandemic’s impact across countries.
Objectives

Import and clean global COVID-19 data from JHU CSSE.
Analyze time trends for cases and deaths.
Compare metrics across countries (Kenya, United States, India).
Visualize trends with line charts and a choropleth map.
Summarize findings in a clear, reproducible Jupyter Notebook report.

Key Features

Data Cleaning: Reshapes JHU’s time-series data, handles missing values, and formats dates using pandas.
EDA: Calculates death rates and analyzes trends over time.
Visualizations: Includes line charts (cases, deaths) and a global choropleth map using Plotly.
Narrative: Provides 5 key insights, such as case trends, death rate variations, and data limitations.
Reproducibility: Loads data from JHU CSSE URLs, ensuring easy execution without local files.

Repository Contents

covid19_global_tracker.ipynb: The main Jupyter Notebook containing all code, visualizations, and narrative.
Note: No dataset files are included, as the notebook fetches data from:
Confirmed cases
Deaths



Setup Instructions
To run the project, you need a Jupyter Notebook environment with the required Python libraries. Follow these steps:

Clone or Download the Repository:
git clone https://github.com/princelailan/COVID-19_Global_Data_Tracker_JHU.git

Or download the covid19_global_tracker.ipynb file directly.

Install Dependencies:Ensure Python 3.8+ is installed, then install the required libraries:
pip install pandas matplotlib seaborn plotly


Run the Notebook:

Open covid19_global_tracker.ipynb in Jupyter Notebook, JupyterLab, or Google Colab.
Run all cells sequentially. The notebook fetches data directly from JHU CSSE URLs.



Usage

Running the Notebook: Execute each cell in covid19_global_tracker.ipynb to load data, clean it, generate visualizations, and view insights.
Customizing Analysis: Modify the countries list in the notebook (e.g., countries = ['Kenya', 'United States', 'India']) to analyze other countries.
Viewing Visualizations: The notebook produces:
Line charts for cases and deaths over time.
A choropleth map showing global case distribution.


Insights: Review the "Step 5: Insights & Narrative" section for key findings, including specific trends and anomalies for the selected countries.

Project Structure
The notebook follows a clear, step-by-step structure:

Data Loading & Exploration: Loads and inspects the JHU dataset.
Data Cleaning: Filters countries, reshapes time-series data, and handles missing values.
Exploratory Data Analysis (EDA): Analyzes trends and calculates death rates.
Choropleth Map: Displays global case distribution.
Insights & Narrative: Summarizes findings with a conclusion and future work suggestions.

Submission Details
This project, authored by Joseph Onyango, is part of a data analysis assignment. The covid19_global_tracker.ipynb file fulfills all requirements, including:

Data collection from JHU CSSE.
Data cleaning and preparation.
EDA with calculated metrics (death rates).
Visualizations (line charts, choropleth map).
A well-documented report with code, visuals, and narrative insights.

To review the project:

Access the notebook on GitHub: covid19_global_tracker.ipynb.
Run it in a Jupyter environment to reproduce the analysis.
Contact Joseph Onyango at jesuspromisesmedia@gmail.com for any questions or clarification.

Future Improvements

Integrate vaccination data from sources like Our World in Data to analyze immunization trends.
Develop an interactive dashboard using Streamlit or Dash for user-driven exploration.
Investigate the impact of specific policies (e.g., lockdowns, travel bans) on case trends.

References

Dataset: JHU CSSE COVID-19
Alternative Source: Our World in Data COVID-19
Libraries: pandas, matplotlib, seaborn, plotly

Contact
Author: Joseph OnyangoEmail: jesuspromisesmedia@gmail.comGitHub: princelailan  
For questions or issues, please open an issue in this repository or contact Joseph via email.
Happy exploring!
