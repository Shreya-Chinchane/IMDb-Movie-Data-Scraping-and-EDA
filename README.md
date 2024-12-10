# IMDb-Movie-Data-Scraping-and-EDA


This project demonstrates how to scrape IMDb movie data using Selenium and perform exploratory data analysis (EDA) to derive insights from the data. The goal is to collect movie details such as title, release year, rating, duration, number of votes, and content rating, and then analyze the data for patterns, trends, and statistics.


## 🚀 Project Workflow

1. **Data Scraping with Selenium**  
   - Used Selenium to automate the process of navigating IMDb and scraping movie data from the website.
   - Extracted essential details including title, release year, rating, duration, content rating, and number of votes.

2. **Data Cleaning and Preprocessing**  
   - Cleaned the data by removing unwanted characters, converting data types, and handling missing values.

3. **Exploratory Data Analysis (EDA)**  
   - Performed EDA to visualize and understand the relationships within the dataset.
   - Analyzed patterns in movie ratings, release years, and vote counts, and visualized the data through charts and graphs.

4. **Saved Data**  
   - Saved the cleaned and preprocessed data into a CSV file for further analysis or usage.


## 📋 Requirements


To run this project locally, make sure you have the following dependencies installed:

- Python 3.x
- Selenium
- Pandas
- Matplotlib
- Jupyter Notebook (optional for EDA)
- WebDriver (ChromeDriver/GeckoDriver depending on your browser)


## 📊 Dataset Information:


This dataset contains detailed IMDb movie information that has been preprocessed and cleaned for analysis.

Columns:

  - Movie Title: The name of the movie.
  - Release Year: The year the movie was released.
  - Duration: The total runtime of the movie in hours and minutes.
  - Rating: IMDb rating of the movie (out of 10).
  - Content Rating: Rating indicating the appropriate audience for the movie (e.g., PG-13, R).
  - Number of Votes: Total number of votes the movie received on IMDb.
  - Duration (in minutes): Converted duration in minutes.
  - Number of Votes (Numeric): Converted number of votes in numeric form for analysis (e.g., 1M = 1,000,000).


## 📈 Visualizations and Insights


The project includes various visualizations, including:

  - Histograms to show distribution of ratings
  - Bar charts comparing ratings and release years
  - Scatter plots to explore the relationship between votes and ratings
