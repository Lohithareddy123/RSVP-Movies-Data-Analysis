IMDB Data Analysis Using SQL

This project is a comprehensive SQL-based analysis of the IMDB movie dataset. It covers data inspection, cleaning, aggregation, ranking, and insight generation through advanced SQL queries across multiple related tables.

🧠 SQL Concepts Used:

Joins (INNER, LEFT)

Aggregate functions (COUNT, AVG, SUM)

Window functions (RANK, ROW_NUMBER, LEAD)

Conditional logic (CASE)

Subqueries and CTEs (WITH)

String functions (LIKE, LOWER, POSITION)

Date manipulation (DATEDIFF, MONTH, EXTRACT)

✅ Step-by-Step Summary

🔹 Segment 1: Data Overview & Movie Table Analysis
Viewed contents of all key tables: movie, ratings, genre, names, role_mapping, director_mapping.

Checked row counts for all tables to understand dataset scale.

Identified null values in movie table (e.g., production company, gross income).

Analyzed yearly & monthly trends in movie releases.

Filtered country-specific releases (India/USA, 2019).

Extracted unique genres and ranked them by frequency.

Calculated average duration by genre.

Ranked genres by movie count and analyzed genre distribution (e.g., ‘Drama’ highest).

Used window functions to find rank of genres and single-genre movies.

🔹 Segment 2: Ratings Table Insights
Summarized min/max values of average, median rating, and vote counts.

Identified top 10 movies by average rating.

Grouped ratings by median rating for distribution analysis.

Ranked production houses by number of hit movies (avg rating > 8).

Analyzed genres in March 2017 US movies with > 1000 votes.

Filtered movies starting with “The” and rated > 8.

Counted movies with median rating = 8 released between April 2018–19.

Compared vote averages between German and Italian movies.

🔹 Segment 3: Names Table & Role Mapping
Identified null values in names table fields.

Ranked top directors in top-rated genres (>8 avg rating).

Found top 2 actors with median rating ≥ 8.

Ranked top 3 production houses by total votes.

Ranked Indian actors with at least 5 movies by weighted avg rating.

Ranked Hindi actresses with at least 3 Indian movies by weighted avg rating.

Categorized thriller movies by average rating: Superhit, Hit, One-time-watch, Flop.

🔹 Segment 4: Advanced Business Queries
Calculated running total & moving average of avg movie duration by genre.

Ranked top 5 grossing movies per year per top 3 genres.

Found top 2 production houses for multilingual hits (median rating ≥ 8).

Ranked top 3 actresses in ‘Drama’ genre by average rating.

Built a detailed director summary:

Number of movies

Inter-movie duration (in days)

Avg rating, total votes, min/max rating

Total duration of all their movies

