# Data Cleaning & Reporting Automation using Tableau

## Project Overview

This project demonstrates how to automate data cleaning and reporting workflows using Tableau. The dataset contains customer sales information with missing values, duplicate records, and inconsistent data. Tableau was used to clean the data, create visualizations, and generate an interactive dashboard.

## Objectives

* Handle missing values in the dataset
* Identify and manage duplicate records
* Create calculated fields for data preprocessing
* Build automated reports and visual dashboards
* Improve reporting efficiency through visualization

## Dataset

The dataset contains the following fields:

* Customer ID
* Customer Name
* City
* Category
* Sales

### Data Quality Issues

* Missing City values
* Missing Category values
* Missing Sales values
* Duplicate customer records

## Data Cleaning Process

### 1. Handling Missing Values

Created calculated fields:

#### Clean City

```tableau
IFNULL([City], "Unknown")
```

#### Clean Category

```tableau
IFNULL([Category], "Others")
```

#### Clean Sales

```tableau
IFNULL([Sales], 0)
```

### 2. Duplicate Record Handling

Duplicate customer records were identified and excluded during analysis to ensure accurate reporting.

## Dashboard Components

### Total Sales KPI

Displays the overall sales value from the cleaned dataset.

### Sales by Category

Shows sales performance across different product categories.

### Sales by City

Visualizes sales distribution across cities.

### Customer Distribution

Displays the number of customers in each city.

## Tools Used

* Tableau Public
* CSV Dataset
* Data Cleaning Techniques
* Dashboard Design

## Key Learnings

* Data preprocessing and cleaning
* Handling null values using calculated fields
* Creating KPI metrics
* Building interactive dashboards
* Automating reporting workflows
* Data visualization best practices

## Project Outcome

Successfully cleaned the dataset, handled missing values, generated business insights, and developed an automated reporting dashboard using Tableau.

## Screenshots

### Raw Dataset

(Add screenshot here)

### Data Cleaning Process

(Add screenshot here)

### Final Dashboard

(Add screenshot here)

## Author

Mathi
