# IMDB_Dataset_analysis_Tableau


# 🎬 IMDB Dataset Analysis Project

Welcome to the **IMDB Dataset Analysis Project**! This project delves into the IMDB Movies Dataset, focusing on data cleaning, visualization, and exploratory data analysis using Tableau and Python. Below, you will find comprehensive documentation on the structure and design of our project.

---

## 📁 Table of Contents
- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Variables in the Dataset](#variables-in-the-dataset)
- [Design Process](#design-process)
- [Dashboard Rationale](#dashboard-rationale)
- [Observations and Insights](#observations-and-insights)
- [About Us](#about-us)

---

## 📝 Introduction
The IMDB Dataset Analysis Project explores the top 1000 movies and TV shows listed on IMDB. Through this analysis, we aim to uncover trends and insights related to movies' ratings, box office performances, genres, and other key variables.

## 📊 Dataset Overview
**Dataset Name**: IMDB Movies Dataset  
**Description**: This dataset consists of information about the top 1000 movies and TV shows, containing 16 attributes with 1000 rows each.  
**Data Source**: [IMDB Dataset]([https://www.imdb.com](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows))

### Dataset Variables
- **Poster_Link**: URL of the movie poster.
- **Series_Title**: Title of the movie.
- **Released_Year**: Year when the movie was released.
- **Certificate**: Certification earned by the movie.
- **Runtime**: Duration of the movie.
- **Genre**: Category of the movie.
- **IMDB_Rating**: Movie rating on IMDB.
- **Overview**: Short summary of the movie.
- **Meta_score**: Metascore assigned to the movie.
- **Director**: Director's name.
- **Star1, Star2, Star3, Star4**: Names of the lead actors.
- **No_of_votes**: Total number of votes received.
- **Gross**: Box office earnings.

## 🧩 Design Process
The design process is iterative and involves visualizing the data to find the most effective representation of each analysis. We used a variety of charts and dashboards in Tableau to display our findings:

1. **Income vs. Genre Analysis**  
   - Initial Visualization: Histogram  
   - Final Visualization: Line Chart

2. **Distribution of Movies by Release Year**  
   - Initial Visualization: Simple Text  
   - Final Visualization: Pie Chart

3. **Certificates Comparison**  
   - Initial Visualization: Side-by-side Bar Chart  
   - Final Visualization: Stacked Bar Chart

![Design Example 1](path/to/image1.png)  
*Figure 1: Income vs. Genre Analysis*

![Design Example 2](path/to/image2.png)  
*Figure 2: Movie Distribution Analysis*

## 🎨 Dashboard Rationale
### 1. IMDB Release Year Analysis
We grouped release years into intervals of 20 years and compared attributes such as gross income, genre, and number of movies released. The color scheme follows a color-blind friendly palette, ensuring accessibility.

### 2. IMDB Directors Analysis
We analyzed directors' performances in terms of IMDB ratings, box office collections, and movie certifications. Using word clouds and stacked bar charts, we highlighted key patterns and correlations.

### 3. IMDB Actor Analysis
Director-actor pairs were analyzed to identify which pairs produced the most movies together and achieved the highest box office earnings.

### 4. IMDB Rating Analysis
We explored how IMDB ratings correlate with runtime, certification, and the number of votes. The results help determine factors contributing to higher ratings.

### 5. IMDB Metascore Analysis
Metascores were compared with gross earnings, votes, and certificates to uncover patterns and influences.

### 6. IMDB Number of Votes Analysis
We examined how the length of movie overviews relates to the number of votes a movie receives. Python was used for word count analysis.

## 🔍 Observations and Insights
### Dashboard 1 - IMDB Release Year Analysis
- **Highest Average Gross Income**: The 2000-2019 range, with $78,466,340 average.
- **Top Director**: James Cameron (1980-2019) with $503,719,934 average income.
- **Most Popular Genre**: “Family, Sci-Fi” in 1980-1999 with $435,110,554 earnings.

### Dashboard 2 - IMDB Directors Analysis
- **Top Director by Box Office**: Christopher Nolan with an average IMDB rating of 8.45.
- **Most Successful Movie Series**: Peter Jackson’s *The Lord of the Rings* trilogy.

### Dashboard 3 - IMDB Actor Analysis
- **Top Actor**: Robert Downey Jr with 7 movies and an average gross income of $447,010,463.

### Additional Observations
- IMDB ratings have a correlation with runtime and the number of votes.
- There is a pattern in metascores relating to directors and genres.
- The length of movie overviews impacts the number of votes received.

---

Feel free to use or modify this template for your project. Make sure to update image paths and other placeholders as needed.
