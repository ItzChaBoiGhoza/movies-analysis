# movies-analysis
Exploratory Data Analysis (EDA) process on the Netflix dataset, which contains information about Movies and TV Shows available on the platform as of mid-2021 data.

## Objectives
This analysis aims to answer the following questions:
- What type of content (Movies or TV Shows) dominates in Netflix? And, which is the common one over the years?
- How has the number of releases changed over the years?
- Which genre are the most common?
- Which countries produces the most content?
- What is the extend of diffrent ratings on Netflix based on the type (Movies or TV Shows)?
- How do content durations vary between movies and TV shows?
- Which directors produces the most titles on Netflix?
- Which month sees the most content added on Netflix?

## Dataset Description
The dataset contains **8,807** titles with the following columns:
- `show_id`: Unique ID for every titles.
- `type`: Identifier whether the title is Movie or TV Show.
- `title`: Title of the Movie / TV Show.
- `director`: Director of the title.
- `cast`: Actors involved in the Movie / TV Show.
- `country`: Country where the content was produced.
- `date_added`: Date content was added on Netflix.
- `release_year`: Original release year.
- `rating`: Content rating (e.g., PG, TV-MA).
- `duration`: Total duration - in minutes or number of seasons.
- `listed_in`: Genre/categories.
- `description`: Brief summary of the content.

## Key Insights

### Content Type Trends
- The majority of Netflix content is **Movies**, accounting for **43.67% more titles** than TV Shows.
- Between year **2000 and 2020**, Movies saw a significant rise, which could reflect the popularity of films during that era.
- From **2025 to 2021**, Netflix expanded their catalog, peaking in **2019** driven primarily by the addition of Movies catalog.

---

### Genre Insights
- The most common genres on Netflix are **International**, followed by **Dramas** and **Comedies**.
- Across most genres, **Movies** dominate over TV Shows in count.

---

### Country Distribution
The top 10 content-producing countries on Netflix are:
**United States**, **India**, **United Kingdom**, **Canada**, **France**, **Japan**, **Spain**, **South Korea**, **Germany**, and **Mexico**.

Unsurprisingly, the **United States** leads, consistent with Hollywood's global influence and production scale.

---

### Rating Analysis
- The most common ratings are **TV-MA (Mature Content)** and **TV-14**, showing Netflix's focus on teen and adult audiences.
- Most of these rated titles belong to the **Movie** category.

---

### Duration Insights
- **Movies** typically range from **90 - 125 minutes**, with the **Classic** genre having the longest duration (~120 minutes).
- **TV Shows** are most often **1 season long**, with few extending beyond 5 seasons. Among the 1-season TV Shows, **International** titles are the most common.

---

### Directors
The most prolific director on Netflix is **Rajiv Chilaka**, CEO of hyderabad-based Green Gold Animation and creator of several animated series, with **19 titles** on the platform.

---

### Content Addition Over Time
Netflix tends to add the most content during **July** and **December**, aligning with **summer** and **holiday seasons** when viewership peaks.

---

### Strategic Insight
From a produce's perspective:
- Focus on creating **Movies**, especially within **Drama**, **Comedy**, or **International** genres.
- Keep duration between **90 - 125 minutes** for optimal audience engagement.
- Try to target release periods around **July** or **December**, when Netflix commonly add new content.
- Aim for content rated **TV-14** or **TV-MA** to align with platform trends and audience demographics.

## Acknowledgement
Dataset is from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)