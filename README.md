# 📊 Netflix Power BI Dashboard  

An interactive Power BI dashboard analyzing Netflix’s global catalog — uncovering **content trends, genres, release years, and audience insights**.  

## 🔍 Project Overview  

Netflix has grown into one of the world’s largest streaming platforms, producing and distributing content worldwide. With thousands of movies and TV shows across multiple countries and genres, it can be hard to understand the bigger picture.  

This project analyzes Netflix’s catalog using **Power BI** to identify:  
- Content trends and release patterns  
- Genre distribution over time  
- Country-wise contributions  
- Audience maturity ratings  

👉 **Goal**: To showcase **data storytelling + visualization skills** while answering real business questions such as:  
- Which genres dominate Netflix’s library?  
- Which years saw peak content addition?  
- How does content vary by country?  
- Are TV shows catching up with movies in volume?  

## 🛠️ Tools & Dataset  

**Tools Used**  
- Power BI Desktop → dashboard building & visualization  
- Excel / Power Query → dataset cleaning & preparation  
- GitHub → version control & portfolio hosting  

**Dataset**  
- Source: [Netflix Movies and TV Shows — Kaggle Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) by Shivam Bansal  

## 🧹 Data Cleaning & Preparation  

The original dataset contained nulls, duplicates, and inconsistent formats. I applied multiple cleaning steps before analysis:  
- ✅ Removed missing values in *director, cast, rating* where possible  
- ✅ Split multiple genres & countries into separate rows  
- ✅ Extracted `release_year` and `added_year` from `date_added`  
- ✅ Normalized ratings (TV-MA, TV-14, PG, etc.)  
- ✅ Standardized column names & formatting  

Final cleaned dataset: **netflix_clean.csv**  

## 📈 Dashboard Walkthrough  

**1. Overview Page**  
- KPIs: Total Titles, Movies vs TV Shows, Country Count  
- Timeline of releases  
- Quick global snapshot  

**2. Genre Analysis**  
- Distribution of titles by genre  
- Top 10 genres overall  
- Trends of genres over years  

**3. Country & Languages**  
- Map view of titles by country  
- Contribution of top producers  
- Popular languages  

**4. Ratings & Duration**  
- Rating distribution (TV-MA, PG-13, etc.)  
- Average movie duration vs TV Show seasons  
- Ratings trend over years  

## 💡 Key Insights  

- 🎬 **Movies dominate** Netflix’s catalog (~70%), though TV Shows are growing steadily.  
- 🌍 **United States leads** content production, followed by **India** and the **UK**.  
- 📅 **2019 was the peak** year for new releases, with a dip in 2020 (COVID impact).  
- 🎭 **Drama, Comedy, and Documentaries** are the top 3 genres globally.  
- 🔞 **TV-MA rating dominates**, showing a strong focus on mature audiences.  
- ✨ **Business takeaway**: Expanding into **regional, non-English genres** (e.g., India & Brazil) could help Netflix diversify and capture new audiences.  

## 🚀 How to Explore  

- **Quick View** → See `netflix_dashboard.pdf` or browse images in the `screenshots/` folder  
- **Interactive View (Recommended)** → Download `netflix_dashboard.pbix` and open in **Power BI Desktop** (latest version)

  ## 🔗 Connect & Explore More  
- 💼 LinkedIn Post: [Project Walkthrough & Insights](https://www.linkedin.com/posts/sakshi-verma-841045285_powerbi-dataanalytics-netflixinsights-activity-7331646334833238016-bqeU?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEU9OnEBaBEIQXaz-TIOqDeb7BKd_AFZl-w)  

📌 *This project demonstrates my ability to clean raw datasets, create interactive dashboards, and extract business insights — skills directly applicable to data analysis and BI roles.*  
