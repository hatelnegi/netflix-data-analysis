# 🎬 Netflix Data Analysis

## 📌 Project Overview

This project analyzes a Netflix dataset using Python and Pandas to explore the content available on the platform.

The analysis focuses on understanding the distribution of **Movies and TV Shows**, identifying the countries producing the most Netflix content, and examining how the number of titles has changed across release years.

The project also includes data cleaning and standardization to prepare the dataset for analysis.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand the structure and quality of the Netflix dataset
- Identify and handle missing values and duplicate records
- Standardize inconsistent data
- Analyze the distribution of Movies vs TV Shows
- Identify the countries producing the highest number of titles
- Analyze Netflix content by release year
- Identify years with high content production
- Create visualizations to communicate findings clearly
- Derive business-oriented insights from the data

---

## 📂 Dataset

The project uses a Netflix titles dataset containing information about movies and TV shows available on Netflix.

Key attributes used in the analysis include:

- `type`
- `title`
- `country`
- `release_year`
- `rating`
- Other descriptive attributes related to Netflix titles

The dataset was cleaned and transformed before performing the analysis.

---

## 🧹 Data Cleaning & Preparation

The following data preparation steps were performed:

- Checked the dataset structure and data types
- Identified missing/null values
- Checked for `"Not Given"` values
- Checked for duplicate records
- Removed unnecessary spaces from text values
- Standardized values in:
  - `country`
  - `rating`
  - `type`
- Converted `release_year` into a numeric format
- Created a cleaned dataset
- Exported the cleaned data as `Netflix_Cleaned.csv`

---

## 📊 Analysis Performed

### 1. Movies vs TV Shows

The project analyzes the distribution of content types available on Netflix.

The analysis includes:

- Total number of Movies
- Total number of TV Shows
- Percentage distribution
- Bar chart
- Pie chart

This helps understand the overall composition of Netflix's content library.

---

### 2. Country-wise Content Analysis

The `country` column can contain multiple countries for a single title.

To analyze country-level production:

- Multiple country values were separated
- The data was transformed using `explode()`
- Titles were counted for each country
- The top 10 countries were identified
- A horizontal bar chart was created

This provides an overview of the countries contributing the largest amount of content to the dataset.

---

### 3. Release Year Analysis

The project also examines Netflix titles based on their release year.

The analysis includes:

- Number of titles released in each year
- Identification of the highest and lowest release years
- Year-wise content trends
- Line chart showing the trend
- Top 10 years based on number of titles

This helps identify periods in which a larger number of titles were represented in the dataset.

---

## 📈 Visualizations

The project uses visualizations to make the analysis easier to understand.

Visualizations include:

- 📊 Bar charts
- 🥧 Pie charts
- 📈 Line charts
- 📊 Horizontal bar charts

These visualizations are used to communicate patterns and trends in the Netflix dataset.

---

## 💡 Key Insights

The analysis provides insights into:

- The distribution between Movies and TV Shows
- Countries contributing significant amounts of Netflix content
- Changes in the number of titles across release years
- Years with comparatively high numbers of titles
- Data quality issues such as missing and `"Not Given"` values

These insights demonstrate how data cleaning, exploratory analysis, and visualization can be used to understand a content-based dataset.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Data Standardization
     ↓
Exploratory Data Analysis
     ↓
Country & Content Analysis
     ↓
Release Year Analysis
     ↓
Data Visualization
     ↓
Business Insights
