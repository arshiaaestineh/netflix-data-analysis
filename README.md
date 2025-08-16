# 🎬 Netflix Movies & TV Shows — Exploratory Data Analysis  

## 📌 Project Overview  
This project explores the **Netflix dataset** containing information about movies and TV shows available on the platform.  
The goal of this analysis is to **uncover patterns, trends, and insights** about Netflix's content library through data cleaning, visualization, and descriptive statistics.  

---

## 📂 Dataset  
- **Source**: [Netflix Titles on Kaggle](https://www.kaggle.com/shivamb/netflix-shows)  
- **Size**: ~7,800 entries  
- **Features**:  
  - `show_id`: Unique identifier  
  - `type`: Movie / TV Show  
  - `title`: Title of the content  
  - `director`: Director(s) of the content  
  - `cast`: Main cast members  
  - `country`: Country of production  
  - `date_added`: Date content was added to Netflix  
  - `release_year`: Original release year  
  - `rating`: Content rating (e.g., PG, R, TV-MA)  
  - `duration`: Duration in minutes (Movies) / Number of seasons (TV Shows)  
  - `listed_in`: Genres  
  - `description`: Brief summary of the content  

---

## 🔧 Steps Performed  

### 1️⃣ Data Cleaning  
- Handled **missing values** using appropriate strategies:  
  - Filled categorical columns (`country`, `rating`, etc.) with **mode**.  
  - Cleaned and standardized string values.  
- Extracted **year** and **month** from `date_added`.  
- Normalized multi-valued columns like `country` and `listed_in` by splitting and exploding.  

### 2️⃣ Exploratory Data Analysis (EDA)  
- **Yearly additions trend**: Number of new titles added by year.  
- **Country analysis**: Top producing countries and their contribution.  
- **Genre analysis**: Most popular genres in Netflix’s catalog.  
- **Type distribution**: Ratio of Movies vs. TV Shows.  

### 3️⃣ Visualizations  
- Bar charts and plots using **Matplotlib** & **Seaborn** to showcase:  
  - 📈 Growth of content over the years.  
  - 🌍 Countries with the most titles.  
  - 🎭 Top genres.  
  - 🎥 Movie vs. TV Show distribution.  

---

## 📊 Key Insights  
1. Netflix’s content library has **grown rapidly since 2015**, with a peak in 2019–2020.  
2. **Movies dominate** the catalog, but TV shows have steadily increased.  
3. The **United States, India, and the UK** are the top content producers.  
4. Popular genres include **International Movies, Dramas, and Comedies**.  

---

## 🔮 Future Work  
- Build a **recommendation system** for personalized content.  
- Perform **sentiment analysis** on descriptions.  
- Explore **temporal genre trends** (how preferences change over time).  
- Use external sources (IMDb/Rotten Tomatoes) to measure **quality vs. quantity**.  

---

## 🛠️ Tools & Libraries  
- **Python 3.9+**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib** & **Seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive analysis  

---
✨ Author
👤 Arshia Estineh

📌 Machine Learning Enthusiast | Data Analyst
📫 Contact: arshiaestineh2005@icloud.com
🐙 GitHub: arshiaaestineh
if you like this project, don’t forget to ⭐ star the repo!