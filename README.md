# TITLE: NETFLIX-DATA-ANALYSIS
![Image Alt](https://github.com/PUJITHA12-S/NETFLIX-DATA-ANALYSIS/blob/main/download.png?raw=true)

# Table Content
* About Netflix
* Problem Statement
* Objective
* Dataset Overview
* Data Cleaning
* Basic EDA And Non-Graph Analysis
* Graph analysis
* Overall Insight & Recommendation
* Conclusion

# 🔍 About Netflix
Netflix is an American subscription video on-demand over-the-top streaming service. The service primarily distributes original and acquired films and television shows from various genres, and it is available internationally in multiple languages.

Launched in 2007, nearly a decade after Netflix, Inc. began its pioneering DVD-by-mail movie rental service, Netflix is the most-subscribed video on demand streaming media service, with 301.6 million paid memberships in more than 190 countries as of 2025. By 2022, "Netflix Original" productions accounted for half of its library in the United States and the namesake company had ventured into other categories, such as video game publishing of mobile games through its flagship service. As of 2025, Netflix is the 18th most-visited website in the world, with 21.18% of its traffic coming from the United States, followed by the United Kingdom at 6.01%, Canada at 4.94%, and Brazil at 4.24%

# 🧩 Problem Statement
Netflix aims to understand audience preferences and content performance to guide content production, optimize recommendations, and expand globally. By analyzing its library, we can identify trends in genres, directors, countries, and user interests.

# 🎯 Objective
The objective of this project is to perform exploratory data analysis (EDA) on Netflix's content to uncover insights about content types, release patterns, country-wise distribution, and user preferences. This helps generate data-driven recommendations for Netflix’s strategic decisions.

# 📂 Dataset Overview

The dataset contains information on all movies and TV shows available on Netflix, including:

* show_id: Unique ID for each title
* type: Movie or TV Show
* title: Name of the title
* director: Director name
* cast: List of main cast members
* country: Country of origin
* date_added: Date when content was added to Netflix
* release_year: Year of release
* rating: Audience rating
* duration: Duration of the content
* listed_in: Genre(s)

# Data Loading
Data cleaning in Python is the process of preparing raw data for analysis by fixing errors and inconsistencies. It includes handling missing values, correcting data types, and removing duplicates. This step ensures the dataset is accurate, complete, and reliable. Libraries like Pandas and
NumPy are widely used for these tasks.

# Non Graphical Analysis 
* 1.What type of content is available in different countries?
* 2.How has the number of movies released per year changed over the last 20-30 years? 
* 3.Comparison of tv shows vs. movies. 
* 4.What is the best time to launch a TV show? 
* 5.Analysis of actors/directors of different types of shows/movies. 
* 6.Does Netflix has more focus on TV Shows than movies in recent years 
* 7.Understanding what content is available in different countries

# Overall Insights & Recommendation
🔍 Insight 1: Dominance of Movie Content on Netflix
Movies account for 69.3% of total content, while TV shows account for 30.4%.

2018 had the highest number of releases overall.

📌 Recommendation:
Continue prioritizing movie content, especially around high-performing years like 2018. However, also consider increasing investment in engaging TV series, which can drive longer user retention.

🔍 Insight 2: Top Performing Director – Rajiv Chilaka
Rajiv Chilaka has the highest number of directed content (19 titles) on Netflix.

Other notable directors include Raúl Campos and Marcus Raboy.

📌 Recommendation:
Build ongoing collaborations with top-performing directors like Rajiv Chilaka. Also, explore marketing content by globally recognized directors such as Steven Spielberg to expand international reach.

🔍 Insight 3: Genre Popularity
International Movies and Dramas are the top genres, while Romantic Movies have relatively lower representation.

📌 Recommendation:
Focus production efforts on International Movies and Dramas. They have a wider global appeal and can help Netflix maintain competitive advantage across regions.

🔍 Insight 4: Country-wise Content Distribution
The United States contributes the most content, followed by India and the United Kingdom.

Different countries show preferences for different genres (e.g., Anime in Japan, Family content in the U.S., Dramas in India).

📌 Recommendation:
Adopt a region-specific content strategy. Tailor content offerings based on local preferences (e.g., Anime for Japan, Comedies/Dramas for India) to improve engagement and viewer loyalty.

🔍 Insight 5: Optimal Time for Releasing TV Shows
July is the best month for launching TV shows.

Friday is the most popular day for releasing both Movies and TV shows.

📌 Recommendation:
Time the launch of major content, especially TV shows, in July and on Fridays to capitalize on viewer availability and holiday seasons for maximum impact.



