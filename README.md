# Exploratory Airbnb Data Cleaning and Analysis

## Goal of the Project
The purpose of this project is to conduct a comprehensive data cleaning and exploratory analysis using a random Airbnb dataset from Kaggle. Initially, the focus was on data cleaning, with no specific analysis objective in mind. This project showcases the iterative and often non-linear nature of data analytics, where the initial data preparation lays the groundwork for deeper analytical exploration. Typically, the common approach in data analytics is to define the problems and questions first, then find relevant datasets to answer them. However, for this initial personal data analytics project, I intentionally chose a challenging dataset with significant issues. The goal was to transform the data completely. Through this process, I gained a deeper understanding of the dataset's dimensions and formulated future actions. Ultimately, I conducted a thorough analysis and created a comprehensive dashboard.

## Powerbi Dashboard
The Pricing insight Dashboard for Airbnb Listings and Pricing Analysis.
![2024-07-26-09-07-24](https://github.com/user-attachments/assets/ab5ec900-5fbd-4b71-8503-449365062d8e)



## Jupyter Notebooks
In case of failure of loading Jupyter Notebooks on GitHub, the following notebooks can be found in nbviewer. Click on the respective hyperlinks to view:

- [Data Cleaning]([link_to_nbviewer_data_cleaning](https://nbviewer.org/github/Rahulloriya/Airbnb-Data-analytics-project-/blob/main/3.Airbnb_Cleaned_2))
- [Exploratory Data Analysis](link_to_nbviewer_data_exploration_analysis)

## Analysis Approach
### 1. Data Quality Assessment and Data Cleaning
The first step towards generating useful insights from the data was the data preparation, quality assessment, and data cleaning step. After the cleaning process, exploratory data analysis on the dataset and identification of customer purchasing behaviors to generate insights can be performed.

In the data cleaning step, the following data quality issues were observed and the necessary process to mitigate the issues was followed:

- **airbnb Datacleaning**:
  - Dropped irrelevant columns.
  - Handled missing values appropriately.
  - Standardized data and removed inconsistencies.
  - Created new features from existing columns.
  - Seperate and categorized various columns.

### 2. Exploratory Data Analysis
After the data cleaning process, exploratory analysis on the dataset was performed and the following insights were obtained:

  - Analyzed the distribution of prices and ratings for Airbnb listings.
  - Understood relationship between various features with price
  - endoded text features into 1 & 0 to find correlation between them and price.
  - Analyzed the distribution of listings across different price segments.
  - analyzed top anemities provided by each property segment. 
  - Identified the top destinations generating the highest revenue.

### 3. Visualization and Dashboard Creation
A comprehensive dashboard was created to visualize the key findings and insights from the analysis. The dashboard includes:

- **Average Price and Ratings**: Displays the overall average price and rating of listings.
- **Guest Engagement**: Shows the engagement across different property segments.
- **Market Share**: Illustrates the balance between affordable and luxury listings.
- **Top Revenue Generators**: Highlights the top destinations generating the highest revenue.

![Airbnb Dashboard](link_to_screenshot)

## Datasets Used
The dataset used includes:

- **airbnb.csv**: This dataset included detailed information about Airbnb listings such as prices, ratings, property types, and locations.

## Tools and Technologies Used
- **Python**: For Data Quality Assessment, Data Cleaning, and Exploratory Data Analysis using libraries like pandas, matplotlib, and seaborn.
- **Tableau**: For creating the Sales Dashboard to visualize customer segmentation and analysis.
