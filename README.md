# Exploratory Airbnb Data Cleaning and Analysis

## Goal of the Project
The purpose of this project is to conduct a comprehensive data cleaning and exploratory analysis using a random Airbnb dataset from Kaggle. Initially, the focus was on data cleaning, with no specific analysis objective in mind. This project showcases the iterative and often non-linear nature of data analytics, where the initial data preparation lays the groundwork for deeper analytical exploration. Typically, the common approach in data analytics is to define the problems and questions first, then find relevant datasets to answer them. However, for this initial personal data analytics project, I intentionally chose a challenging dataset with significant issues. The goal was to transform the data completely. Through this process, I gained a deeper understanding of the dataset's dimensions and formulated future actions. Ultimately, I conducted a thorough analysis and created a comprehensive dashboard.

## Powerbi Dashboard
The Pricing insight Dashboard for Airbnb Listings and Pricing Analysis.
![2024-07-26-09-07-24](https://github.com/user-attachments/assets/ab5ec900-5fbd-4b71-8503-449365062d8e)

## Jupyter Notebooks
In case of failure of loading Jupyter Notebooks on GitHub, the following notebooks can be found in nbviewer. Click on the respective hyperlinks to view:

- Data Cleaning: [link to nbviewer data cleaning](https://nbviewer.org/github/Rahulloriya/Airbnb-Data-analytics-project-/blob/main/3.Airbnb_Cleaned_2.ipynb)
- Exploratory Data Analysis: [link to nbviewer data exploration analysis](https://nbviewer.org/github/Rahulloriya/Airbnb-Data-analytics-project-/blob/main/4.Airbnb%20Exploration%20and%20analysis%20.ipynb)

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
   ![download (1)](https://github.com/user-attachments/assets/315d90a7-a2ae-4607-ab7c-b5758675ca54)
  - Understood relationship between various features with price
   ![download](https://github.com/user-attachments/assets/b9207fdf-52e8-481b-b492-935963c54183)
  - endoded text features into 1 & 0 to find correlation between them and price.
  - Analyzed the distribution of listings across different price segments.
   ![download (2)](https://github.com/user-attachments/assets/7264ac84-ed4d-403b-ba30-f53ce69727ab)
  - analyzed top anemities provided by each property segment.
   ![download (3)](https://github.com/user-attachments/assets/a78754fb-e28c-4288-b591-e2a939e2bf48)
  - Identified the top destinations generating the highest revenue.
   ![download (4)](https://github.com/user-attachments/assets/664c0635-01c5-4cbc-9794-2b381726bd10)
  -Performed hypothesis testing to identify significant relationships between variables and draw meaningful inferences.

### 3. Visualization and Dashboard Creation
A comprehensive dashboard was created to visualize the key findings and insights from the analysis. The dashboard includes:

- **Average Price and Ratings**: Displays the overall average price and rating of listings.
- **Guest Engagement**: Shows the engagement across different property segments.
- **Market Share**: Illustrates the balance between affordable and luxury listings.
- **Top Revenue Generators**: Highlights the top destinations generating the highest revenue.

## Datasets Used
- **airbnb raw.csv**: This dataset included detailed information about Airbnb listings such as prices, ratings, property types, and locations.
- [link to actual dataset from kaggle](https://www.kaggle.com/datasets/ashishjangra27/airbnb-dataset)

## Tools and Technologies Used
- **Python**: For Data Quality Assessment, Data Cleaning, and Exploratory Data Analysis using libraries like pandas, matplotlib, and seaborn.
- **Excel**: For minor analysis and broad view to make decisions. 
- **Powerbi**: For creating the Pricing insight Dashboard to visualize analysis.
