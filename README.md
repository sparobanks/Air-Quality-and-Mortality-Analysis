# Air Quality and Mortality Analysis

## Overview

This project analyses air quality and mortality data to explore the relationship between air pollution, deprivation and health outcomes.

The project uses Apache Spark and PySpark to process and analyse the data. The aim is to identify patterns in air quality and mortality and understand how these patterns differ across areas and deprivation levels.

## Objectives

The main objectives of this project are to:

* Analyse air quality and mortality data.
* Clean and prepare the datasets for analysis.
* Explore differences in mortality across areas.
* Investigate the relationship between air pollution, deprivation and mortality.
* Identify patterns in mortality rates and avoidable mortality.
* Present the results using clear visualisations.

## Technologies Used

* Python
* Apache Spark
* PySpark
* Pandas
* Jupyter Notebook
* Matplotlib
* Data Analysis
* Data Visualisation

## Project Structure

```text
Air-Quality-and-Mortality-Analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── notebooks/Death-caused-by-air-pollution.ipynb
│
├── src/
│   └── analysis.py
│
└── results/
    ├── charts/
    └── outputs/
```

## Data Analysis

The analysis covers areas such as:

* Air quality levels
* Mortality rates
* Avoidable mortality
* Deprivation levels
* Geographic differences
* Relationships between environmental and health indicators

PySpark was used to process and analyse the data efficiently. Pandas and Matplotlib were used where appropriate for further analysis and visualisation.

## Workflow

The project follows these main steps:

1. Load the datasets.
2. Inspect and clean the data.
3. Handle missing or inconsistent values.
4. Transform the data into a suitable format for analysis.
5. Analyse air quality, deprivation and mortality indicators.
6. Compare results across different groups and locations.
7. Create visualisations to present the findings.
8. Interpret the results.

## Key Skills Demonstrated

This project demonstrates practical experience in:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Big data processing with PySpark
* Working with real-world datasets
* Data transformation and aggregation
* Statistical and comparative analysis
* Data visualisation
* Communicating analytical findings

## Running the Project

Clone the repository:

```bash
git clone https://github.com/sparobanks/Air-Quality-and-Mortality-Analysis.git
cd Air-Quality-and-Mortality-Analysis
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
notebooks/Death-caused-by-air-pollution.ipynb
```

Apache Spark must also be installed and configured to run the PySpark analysis.

## Results

The analysis provides insights into patterns between air quality, deprivation and mortality. The results are presented through data summaries and visualisations to make the findings easier to understand.

Charts and other outputs from the analysis are available in the `results/` directory.

## Author

**Jasper Chinedu**

MSc Computer Science & Technology
Data Science | Machine Learning | Artificial Intelligence
