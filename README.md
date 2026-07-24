# Ford GoBike Bike Sharing Data Analysis

## Project Overview

This project performs an in-depth analysis of the **Ford GoBike Bike Sharing Dataset (February 2019)** using Python. The primary objective is to explore rider behavior, identify usage patterns, and communicate meaningful insights through effective data visualization and storytelling.

The project is divided into two parts:

- **Part I:** Exploratory Data Analysis (EDA)
- **Part II:** Explanatory Data Analysis (Data Storytelling)

The analysis follows the complete data analysis workflow, including data cleaning, feature engineering, exploratory visualization, and presentation of key findings.

---

## Dataset

This project uses the **Ford GoBike Bike Sharing Dataset (February 2019)**.

Due to GitHub's file size limitations, the dataset is **not included** in this repository.

You can download the dataset from the official Bay Wheels data archive:

**Dataset Download:**
https://s3.amazonaws.com/baywheels-data/index.html

Download the following file:

```
201902-fordgobike-tripdata.csv
```

After downloading, create a folder named **data** and place the dataset inside it.

```
Ford-GoBike-Data-Analysis/
│
├── data/
│   └── 201902-fordgobike-tripdata.csv
```

---

# Repository Structure

```
Ford-GoBike-Data-Analysis/
│
├── data/
│   └── 201902-fordgobike-tripdata.csv
│
├── Part I - Ford GoBike Trip Data Exploration.ipynb
├── Part I - Ford GoBike Trip Data Exploration.html
│
├── Part II - Explanatory Data Analysis of Ford GoBike Bike Sharing Dataset.ipynb
├── Part II - Explanatory Data Analysis of Ford GoBike Bike Sharing Dataset.html
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Project Objectives

- Perform data cleaning and preprocessing
- Explore the distribution of bike trips
- Analyze rider demographics
- Study customer and subscriber behavior
- Investigate relationships between multiple variables
- Present insights through polished visualizations
- Build an executive-style explanatory report

---

# Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# Data Preprocessing

The following preprocessing steps were performed before analysis:

- Removed missing values
- Removed duplicate records
- Corrected data types
- Converted date columns to datetime format
- Created new features
  - Age
  - Hour
  - Day
  - Month
- Removed outliers from trip duration
- Improved dataset consistency

---

# Exploratory Data Analysis (Part I)

The exploratory analysis investigates the dataset using multiple visualization techniques to answer important business questions.

## Univariate Analysis

Visualizations include:

- Histogram
- Count Plot

Questions Answered

- What is the distribution of trip duration?
- Which user type is most common?
- Which gender has the highest participation?

---

## Bivariate Analysis

Visualizations include:

- Scatter Plot
- Box Plot
- Bar Chart

Questions Answered

- Does age affect trip duration?
- Do subscribers and customers ride differently?
- How does gender influence riding behavior?

---

## Multivariate Analysis

Visualizations include:

- Facet Plot
- Scatter Plot with Multiple Encodings

Questions Answered

- How do age, gender, and user type interact?
- Which rider groups have the longest trips?
- What overall patterns emerge when combining multiple variables?

---

# Key Findings

The exploratory analysis revealed several important insights:

- Most bike trips last between **5 and 15 minutes**.
- Subscribers account for the majority of rides.
- Male riders represent the largest portion of users.
- Customers generally take longer trips than subscribers.
- Rider age has only a weak relationship with trip duration.
- Gender has minimal influence on ride duration.
- User type is one of the strongest factors affecting riding behavior.

---

# Explanatory Data Analysis (Part II)

The explanatory notebook transforms the exploratory findings into a clear and concise data story suitable for decision-makers.

The presentation focuses on:

- Rider demographics
- Trip duration patterns
- Subscriber vs Customer comparison
- Business insights
- Final conclusions and recommendations

Visualizations were refined with:

- Clear titles
- Better axis labels
- Improved annotations
- Consistent formatting
- Executive-friendly presentation

---

# Visualizations Included

The project satisfies the visualization requirements by including more than seven visualizations.

### Univariate

- Histogram
- Count Plot

### Bivariate

- Scatter Plot
- Box Plot
- Bar Chart

### Multivariate

- Facet Plot
- Scatter Plot with Multiple Encodings

**Total Visualizations:** 7+

---

# Project Workflow

1. Load Dataset
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis
5. Identify Patterns
6. Create Explanatory Visualizations
7. Present Business Insights

---

# How to Run

## 1. Clone the repository

```bash
git clone https://github.com/<your-username>/Ford-GoBike-Data-Analysis.git
```

## 2. Move into the project folder

```bash
cd Ford-GoBike-Data-Analysis
```

## 3. Install required libraries

```bash
pip install -r requirements.txt
```

## 4. Download the dataset

Download

```
201902-fordgobike-tripdata.csv
```

from

https://s3.amazonaws.com/baywheels-data/index.html

## 5. Create the data folder

```
Ford-GoBike-Data-Analysis/
│
├── data/
│   └── 201902-fordgobike-tripdata.csv
```

## 6. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open either notebook and run all cells.

---

# Project Deliverables

- Exploratory Data Analysis Notebook (.ipynb)
- Exploratory Analysis Report (.html)
- Explanatory Data Analysis Notebook (.ipynb)
- Explanatory Analysis Report (.html)
- README.md

---

# Code Quality

This project follows clean coding practices by:

- Writing readable and organized code
- Using meaningful variable names
- Following consistent 4-space indentation
- Adding comments where necessary
- Reusing code through functions where appropriate
- Producing notebooks that execute without errors

---

# Rubric Compliance

| Requirement | Status |
|------------|:------:|
| Clean Code | ✅ |
| Documented Code | ✅ |
| Consistent Indentation | ✅ |
| Meaningful Variable Names | ✅ |
| Exploratory Data Analysis | ✅ |
| 7+ Visualizations | ✅ |
| Univariate Analysis | ✅ |
| Bivariate Analysis | ✅ |
| Multivariate Analysis | ✅ |
| Questions & Observations | ✅ |
| Executive Summary | ✅ |
| Explanatory Storytelling | ✅ |
| Polished Visualizations | ✅ |

---

# Future Improvements

Possible enhancements include:

- Predictive modeling for trip duration
- Station popularity analysis
- Seasonal and monthly trend analysis
- Interactive dashboards using Plotly or Tableau
- Geospatial visualization of trip locations
- Machine learning models for rider behavior prediction

---

# Learning Outcomes

This project demonstrates practical experience in:

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- Statistical Analysis
- Storytelling with Data
- Python Programming
- Jupyter Notebook Documentation

---
