# Data_Science_Projects
This is my repository for data visualization section of netlfix dataset in which i designed different charts accordingly to the netflix dataset.
# Netflix Movies and TV Shows Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?logo=matplotlib)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-lightblue?logo=seaborn)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Table of Contents
1.  [Project Overview](#-project-overview)
2.  [Dataset](#-dataset)
3.  [Objectives](#-objectives)
4.  [Tech Stack](#-tech-stack)
5.  [Installation & Usage](#-installation--usage)
6.  [Methodology & Analysis](#-methodology--analysis)
7.  [Results & Findings](#-results--findings)
8.  [Visualizations](#-visualizations)
9.  [Conclusion & Insights](#-conclusion--insights)
10. [Future Work](#-future-work)
11. [License](#-license)
12. [Contact](#-contact)

---

## 🧐 Project Overview

This project involves a comprehensive exploratory data analysis (EDA) of Netflix's movie and TV show catalog. The goal is to uncover trends, patterns, and insights into Netflix's content strategy, including content growth over time, distribution of ratings, geographic analysis of production, and genre trends. This analysis helps understand the evolution and composition of Netflix's library.

## 📁 Dataset

*   **Source:** [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
*   **Description:** This dataset contains listings of all movies and TV shows available on Netflix as of 2021. It includes details such as title, type, director, cast, country, date added, release year, rating, duration, and genres.
*   **Size:** 8,807 rows x 12 columns

## 🎯 Objectives

The main questions this analysis seeks to answer are:
1.  What is the ratio of Movies to TV shows on Netflix?
2.  How has Netflix's content output changed over the years?
3.  Which countries produce the most content on Netflix?
4.  What are the most common genres and ratings?
5.  Is there a seasonal trend for new releases?
6.  What is the average duration of movies?

## 🛠 Tech Stack

*   **Programming Language:** Python 3.8+
*   **Libraries:**
    *   **Data Manipulation:** Pandas, NumPy
    *   **Data Visualization:** Matplotlib, Seaborn
*   **Environment:** Jupyter Notebook
*   **Dataset Format:** CSV

## 💻 Installation & Usage

### Prerequisites
Ensure you have Python and Jupyter Notebook installed. We recommend using [Anaconda](https://www.anaconda.com/products/distribution).

### Steps to Run the Project
1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/Syed Wasia Ali Shah/netflix-data-analysis.git
    cd netflix-data-analysis
    ```

2.  **Install Dependencies:**
    Install the required libraries using pip:
    ```bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```

3.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Open the `Netflix_Analysis.ipynb` file from the Jupyter dashboard.

4.  **Run the Analysis:**
    Run the cells in the notebook sequentially to execute the code and see the analysis.

## 🔍 Methodology & Analysis

1.  **Data Loading & Inspection:** Loaded the dataset and used `.info()`, `.describe()`, and `.isnull().sum()` to understand its structure and missing values.
2.  **Data Cleaning:**
    *   Handled missing values in `director`, `cast`, and `country` by filling them with "Not Specified".
    *   Converted the `date_added` column to datetime format.
    *   Extracted new features like `month_added` and `year_added`.
3.  **Exploratory Data Analysis (EDA):**
    *   Performed univariate and bivariate analysis on key features.
    *   Used value counts and grouping to analyze trends over time and across categories.
4.  **Data Visualization:** Created various plots to visually communicate the findings effectively.

## 📊 Results & Findings

*   **Content Type Distribution:** Netflix's catalog consists of **69.1%** Movies and **30.9%** TV Shows.
*   **Growth Over Time:** Netflix has dramatically increased its original content production since 2015. The number of titles added peaked in 2019.
*   **Top Production Countries:** The United States is the leading producer of content on Netflix by a significant margin, followed by India and the United Kingdom. Over 30% of content has no country data listed.
*   **Ratings:** The most common rating is **TV-MA** (Mature Audience), followed by **TV-14** and **R**. This indicates a large portion of content is for adult audiences.
*   **Genre Trends:** The most common genres are **International Movies**, **Dramas**, and **Comedies**.
*   **Release Trends:** Most new content is added to the platform in the months of **July, December, and October**.

## 📈 Visualizations

Key visualizations from this analysis include:
1.  A pie chart showing the split between Movies and TV Shows.
2.  A line chart showing the growth of content added per year.
3.  A bar chart showing the top 10 countries producing content.
4.  A bar chart showing the distribution of content ratings.

*(After saving your charts as PNG files in an `images/` folder, you can add them here like this:)*
<!--
![Content Type Distribution](images/content_type_pie.png)
*Figure 1: Distribution of Movies vs. TV Shows on Netflix.*
-->

## 🧠 Conclusion & Insights

The analysis reveals that Netflix's library is predominantly comprised of movies, with a strong focus on content produced in the United States. The significant growth in content post-2015 highlights Netflix's shift towards original programming. The prevalence of TV-MA and TV-14 ratings suggests their core target audience is teens and adults.

This project successfully outlined the structure and trends within the Netflix catalog, providing a clear picture of their content strategy.

## 🔮 Future Work

*   **Sentiment Analysis:** Analyze movie descriptions to predict genres or success.
*   **Comparative Analysis:** Compare Netflix's catalog with other streaming services like Disney+ or Hulu.
*   **Recommendation System:** Build a simple content-based recommendation system using the genres and descriptions.

## 📜 License

This project is licensed under the MIT License. The dataset was sourced from Kaggle and is credited to Shivam Bansal.

## 📧 Contact

Created by SYED WASIA ALI SHAH - feel free to contact me!

*   GitHub: Syed Wasia Ali Shah https://github.com/Wasay-3435/Data_Science_Projects
*   Email: syedwasay899@gmail.com

---
