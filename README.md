# Pluto-AI-ML-Internship-Project-1-Exploratory-Data-Analysis-EDA-

📌 Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of the Netflix Movies & TV Shows Dataset. The objective is to examine Netflix's content library, identify meaningful trends, clean and preprocess the data, create insightful visualizations, and derive actionable business insights that can support strategic decision-making.

The analysis follows the complete data analysis workflow, beginning with data loading and inspection, followed by data cleaning, feature engineering, exploratory analysis, visualization, and interpretation of findings.

This project was developed as part of the Pluto Academy AI & Machine Learning Internship.


🎯 Objectives

The primary objectives of this project are to:

Understand the structure and quality of the Netflix dataset.
Perform data cleaning and preprocessing.
Handle missing values and duplicate records.
Engineer useful features for deeper analysis.
Explore relationships between different variables.
Visualize important trends using interactive charts.
Extract meaningful business insights.
Provide data-driven recommendations based on the analysis.


📂 Dataset Information

Dataset Name
Netflix Movies and TV Shows Dataset

Source
https://www.kaggle.com/datasets/shivamb/netflix-shows

Dataset Description
The dataset contains metadata for thousands of Netflix titles, including movies and television shows available on the platform.

Important attributes include:
Show ID
Type (Movie / TV Show)
Title
Director
Cast
Country
Date Added
Release Year
Rating
Duration
Genre (Listed In)
Description


🛠️ Technologies Used

Python

Google Colab

Pandas

NumPy

Plotly

Matplotlib

Seaborn


📋 Project Workflow

The project was completed following the standard Exploratory Data Analysis pipeline.

1. Data Collection
Imported the Netflix dataset from Kaggle.
Loaded the dataset using Pandas.

2. Data Inspection
The dataset was inspected to understand its structure by analyzing:
Dataset dimensions
Column names
Data types
Statistical summaries
Missing values
Duplicate records

3. Data Cleaning
Several preprocessing techniques were applied to improve data quality.
These include:
Removing duplicate records
Handling missing values
Standardizing categorical values
Converting date columns into datetime format
Extracting numerical values from duration
Creating new features for month and year
Cleaning country and director information

The cleaned dataset was then used for further analysis.


📊 Exploratory Data Analysis

The notebook answers multiple analytical questions about Netflix's content library.
The analysis includes:

1. Movies vs TV Shows Distribution
Examines the proportion of movies and television shows available on Netflix.

2. Content Growth Over Time
Analyzes how Netflix expanded its content library between 2008 and 2021.

3. Movie Runtime Distribution
Investigates the duration of movies and identifies common runtime ranges.

4. TV Show Season Distribution
Studies how many seasons most Netflix television shows contain.

5. Top Content Producing Countries
Identifies countries contributing the highest number of titles to Netflix.

Top contributors include:
United States
India
United Kingdom
Canada
France

6. Content Rating Distribution
Analyzes ratings such as:
TV-MA
TV-14
TV-PG
PG-13
R
for both Movies and TV Shows.

7. Top Directors
Identifies directors with the largest number of Netflix productions.

8. Monthly Content Trends
Examines seasonal publishing trends by analyzing monthly additions to Netflix.

9. Country vs Rating Heatmap
Explores the relationship between content ratings and major producing countries through a heatmap.


📈 Visualizations

The project includes several interactive visualizations created using Plotly.
These include:

Pie Charts
Bar Charts
Horizontal Bar Charts
Line Charts
Histograms
Stacked Bar Charts
Heatmaps
Each visualization includes proper titles, axis labels, legends, and interpretations.


🔍 Key Insights

Some important observations obtained from the analysis include:

Netflix hosts significantly more Movies than TV Shows.
The number of titles added to Netflix increased rapidly between 2016 and 2020.
Most movies have a runtime close to 100 minutes.
One-season TV Shows dominate Netflix's television catalog.
The United States contributes the largest amount of Netflix content, followed by India.
TV-MA is the most common content rating on the platform.
A small number of directors account for a significant portion of available titles.
Netflix consistently releases content throughout the year with relatively balanced monthly additions.


💡 Business Recommendations

Based on the findings, the following recommendations can be made:

Continue investing in regions with growing content production such as India and South Korea.
Expand multi-season television content to improve long-term user engagement.
Increase family-friendly programming to reach wider audiences.
Strengthen partnerships with highly productive directors and creators.
Continue maintaining a balanced content release schedule throughout the year.
Invest further in international productions to diversify Netflix's catalog.


▶️ How to Run

Clone this repository.
Install the required Python libraries.
Open the notebook using Google Colab or Jupyter Notebook.
Ensure the dataset file is located in the project directory.
Execute all notebook cells sequentially.


📚 Python Libraries
pandas
numpy
matplotlib
seaborn
plotly

Install them using:

pip install pandas numpy matplotlib seaborn plotly



📌 Future Improvements

Potential enhancements include:

Sentiment analysis of content descriptions.
Genre recommendation system.
Interactive dashboard using Streamlit or Dash.
Machine Learning-based popularity prediction.
Time-series forecasting for future content additions.
Geographic visualization of global content distribution.


🎓 Internship Information

Internship Program: AI & Machine Learning Internship
Organization: Pluto Academy
Project: Project 1 – Exploratory Data Analysis (EDA)


👨‍💻 Author

Name: Akshar Patel
Program: B.Tech Information Technology (Honors in Cybersecurity)


📜 License

This project is developed solely for educational and internship purposes as part of the Pluto Academy AI & Machine Learning Internship.


⭐ Acknowledgements

Special thanks to:
Pluto Academy for providing the internship project.
Kaggle for making the Netflix dataset publicly available.
The Python open-source community for providing excellent data analysis libraries.
