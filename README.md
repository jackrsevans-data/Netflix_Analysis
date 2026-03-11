## Netflix Data Analysis Project

This project performs an exploratory data analysis (EDA) on a Netflix dataset to uncover insights into its content library. The analysis focuses on understanding content distribution, popular genres, and trends over time. Before beginning this analysis, I theorised that the movies I was watching on Netflix seemed to be getting longer, with runtimes typically around 2 hours, however I always remember films in my youth being around the 90-minute mark. I was also aware that the audience's attention span is decreasing, with many people viewing two devices at once. This started me down my path with 3 questions in mind;

1) What is the most common content on Netflix?
   What is Netflix adding to its library to keep consumers subscribed?
2) What is the distribution of movies vs. TV shows over the past 20 years?
   Many people I've spoken to rarely watch films but seem to be binge-watching multiple series a month. Does Netflix's data show this with their recent content releases?
3) How has movie duration changed?
   As previously mentioned, I believed runtimes were increasing. I wanted to investigate how the average movie length has changed to see if there is a conclusive trend.

## Data Source

The dataset used in this analysis is named `NetFlix.csv`, which contains information about movies and TV shows available on Netflix up to the start of 2022. Due to Covid-19 and the consequential shutdown of the media industry during this time, there was a sharp decrease in content for this period.

## Technologies Used

*   Python
*   Pandas (for data manipulation and analysis)
*   Matplotlib and Seaborn (for data visualization)

## Analysis Steps

The project has the following structure;

1.  **Importing and Checking Data**: Load the dataset and get a preliminary understanding of its structure and content.
2.  **Cleaning Dataset**: Address missing values by filling some with 'Unknown' and dropping rows for others. Duplicate rows are also handled, and the `date_added` column is converted to datetime objects.
3.  **Visualising Data**: Create various visualizations to answer key questions about the Netflix content.
    *   **Most Common Genres**: A clustered bar chart displays the top 5 genres, broken down by content type (Movie/TV Show).
    *   **Release Format Change**: A stacked bar chart illustrates the yearly distribution of Movies and TV Shows, showing how content formats have evolved.
    *   **Average Movie Length Trend**: A bar chart shows the average duration of movies by release year, revealing any trends in movie lengths.
