# EDA-Netflix-and-Prime-Video-Movies
Exploratory Data Analysis (EDA) of movies and TV shows on Amazon Prime Video and Netflix.

## 1. Background & Overview
   
## Key Notes
This project performs an Exploratory Data Analysis (EDA) on Netflix and Prime Video content catalogs.
It uncovers platform differences, genre trends, duration patterns, and global content distribution.
The project was done as part of my data-science learning journey, applying statistics, visualization, and data cleaning skills.

## Business Context & Goals
   Streaming platforms face intense competition. Understanding content trends helps:
   Optimize content acquisition and production
   Identify viewer engagement opportunities
   Strengthen platform differentiation
   Improve regional and genre coverage

## Why This Project Matters
   Helps platform teams make data-driven content decisions
   Highlights where Netflix and Prime differ in:

## Genre focus
   Movies vs TV show proportions
   Country contributions
   Duration patterns
   Useful for content strategy, media analytics, and entertainment research

## 2. Data Structure Overview

## Dataset Details
   Source: Publicly available content catalog for Netflix and Prime Video
   Rows: 18,477 titles
   Columns: 16 metadata attributes
   Period: Release years from 1920–2024
   Regions: U.S., India, UK, Japan, and global markets

## Main Tables / Columns Used

| Column             | Description                |
| ------------------ | -------------------------- |
| `show_id`          | Unique ID                  |
| `type`             | Movie or TV Show           |
| `title`            | Title of the content       |
| `director`, `cast` | Key people                 |
| `country`          | Country of origin          |
| `date_added`       | Date added to platform     |
| `release_year`     | Year of release            |
| `rating`           | Content rating             |
| `duration`         | Total duration             |
| `duration_movies`  | Numeric duration (minutes) |
| `duration_tv`      | Number of seasons          |
| `listed_in`        | Genre(s)                   |
| `description`      | Short summary              |
| `Platform`         | Netflix or Prime           |
| `Platform_Id`      | Numerical indicator        |

## 3. Executive Summary — Key Insights
   Movies dominate overall, but:
   Netflix has more TV shows
   Prime Video has more movies
   Prime Video has slightly more total content
   Top genres: Drama, Comedy, Action, Documentaries, Action & Adventure
   Duration differences:
   Netflix movie average: 99 mins
   Prime Video movie average: 91 mins
   Country contributions: U.S. leads; major presence from India, UK, Japan
   **Content additions peaked from 2018–2021

## Statistical findings:
   T-test: Movie durations differ significantly between platforms
   ANOVA: Genres significantly influence durations
   Notable outliers exist for exceptionally long movies

##  4. Insights Deep Dive
   Platform Differences
     Netflix invests heavily in TV shows
     Prime Video leans toward movie-heavy catalog
   Genre Patterns
     Drama consistently dominates both platforms
     Action & Adventure more common on Prime
     Netflix has more documentaries and international content
   Duration Trends
     Netflix prefers longer movies
     Prime Video includes more shorter, diverse-range movies
   Geographical Insights
     U.S. remains the major producer
     India contributes heavily to Prime Video, aligning with regional strategies
     Netflix shows more variety across Europe and East Asia
   Statistical Insights
     T-test: Confirms measurable difference in durations across platforms
     ANOVA: Genre is a major factor in runtime variation
     Normality tests: Duration data shows mild skewness & outliers

## 5. Recommendations
For Streaming Platforms
Netflix
   Expand shorter, quick-watch movies to balance catalog
   Increase regional-specific content to compete with Prime Video in India

Prime Video
   Invest more in high-quality TV originals to match Netflix’s strength
   Promote long-duration premium movies to attract binge viewers

General Strategy Suggestions
    Focus on genres with high global traction: Drama, Action, Comedy
    Leverage data insights to plan acquisitions in underrepresented regions
    Release more content during peak engagement years (historically 2018–2021 range)

## 6. Caveats & Assumptions
   * Dataset may not represent complete catalogs
   * Missing values were cleaned and imputed where necessary
   * Outliers (very long movies) could influence averages
   * Country information sometimes incomplete or aggregated
   * Catalog changes post-2021 are not included in this study

## 7. Tools & Technologies
    Python
    Pandas, NumPy
    Matplotlib, Seaborn
    SciPy (T-test, ANOVA)
    Jupyter Notebook
    Excel (raw data)
    Data Cleaning & Feature Engineering techniques

## 8. Conclusion

     This project provided a comprehensive look into content trends, platform differences, and regional dynamics between Netflix and Prime Video. By applying full EDA workflows—data cleaning, visualization, statistical testing—this analysis highlights how data insights can directly influence content strategy, competitiveness, and viewer engagement in the streaming industry.

It also strengthened my practical expertise in:
     Data analysis
     Visualization
     Statistical inference
     Business-oriented storytelling
