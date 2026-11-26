# Netflix Content Analysis

### Internship Project – CognoRise InfoTech

## Project Overview

This project focuses on analysing Netflix Movies and TV Shows data to understand the distribution of content, popular genres, country-wise contributions, release trends and content duration.

The analysis is performed using Python libraries for data cleaning, exploratory data analysis, statistical testing and visualization.

## Objectives

- Analyse the distribution of Movies and TV Shows.
- Identify countries contributing the most titles.
- Explore the most common genres on Netflix.
- Examine content release trends over time.
- Analyse movie durations and TV Show seasons.
- Perform statistical tests to identify relationships and differences in the dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- VS Code

## Dataset

**Dataset:** Netflix Movies and TV Shows

**File name:** `netflix_titles.csv`

The dataset contains information about Netflix titles, including:
- Show ID
- Title
- Director
- Cast
- Country
- Release Year
- Rating
- Duration
- Genre
- Date Added

## Project Workflow

### 1. Data Loading and Inspection
Loaded the dataset using Pandas and examined its structure, columns, missing values and duplicate records.

### 2. Data Cleaning
- Removed duplicate records.
- Handled missing values.
- Corrected misplaced duration values.
- Converted date columns.
- Extracted movie duration and TV Show seasons.
- Prepared country, genre and director data for analysis.

### 3. Exploratory Data Analysis (EDA)

The analysis includes:

- Movies vs TV Shows distribution.
- Release year trends.
- Netflix content additions by year and month.
- Top 10 countries.
- Content ratings and audience categories.
- Top 12 genres.
- Director analysis.
- Movie duration and TV Show seasons.

### 4. Statistical Analysis

Three statistical methods were applied:

- Chi-Square Test
- Spearman Rank Correlation
- Mann-Whitney U Test

### 5. Dashboard

Created a dashboard containing four visualizations:
- Movies vs TV Shows.
- Titles by release year.
- Top 10 countries.
- Top 12 genres.

### Netflix Content Analysis Dashboard

![Netflix Dashboard](outputs/00_dashboard.png)

## Key Findings

- Movies represent 69.6% of the catalogue, while TV Shows account for 30.4%.
- The United States contributes the highest number of titles, followed by India and the United Kingdom.
- International Movies are the most frequently listed genre, followed by Dramas and Comedies.
- The average movie duration is 99.6 minutes.
- Most TV Shows have one season, with an average of 1.8 seasons.

## Project Limitations

- The dataset represents a snapshot of Netflix's content catalogue.
- Some records contain missing information.
- Viewer ratings and streaming statistics are not available.
- Titles associated with multiple countries or genres may appear in multiple category counts.

## How to Run the Project

1. Clone or download this repository.
2. Place `netflix_titles.csv` in the project folder.
3. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scipy jupyter
```

4. Open the notebook in VS Code or Jupyter Notebook.
5. Run all cells to perform the analysis.

## Author

**Muhsina Rinsha T P**

B.Tech – Artificial Intelligence and Data Science

Internship: CognoRise InfoTech
