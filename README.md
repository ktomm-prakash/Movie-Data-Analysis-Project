# Movie-Data-Analysis-Project
This project explores and analyzes a movie dataset to uncover patterns in popularity, ratings, release years, and genres. Using Python and visualization libraries, we derive insights that can support decision-making in content recommendations, marketing, or understanding viewer trends.

## 📌 Project Objectives

- Clean and preprocess movie dataset
- Analyze vote counts, averages, and popularity
- Explore genre-wise and year-wise trends
- Visualize data using intuitive charts

## 📂 Dataset

The dataset contains the following key columns:
- `Title`: Name of the movie
- `Popularity`: Popularity score of the movie
- `Vote_Count`: Number of user votes
- `Vote_Average`: Average user rating
- `Genre`: Movie genre(s)
- `Release_Date`: Original release date

## ⚙️ Key Tasks Performed

- Removed duplicates and handled missing values
- Converted data types (e.g., date parsing, numeric casting)
- Created a `Release_Year` column from `Release_Date`
- Categorized vote count and popularity using quantiles
- Grouped and visualized vote averages vs. popularity
- Generated genre-wise boxplots of vote averages with unique colors

## 📊 Visualizations

Some of the visualizations included in the notebook:
- **Bar Plot**: Average popularity by vote average
- **Box Plot**: Vote average distribution by genre with unique colors
- **Countplot / Lineplot / Distribution Plot** (optional): For extended analysis
