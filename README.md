# PLP-PYTHON-ASSIGNMENT-WEEK-8


# 🌍 COVID-19 Global Data Tracker

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/pandas-1.3%2B-orange)
![License](https://img.shields.io/badge/license-MIT-green)

A data analysis project that tracks and visualizes global COVID-19 trends including cases, deaths, and vaccination progress using real-world data from [Our World in Data](https://ourworldindata.org/covid-cases).

## 📌 Features

- **Data Analysis**:
  - Time-series trends of cases/deaths
  - Vaccination progress comparison
  - Case fatality rate calculations
- **Visualizations**:
  - Interactive choropleth world map
  - Time-series line charts
  - Comparative bar/box plots
- **Outputs**:
  - PNG images of all plots
  - HTML interactive map
  - Cleaned CSV dataset

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/covid-19-tracker.git
cd covid-19-tracker
```

2. Install dependencies:
```bash
pip install pandas matplotlib seaborn plotly
```

3. Run the Jupyter Notebook:
```bash
jupyter notebook covid19_tracker.ipynb
```

## 📊 Data Sources

- Primary dataset: [Our World in Data COVID-19](https://covid.ourworldindata.org/data/owid-covid-data.csv)
- Updated daily with:
  - Cases/deaths statistics
  - Vaccination data
  - Population metrics

## 🎯 Project Structure

```
covid-19-tracker/
├── data/                   # Raw and cleaned data
│   ├── owid-covid-data.csv
│   └── cleaned_covid_data.csv
├── outputs/                # Generated files
│   ├── cases_over_time.png
│   ├── death_rates.png
│   ├── vaccination.png
│   └── world_map.html
└── covid19_tracker.ipynb   # Main analysis notebook
```

## 📈 Sample Visualizations

### Cases Over Time
![Cases Timeline](outputs/cases_over_time.png)

### Vaccination Progress
![Vaccination](outputs/vaccination.png)

### Interactive World Map
![World Map](outputs/world_map_screenshot.png)

## 🚀 How to Use

1. Run all cells in the Jupyter Notebook
2. Customize analysis by:
   - Editing the `countries` list
   - Adjusting date ranges
   - Adding new metrics
3. Access outputs in the `/outputs` folder

## 🤝 Contributing

Contributions welcome! Please:
1. Fork the project
2. Create a feature branch
3. Submit a PR

## 📜 License

MIT License - see [LICENSE](LICENSE) for details



---


