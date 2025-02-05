Netflix Dataset Exploratory Data Analysis (EDA) Project

📌 Overview: Netflix is one of the largest streaming platforms worldwide, offering a vast collection of movies and TV shows across different genres and countries. This project performs Exploratory Data Analysis (EDA) on the Netflix dataset to extract insights about content distribution, trends, and audience preferences.

By analyzing this dataset, we aim to answer questions such as:

What type of content (Movies vs. TV Shows) dominates Netflix? Which year had the most content releases? What are the most common genres on Netflix? Which countries contribute the most content? Who are the top directors producing Netflix content? This project is an excellent way to understand real-world data, clean messy datasets, and apply data visualization techniques.

📂 Dataset Information: The dataset used in this project is sourced from Kaggle and contains information about Netflix content, including:

show_id – Unique ID for each movie/TV show.

type – Whether the content is a Movie or TV Show.

title – Name of the content.

director – Director of the movie/TV show.

cast – Main actors involved in the content.

country – Country where the content was produced.

date_added – Date when the content was added to Netflix.

release_year – Year the content was released.

rating – Content rating (e.g., TV-MA, PG-13, etc.).

duration – Duration of movies (in minutes) and TV shows (number of seasons).

listed_in – Categories or genres the content belongs to.

description – Brief summary of the content.

🎯 Objectives of the Project Explore the dataset – Understand its structure and contents. Data Cleaning & Preprocessing – Handle missing values and duplicates. Feature Selection – Identify key attributes influencing Netflix content. Data Visualization – Use graphs and charts to analyze content trends. Trend Analysis – Identify the most popular genres, top contributing countries, and key release years. Insights & Recommendations – Provide meaningful observations based on the analysis.

🛠️ Tools & Libraries Used The project is implemented using Python and the following libraries:

pandas – For data manipulation and preprocessing. numpy – For numerical operations. matplotlib – For data visualization. seaborn – For advanced visualizations.

📊 Exploratory Data Analysis (EDA) Steps

1️⃣ Data Cleaning & Preprocessing Checked for missing values and handled them appropriately. Filled missing values in director, cast, and country with "Not Specified". Removed duplicate entries to ensure data integrity.

2️⃣ Understanding Content Types (Movies vs. TV Shows) Counted the number of Movies vs. TV Shows using a bar chart. Observation: Netflix has significantly more Movies than TV Shows.

3️⃣ Release Year Analysis Used a histogram to show content releases over the years. Observation: Most content was released between 2000-2020, with the highest number of releases in 2018.

4️⃣ Country-wise Content Contribution Extracted the top 10 countries producing Netflix content. Used a bar chart to visualize the top contributing countries. Observation: The United States has the highest number of Netflix titles, followed by India.

5️⃣ Genre Analysis Extracted unique genres and counted their occurrences. Used a horizontal bar chart to display the top 10 most popular genres. Observation: The most popular genres on Netflix include Documentaries, Stand-up Comedy, Dramas, and International Movies.

6️⃣ Director & Actor Analysis Identified the top 10 directors with the highest number of Netflix content. Filtered the dataset to find all movies featuring actor Mohanlal.

7️⃣ Rating Analysis Analyzed the number of movies rated "TV-14" in India. Identified the country with the highest number of TV Shows.

📈 Key Insights & Findings Movies dominate Netflix – There are significantly more movies than TV shows on the platform. Content production peaked in 2018 – The highest number of new titles were added that year. The United States leads in content production, followed by India. Drama & International Movies are the most popular genres. Most Netflix content falls under TV-14 and TV-MA ratings.

🔍 Future Improvements Perform sentiment analysis on movie descriptions. Build a recommendation system using machine learning. Analyze user reviews and ratings to find popular content.
