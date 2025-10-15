<h2>Netflix Dataset Analysis Project</h2>
<h3>Overview</h3>

- This project focuses on exploring and analyzing the Netflix Dataset to uncover insights about the platform’s content — including movies, TV shows, genres, countries, and release trends.

- The analysis process involves data cleaning, data management in SQL, and visual storytelling in Power BI.

<h3>Step 1: Data Cleaning (Excel)</h3>

- The raw dataset was first cleaned and organized in Microsoft Excel:

- Removed missing and duplicate values

- Standardized date formats and categorical data

- Fixed inconsistent entries (e.g., genre names, country names)

- Ensured column names were clear and consistent for database import

- Replaced empty values with NULL

<h3>Step 2: Database Creation (SQL)</h3>

- After cleaning, the dataset was imported into MySQL for structured storage and analysis.

- Created tables for the Netflix data (e.g., countries_released, netflix_cast, netflix_directors, netflix_titles etc)

- Used SQL queries for:

- Filtering and sorting data

- Performing aggregations and joins

- Running analytical queries to identify patterns and trends 

<h3>Step 3: Visualization (Power BI)</h3>

- The SQL tables were then connected to Power BI for interactive visualizations.
- Key visual elements include:

- Shows by Rating, Shows Added by Date

- Top 10 Genre

- Top countries producing Netflix content

- Movie and Tv Show Filter with Drop down

- Trends in release years and ratings

- The Power BI dashboard provides a clear, visual summary of Netflix’s catalog and helps identify business insights.

<h3>Tools & Technologies</h3>

- Tool	Purpose
- Excel	Data cleaning and preprocessing
- MySQL	Data storage and management
- Power BI	Data visualization and dashboarding

<h3>Key Insights</h3>

- Netflix has been increasing its production of original content significantly after 2015

- The majority of content on Netflix is movies, though TV shows are growing rapidly

- The United States and India are the top countries producing Netflix content

- Stand Up Comedy remain the most popular genres

<h3>Future Improvements</h3>

- Automate data import from Excel to SQL using Python scripts

- Add DAX measures in Power BI for more advanced metrics

- Build a web dashboard version for online access
