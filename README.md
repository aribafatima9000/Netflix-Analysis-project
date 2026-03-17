Netflix Content Analysis & Data Cleaning
Project Overview
This project focuses on the comprehensive cleaning and Exploratory Data Analysis (EDA) of the Netflix Movies and TV Shows dataset. The goal is to transform raw data into a structured format to uncover insights regarding content distribution, regional trends, and release patterns.

Key Features
The following data preprocessing and analysis steps were performed:

Data Cleaning: Systematic removal of non-essential columns such as show_id, description, and listed_in to streamline the analysis.

Missing Value Imputation: Addressed null values in critical fields like director, cast, and country by replacing them with "Unknown" to maintain data integrity.

Type Casting: Converted the date_added column to a proper datetime format and ensured release_year is handled as numerical data.

Outlier Analysis: Utilized statistical visualizations (Box Plots) to identify and analyze anomalies in the release timelines.

Categorical Analysis: Analyzed the distribution between Movies and TV Shows to understand Netflix’s content strategy.

Technologies Used
Python: Primary programming language.

Pandas: For data manipulation, filtering, and cleaning.

Matplotlib / Seaborn: For generating statistical visualizations and identifying data trends.

Jupyter Notebook: For interactive development and documentation.

Dataset Description
The dataset consists of approximately 8,807 records, including:

Content Type: Identification of Movies vs. TV Shows.

Cast & Crew: Information regarding directors and leading actors.

Release Metrics: Data on when the content was released and when it was added to the platform.

Ratings: Audience maturity ratings for the content.
