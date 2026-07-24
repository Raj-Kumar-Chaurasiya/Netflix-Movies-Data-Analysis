🎬 Netflix Movies Data Analysis
📌 Project Overview

This project focuses on analyzing a Netflix movie dataset using Python. The goal was to clean the data, perform exploratory data analysis (EDA), and visualize different patterns related to movie genres, popularity, ratings, and release years. Through this project, I practiced data cleaning, feature engineering, and creating meaningful visualizations to answer real-world business questions.

📊 Dataset

The dataset contains information about 9,827 Netflix movies, including:

Movie Title
Release Date
Popularity
Vote Count
Vote Average
Genre
Overview
Original Language
Poster URL
🛠️ Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
📋 Project Workflow
1. Data Loading
Imported the dataset into a Pandas DataFrame.
Explored the dataset structure using head(), info(), and describe().
2. Data Cleaning
Checked for missing values and duplicate records.
Converted the Release_Date column into datetime format and extracted the release year.
Removed unnecessary columns such as Overview, Original Language, and Poster URL.
Categorized movie ratings into four groups:
Not Popular
Below Average
Average
Popular
Split multiple genres into separate rows for better analysis.
3. Exploratory Data Analysis (EDA)

The project answers the following questions:

Which genre appears most frequently?
Which rating category has the highest number of movies?
Which movie has the highest popularity?
Which movie has the lowest popularity?
Which year had the highest number of movie releases?
4. Data Visualization

Created visualizations using Matplotlib and Seaborn to better understand:

Genre distribution
Vote Average distribution
Movie popularity
Release year trends
📈 Key Findings
Drama is the most common genre in the dataset.
Most movies fall into the Popular rating category.
Spider-Man: No Way Home has the highest popularity score.
The United States vs. Billie Holiday and Threads have the lowest popularity scores in the dataset.
2020 recorded the highest number of movie releases.
📚 Skills Demonstrated
Data Cleaning
Exploratory Data Analysis (EDA)
Data Visualization
Feature Engineering
Data Transformation
Python Programming
Pandas
NumPy
Matplotlib
Seaborn
🎯 Conclusion

This project helped me strengthen my understanding of data analysis using Python. I learned how to clean and prepare data, transform features for better analysis, and create visualizations that highlight useful insights. It also improved my ability to interpret datasets and present findings in a clear and meaningful way.

📷 Project Output

The notebook includes charts and visualizations for:

Genre Distribution
Vote Average Distribution
Highest and Lowest Popular Movies
Movie Release Trend by Year
🚀 Future Improvements
Build an interactive dashboard using Power BI or Tableau.
Add sentiment analysis using movie overviews.
Compare Netflix trends with IMDb or TMDb datasets.
Develop a recommendation system based on genres and ratings.
