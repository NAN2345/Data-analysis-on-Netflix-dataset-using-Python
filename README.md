# Data-analysis-on-Netflix-dataset-using-Python
## Overview

This project involves the analysis of a comprehensive dataset sourced from Netflix. The dataset contains information on various movies and TV shows available on the platform. Through this analysis, we aim to uncover insights into the content library, trends over time, and key contributors to Netflix's offerings.

## Features

### Data Preparation and Cleaning
- **Duplicate Removal**: Duplicate records within the dataset are identified and removed to ensure data integrity.
- **Null Value Detection**: Null values across different columns are identified and visualized using heatmaps for easy detection.

### Exploratory Data Analysis (EDA)
- **Yearly Analysis**: The dataset is analyzed to determine the distribution of movies and TV shows released each year. This includes visualizations such as bar graphs showcasing the yearly trends.
- **Category and Type Distribution**: The distribution of content across different categories (e.g., movie, TV show) and types (e.g., dramas, comedies) is examined.
- **Top Directors**: Identification of the top directors contributing to Netflix's content library based on the number of movies and TV shows they have directed.
- **Cast Analysis**: Analysis of cast members, including specific queries such as instances where Tom Cruise was cast.

### Querying Insights
1. **Duplicate Record Removal**: The dataset is checked for duplicate records, and if found, they are removed to maintain data accuracy.
2. **Null Value Detection**: Null values are visualized using heatmaps, aiding in identifying areas with missing data.
3. **Show Identification**: The Show ID and director for 'House of Cards' are extracted.
4. **Yearly Releases**: Movies released in the year 2020 are listed.
5. **Country-specific TV Shows**: Titles of TV shows released exclusively in India are identified.
6. **Top Directors**: The top 10 directors contributing to Netflix's content library are listed based on the number of movies and TV shows directed.
7. **Filtering by Category and Type**: Records meeting specific criteria, such as movies categorized as comedies or originating from the United Kingdom, are extracted.
8. **Cast Analysis**: Instances where Tom Cruise was cast are determined.
9. **Rating Identification**: Different ratings defined by Netflix are listed, and related queries such as the number of movies with a 'TV-14' rating in Canada are answered.
10. **Maximum Duration**: The maximum duration of a movie or show on Netflix is identified.
11. **Country with Highest TV Shows**: The country with the highest number of TV shows is determined.

### Usage

To use this project:
1. Clone the repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Execute the main Python script, `netflix_analysis.py`, to perform analyses and explore the dataset.

### Contribution

Contributions to this project are encouraged! Feel free to fork the repository, make improvements, and submit pull requests adhering to the project's coding standards and guidelines.


