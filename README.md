# Netflix Case Study – Exploratory Data Analysis (EDA)

## Business Problem
Netflix is one of the world’s largest OTT platforms with a diverse global content library.
With increasing competition from other streaming platforms, Netflix must make
data-driven decisions on:
- What type of content to produce (Movies vs TV Shows)
- Which genres drive the highest engagement
- Which regions offer strong growth opportunities
- How content strategy has evolved over time

This project performs an Exploratory Data Analysis (EDA) on Netflix’s content dataset
to extract actionable business insights that can support strategic decision-making.

---

## Dataset Description
- **Source:** Netflix titles dataset (up to mid-2021)
- **Records:** ~8,800 Movies and TV Shows
- **Key Attributes:**
  - Type (Movie / TV Show)
  - Title
  - Director
  - Cast
  - Country
  - Date Added
  - Release Year
  - Rating
  - Duration
  - Genre (Listed_in)

---

## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Performed
- Data loading and inspection
- Data type validation
- Missing value analysis and treatment
- Feature extraction from date columns
- Univariate analysis (content type, ratings, genres, release years)
- Bivariate analysis (content type vs year, country, ratings, genres)
- Visual analysis using plots and charts
- Business-focused interpretation of results

---

## Key Insights
- Movies dominate Netflix’s content library, but TV Shows have grown significantly in recent years.
- Netflix strongly focuses on mature and young-adult audiences (TV-MA, TV-14, R).
- Dramas, International Movies, Comedies, and Documentaries are the most common genres.
- The United States is the largest content contributor, followed by India and the UK.
- Rapid growth in content additions occurred after 2015, aligning with Netflix’s global expansion phase.
- TV Shows are increasingly used for user retention rather than content volume alone.

---

## Business Recommendations
- Increase investment in regional and international TV Shows to improve user retention.
- Expand family and kids content to diversify audience segments.
- Continue focusing on high-engagement genres like Dramas and Documentaries.
- Reduce over-dependence on U.S. content by strengthening international original productions.
- Maintain a balanced portfolio of Movies (for acquisition) and TV Shows (for retention).

---

## Project Structure
Netflix-Case-Study-EDA/
│
├── data/
│ └── netflix_titles.csv
│
├── notebooks/
│ └── Netflix_Case_Study_EDA.ipynb
│
├── reports/
│ └── Netflix_Case_Study_EDA.pdf
│
├── README.md
└── .gitignore

---

## Conclusion
This project demonstrates how exploratory data analysis can be used to translate raw
content metadata into meaningful business insights. The findings can help guide
Netflix’s content strategy, regional expansion, and audience targeting decisions.

---

## Author
**Karan Agarwal**  
Aspiring Data Analyst and Data Scientist
www.linkedin.com/in/karan-agarwal-jain94