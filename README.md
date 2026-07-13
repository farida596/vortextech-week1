# Titanic Dataset Analysis

## Overview

This project explores the famous **Titanic dataset** using Python and Pandas. The notebook demonstrates a complete data analysis workflow, including loading the dataset, cleaning missing values, exploring the data, generating summary statistics, and creating visualizations.

The goal is to better understand the dataset while practicing fundamental data analysis techniques.

---

## Dataset

- **Dataset:** Titanic Passenger Data
- **Format:** CSV
- **File:** `titanic.zip` (contains the dataset)

---

## Project Workflow

### 1. Import Libraries

The notebook uses the following Python libraries:

- Pandas
- Matplotlib
- Seaborn

---

### 2. Load the Dataset

The dataset is loaded using Pandas and the first few rows are displayed to verify that the data has been imported successfully.

---

### 3. Explore the Dataset

Basic information about the dataset is examined, including:

- Dataset shape (rows and columns)
- Data types
- General dataset information
- First five records

---

### 4. Data Cleaning

The dataset is cleaned by:

- Filling missing values in the **Age** column using the median.
- Filling missing values in the **Embarked** column using the mode.
- Removing the **Cabin** column because most of its values are missing.
- Removing duplicate rows.

---

### 5. Summary Statistics

Several descriptive statistics are calculated, including:

- Overall statistical summary
- Mean passenger age
- Median ticket fare
- Number of passengers by gender

---

### 6. Data Visualization

Two visualizations are created:

#### Age Distribution Histogram

Shows how passenger ages are distributed across the dataset.

#### Gender Distribution Bar Chart

Displays the number of male and female passengers.

---

## Project Structure

```
├── Titanic_Analysis.ipynb
├── titanic.zip
└── README.md
```

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Learning Outcomes

By completing this project, I practiced:

- Loading datasets with Pandas
- Exploring dataset structure
- Handling missing values
- Removing duplicate data
- Computing descriptive statistics
- Creating data visualizations
- Organizing a complete data analysis workflow
