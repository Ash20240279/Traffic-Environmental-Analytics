# Traffic & Environmental Analytics

An end-to-end data analysis project exploring the relationship between traffic congestion, environmental conditions, accidents, public transportation, and infrastructure factors.

## Project Overview

This project analyzes multiple datasets to understand the factors that influence urban traffic conditions and identify patterns that can support better transportation and infrastructure decisions.

The analysis combines traffic, air quality, weather, district, public transport, emergency event, city event, and power grid data.

## Objectives

The project focuses on questions such as:

* When and where does traffic congestion become most severe?
* How do weather conditions and special events affect traffic volume?
* What is the relationship between traffic speed and accident severity?
* Which districts experience high traffic density and pollution?
* During which off-peak hours can high speeds contribute to severe accidents?
* How do power outages and electrical grid issues affect traffic signal flow and congestion?
* How do public transportation and emergency events relate to traffic conditions?

## Datasets

The project uses the following datasets:

* `traffic.csv` — traffic volume, congestion, speed, and accident-related information
* `air_quality.csv` — air pollution measurements and air quality indicators
* `weather.csv` — weather and environmental conditions
* `city_events.csv` — events that may influence traffic patterns
* `districts.csv` — district-level information
* `emergency_events.csv` — emergency-related events
* `power_grid.csv` — power outages and electrical grid information
* `public_transport.csv` — public transportation data
* `data_dictionary.csv` — descriptions of dataset columns

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Analysis Workflow

The project follows a complete data analysis workflow:

1. Data loading
2. Data exploration
3. Data quality checking
4. Missing-value analysis
5. Duplicate detection
6. Data cleaning
7. Data transformation
8. Exploratory Data Analysis (EDA)
9. Statistical comparisons
10. Visualization
11. Insight extraction

## Key Areas of Analysis

### Traffic & Congestion

Analysis of traffic volume, congestion levels, average speed, peak hours, rush hours, weekends, and other traffic patterns.

### Traffic & Accidents

Investigation of how traffic speed, congestion, weather, and other conditions relate to accident frequency and severity.

### Air Quality & Traffic

Exploration of the relationship between traffic conditions and pollution indicators such as:

* PM2.5
* PM10
* NO₂
* O₃
* CO
* AQI

### District Density & Pollution

Identification of districts experiencing high traffic density together with elevated pollution levels.

### Infrastructure & Power Outages

Analysis of how power outages and electrical grid issues may affect traffic signal flow and congestion.

### Events & Weather

Investigation of how weather conditions and special city events influence traffic patterns.

## Project Structure

```text
Traffic-Environmental-Analytics/
│
├── Traffic_Environmental_Analytics.ipynb
│
├── data/
│   ├── air_quality.csv
│   ├── city_events.csv
│   ├── data_dictionary.csv
│   ├── districts.csv
│   ├── emergency_events.csv
│   ├── power_grid.csv
│   ├── public_transport.csv
│   ├── traffic.csv
│   └── weather.csv
|
│
└── README.md
```

## Results

The analysis reveals several patterns connecting traffic conditions with environmental, behavioral, and infrastructure factors.

The notebook contains the detailed analysis, visualizations, comparisons, and key insights derived from the data.

## How to Run

Clone the repository and install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Then open:

```text
Traffic_Environmental_Analytics.ipynb
```

Make sure the `data` folder remains in the same repository structure so that the notebook can access the datasets correctly.

## Author

**Shahd Ayman Kamal**
**ashayman111@gmail.com**
Computer Science & Artificial Intelligence Student
Cairo University

Interested in **Data Analysis, Machine Learning, and Data-driven Solutions**.
