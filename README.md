# 📊 Netflix Data Cleaning & Analysis

This project focuses on cleaning and analyzing Netflix's movie and TV show dataset using Python and Pandas. The aim is to gain insights into content trends, ratings, duration types, and other key attributes to help understand Netflix's content distribution strategy.

---

## 🗂️ Project Structure
netflix_data_cleaning_analysis/
├── Netflix Dataset.csv  https://www.kaggle.com/datasets/shivamb/netflix-shows
├── Netflix Data Cleaning.ipynb
├── Netflix Data Analysis.ipynb
├── .gitignore
└── README.md


---

## 📌 Objectives

- Clean and preprocess Netflix's raw dataset
- Handle missing, inconsistent, and duplicated data
- Perform exploratory data analysis (EDA)
- Visualize trends in Netflix content (genre, release year, country, etc.)
- Derive insights from the cleaned data

---

## 📁 Dataset

The dataset used is publicly available and contains information about Netflix shows and movies. Key columns include:

- `Title`
- `Director`
- `Cast`
- `Country`
- `Date Added`
- `Release Year`
- `Rating`
- `Duration`
- `Genres`
- `Description`

---

## 🧼 Data Cleaning Steps

Performed in `Netflix Data Cleaning.ipynb`, key steps include:

- Dropping duplicates
- Handling null values
- Standardizing column values
- Converting data types (e.g., date formats)
- Splitting multiple values into separate columns (e.g., country, genre)
- Removing extra whitespaces and formatting issues

---

## 📊 Data Analysis

Conducted in `Netflix Data Analysis.ipynb`, highlights include:

- Distribution of content over years
- Most common genres and ratings
- Top contributing countries
- Relationship between type (Movie/TV Show) and duration
- Seasonal content trend analysis

---

## 📷 Sample Visualizations

- Bar plots of content by country
- Pie charts of ratings distribution
- Line plots of content release trends
- Heatmaps for correlation analysis

---

## 🔧 Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📌 Insights

- Majority of Netflix content comes from the US and India
- TV Shows are increasing year over year
- TV content has shorter durations while movies vary widely
- The most common rating is `TV-MA` followed by `TV-14`

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/khankaif17/Netflix-Data-analysis-using-python-and-SQL.git
2. cd netflix_data_cleaning_analysis
3. jupyter notebook
4. Run:
Netflix Data Cleaning.ipynb first
Then Netflix Data Analysis.ipynb

⭐️ Contributions
If you'd like to contribute, feel free to fork the repo and submit a pull request!

