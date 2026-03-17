# netflix-data-analysis
The purpose of this project is to show my work with SQL and Python in cleaning messy data and organizing it in a more useful format.

Netflix Data Analysis

This project demonstrates data cleaning, normalization, and analysis of a real-world dataset using Python and SQL.

Objective

Analyze Netflix content to identify trends in content type, release patterns, and genre distribution.

Dataset

Netflix titles dataset (public dataset)

Tools Used
	•	Python (pandas)
	•	SQL (SQLite)
	•	Data cleaning and transformation techniques

Key Steps
	•	Cleaned missing and inconsistent data
	•	Converted date fields and extracted year-based features
	•	Normalized data into multiple tables (titles, genres, title_genres)
	•	Created structured database using SQLite

Key Insights
	•	Movies make up the majority of Netflix content
	•	Content additions increased significantly in recent years
	•	Drama and Comedy are among the most common genres

Project Structure
	•	titles table: core metadata
	•	movies / tv_shows: separated duration formats
	•	genres: unique genre list
	•	title_genres: many-to-many relationship

Files
	•	01_data_cleaning.ipynb (code to clean data)
	•	*.csv (cleaned datasets)

Future Improvements
	•	Add visualization dashboards
	•	Expand analysis to regional trends
	•	Explore genre evolution over time
