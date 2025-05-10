# 🦠 COVID-19 Global Data Tracker

A data analysis and visualization project by **Joseph Onyango** that explores global COVID-19 trends, including confirmed cases and deaths, using the Johns Hopkins University (JHU) CSSE COVID-19 dataset. Built using Python in Jupyter Notebook, the project covers data cleaning, exploratory data analysis (EDA), interactive visualizations, and key insights.

---

## 📌 Project Overview

This project investigates the global impact of COVID-19 using real-world data. It provides:

- Cleaned and reshaped JHU time-series data.
- Comparative analysis across countries (e.g., Kenya, United States, India).
- Visual storytelling through line charts and choropleth maps.
- Narrative summaries and data-driven insights.

---

## 🎯 Objectives

- Import and preprocess global COVID-19 data from JHU CSSE.
- Analyze time trends in cases and deaths.
- Compare country-level data.
- Create interactive visualizations (line charts and global maps).
- Deliver a clear and reproducible data story.

---

## ✨ Key Features

- **Data Cleaning**: Reshaping time-series data, handling null values, and formatting dates using `pandas`.
- **EDA**: Time-based analysis and calculation of death rates.
- **Visualizations**: 
  - Line charts for country-level trends.
  - Choropleth map for global case distribution using `plotly`.
- **Narrative Insights**: Highlights patterns, anomalies, and limitations of the dataset.
- **Reproducibility**: Uses up-to-date data fetched directly from JHU CSSE URLs.

---

## 📁 Repository Contents

- `covid19_global_tracker.ipynb` — Main Jupyter Notebook containing the complete workflow.
- No local datasets are included; data is fetched live from:
  - Confirmed cases: https://github.com/CSSEGISandData/COVID-19
  - Deaths: https://github.com/CSSEGISandData/COVID-19

---

## ⚙️ Setup Instructions

### 1. Clone or Download the Repository

```bash
git clone https://github.com/princelailan/COVID-19_Global_Data_Tracker_JHU.git
```

Or download the `covid19_global_tracker.ipynb` file directly from the repository.

### 2. Install Required Libraries

Ensure Python 3.8+ is installed, then install dependencies:

```bash
pip install pandas matplotlib seaborn plotly
```

### 3. Run the Notebook

- Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab.
- Run all cells in order. The notebook automatically pulls data from JHU CSSE.

---

## 🚀 Usage

- **Run the Notebook**: Load data, clean it, visualize, and extract insights.
- **Customize Countries**: Modify the `countries` list (e.g., `['Kenya', 'India', 'United States']`) to analyze different regions.
- **View Outputs**:
  - Line charts of cases and deaths.
  - A global choropleth map of confirmed cases.

---

## 📊 Project Structure

1. **Data Loading & Exploration**
2. **Data Cleaning & Reshaping**
3. **Exploratory Data Analysis (EDA)**
4. **Choropleth Mapping**
5. **Narrative & Insights**

---

## 🔍 Insights & Narrative

Visit **"Step 5: Insights & Narrative"** in the notebook to explore key takeaways:

- Trends of case surges over time.
- Death rate comparisons.
- Data limitations (e.g., underreporting, inconsistent testing).

---

## 📝 Submission Details

This notebook fulfills the final submission for the Python Development Module and includes:

- Live data import from JHU CSSE
- Full EDA process and visualizations
- Well-documented steps and conclusions

📄 Access it here: [GitHub Repo](https://github.com/princelailan/COVID-19_Global_Data_Tracker_JHU)

---

## 🌱 Future Improvements

- Integrate vaccination data (e.g., from Our World in Data).
- Create an interactive dashboard using Streamlit or Dash.
- Analyze policy effects (e.g., lockdowns, curfews) on COVID-19 trends.

---

## 📚 References

- Dataset: [JHU CSSE COVID-19](https://github.com/CSSEGISandData/COVID-19)
- Alternative Source: [Our World in Data COVID-19](https://ourworldindata.org/coronavirus)
- Libraries: `pandas`, `matplotlib`, `seaborn`, `plotly`

---

## 📬 Contact

**Author**: Joseph Onyango  
**Email**: [jesuspromisesmedia@gmail.com](mailto:jesuspromisesmedia@gmail.com)  
**GitHub**: [@princelailan](https://github.com/princelailan)

For issues or feedback, please open an issue in the repository or reach out by email.  
**Happy exploring!** 🎉
