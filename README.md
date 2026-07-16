# 🎬 Netflix Content Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Netflix Movies and TV Shows dataset** to uncover meaningful patterns, trends, and insights about Netflix's content library.

The analysis explores the distribution of Movies and TV Shows, content growth over time, top content-producing countries, popular genres, content ratings, movie durations, and directors with the most titles.

This project demonstrates practical skills in **data cleaning, data manipulation, exploratory data analysis, and data visualization** using Python.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze the distribution of Movies and TV Shows on Netflix.
- Explore how Netflix's content library has changed over the years.
- Identify the top content-producing countries.
- Discover the most common genres and content categories.
- Analyze the distribution of content ratings.
- Explore the distribution of movie durations.
- Compare the number of Movies and TV Shows added over time.
- Identify directors associated with the highest number of titles.
- Extract meaningful insights through data visualization.

---

## 🛠️ Technologies and Libraries Used

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
- **Visual Studio Code**

---

## 📂 Project Structure

```text
Netflix-Content-Analysis/
│
├── data/
│   └── netflix_titles.csv
│
├── notebooks/
│   └── netflix_content_analysis.ipynb
│
├── images/
│   ├── movies_vs_tvshows.png
│   ├── content_added_over_years.png
│   ├── top_10_countries.png
│   ├── top_10_genres.png
│   ├── ratings_distribution.png
│   ├── movie_duration_distribution.png
│   ├── movies_vs_tvshows_over_years.png
│   └── top_10_directors.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📊 Dataset

The project uses the **Netflix Movies and TV Shows dataset**.

The dataset contains information about titles available on Netflix, including:

- Show ID
- Content Type
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre / Category
- Description

The dataset contains both **Movies** and **TV Shows**, making it suitable for analyzing Netflix's content library and identifying trends across different categories.

---

## 🧹 Data Cleaning

Before performing the analysis, the dataset was cleaned and prepared using Pandas.

The data-cleaning process included:

- Checking the dimensions and structure of the dataset.
- Examining column names and data types.
- Checking for missing values.
- Checking for duplicate records.
- Removing duplicate rows.
- Handling missing values in categorical columns.
- Removing rows with a small number of missing values in essential columns.
- Converting the `date_added` column into datetime format.
- Creating additional columns such as:
  - `year_added`
  - `month_added`
- Extracting numeric movie duration values for duration analysis.

---

# 📈 Exploratory Data Analysis

## 1. Movies vs TV Shows

This analysis compares the number of **Movies** and **TV Shows** available in the Netflix dataset.

![Movies vs TV Shows](images/movies_vs_tvshows.png)

### 🔍 Insight

Movies make up the majority of Netflix content in this dataset, with substantially more Movies than TV Shows. This indicates that the Netflix catalog represented in the dataset is predominantly movie-focused.

---

## 2. Content Added to Netflix Over the Years

This analysis examines how the number of titles added to Netflix changed over time.

![Content Added Over the Years](images/content_added_over_years.png)

### 🔍 Insight

The number of titles added to Netflix increased significantly over the years, reflecting the rapid expansion of the platform's content library. The trend also shows changes in the rate of content additions during the later years represented in the dataset.

---

## 3. Top 10 Content-Producing Countries

This analysis identifies the countries associated with the highest number of titles in the Netflix dataset.

For titles associated with multiple countries, the country values were separated before calculating the frequency of each country.

![Top 10 Content-Producing Countries](images/top_10_countries.png)

### 🔍 Insight

The United States contributes the largest number of titles to the Netflix catalog, followed by other major content-producing countries. The results demonstrate Netflix's international reach while also showing that a significant portion of its content originates from a few major markets.

---

## 4. Top 10 Genres on Netflix

This analysis identifies the most common genres and content categories available in the Netflix dataset.

Since a single title may belong to multiple categories, the genre values were separated before calculating their frequency.

![Top 10 Genres](images/top_10_genres.png)

### 🔍 Insight

Popular categories such as **International Movies, Dramas, and Comedies** are strongly represented in the Netflix catalog. This indicates a focus on globally diverse content and widely consumed entertainment genres.

---

## 5. Distribution of Content Ratings

This analysis examines the distribution of content ratings to better understand the target audience of titles available on Netflix.

![Ratings Distribution](images/ratings_distribution.png)

### 🔍 Insight

The Netflix catalog contains content for a wide range of audiences. However, mature and teen-oriented ratings represent a significant portion of the available titles, indicating a strong presence of content targeted toward older teenagers and adults.

---

## 6. Movie Duration Analysis

This analysis examines the distribution of movie durations to identify the typical length of Movies available in the Netflix dataset.

![Movie Duration Distribution](images/movie_duration_distribution.png)

### 🔍 Insight

Most movies are concentrated around typical feature-film lengths, while relatively few titles have extremely short or very long durations. The distribution shows that the majority of Movies fall within a common duration range.

---

## 7. Movies vs TV Shows Added Over the Years

This analysis compares the number of Movies and TV Shows added to Netflix each year.

![Movies vs TV Shows Over the Years](images/movies_vs_tvshows_over_years.png)

### 🔍 Insight

Both Movies and TV Shows experienced substantial growth in the number of titles added over time. Movies generally accounted for a larger number of additions, while TV Shows also showed significant growth as Netflix expanded its content library.

---

## 8. Top 10 Directors on Netflix

This analysis identifies the directors associated with the highest number of titles in the Netflix dataset.

For titles associated with multiple directors, the director values were separated before calculating their frequency.

![Top 10 Directors](images/top_10_directors.png)

### 🔍 Insight

Several directors are associated with multiple titles in the Netflix catalog. The analysis highlights the directors with the strongest representation in the dataset.

---

# 🔑 Key Insights

The exploratory data analysis revealed several important patterns:

- 🎬 **Movies dominate the Netflix catalog** represented in the dataset, with considerably more Movies than TV Shows.
- 📈 **Netflix's content library expanded significantly over time**, with substantial growth in the number of titles added.
- 🌍 **The United States is the largest content contributor**, while several other countries also have a strong presence.
- 🎭 **International Movies, Dramas, and Comedies** are among the most common content categories.
- 🔞 **Mature and teen-oriented ratings** represent a significant portion of the available content.
- ⏱️ **Most Movies fall within a typical feature-film duration range**, with fewer extremely short or long titles.
- 📺 **Both Movies and TV Shows grew over time**, although Movies generally accounted for more yearly additions.
- 🎥 **Several directors have multiple titles** represented in the Netflix catalog.

---

# ✅ Conclusion

This project explored the **Netflix Movies and TV Shows dataset** using Python-based data analysis and visualization techniques.

The dataset was cleaned, transformed, and analyzed to identify patterns related to:

- Content type
- Content growth over time
- Countries
- Genres
- Ratings
- Movie duration
- Movies vs TV Shows over time
- Directors

The analysis shows that the Netflix catalog represented in the dataset is dominated by Movies while also containing a diverse range of international content, genres, and audience ratings.

Through this project, I applied practical skills in:

- Data Cleaning
- Data Manipulation
- Exploratory Data Analysis
- Data Visualization
- Extracting Insights from Data

The project helped strengthen my understanding of working with real-world datasets using **NumPy, Pandas, Matplotlib, and Seaborn**.

---

# 🚀 How to Run the Project

## 1. Clone the Repository

```bash
git clone <repository-url>
```

## 2. Navigate to the Project Folder

```bash
cd Netflix-Content-Analysis
```

## 3. Install the Required Libraries

```bash
pip install -r requirements.txt
```

## 4. Open the Jupyter Notebook

Open:

```text
notebooks/netflix_content_analysis.ipynb
```

Run the notebook cells in order to reproduce the analysis and visualizations.

---

# 📦 Requirements

The project uses the following Python libraries:

```text
numpy
pandas
matplotlib
seaborn
jupyter
```

These dependencies are also listed in the `requirements.txt` file.

---

# 📁 Repository Contents

| File / Folder | Description |
|---|---|
| `data/` | Contains the Netflix dataset |
| `notebooks/` | Contains the complete Jupyter Notebook analysis |
| `images/` | Contains the visualizations generated during the analysis |
| `README.md` | Project documentation |
| `requirements.txt` | Required Python libraries |
| `.gitignore` | Files and folders excluded from Git tracking |

---

# 🎓 Skills Demonstrated

- Python Programming
- NumPy
- Pandas
- Data Cleaning
- Data Manipulation
- Exploratory Data Analysis (EDA)
- Data Visualization
- Matplotlib
- Seaborn
- Jupyter Notebook
- Working with Real-World Datasets

---

# 👩‍💻 Author

## Anisha Raj

**B.Tech Artificial Intelligence and Machine Learning Student**

Interested in:

- Artificial Intelligence
- Machine Learning
- Data Analysis
- Software Development

---

# ⭐ Acknowledgement

This project was created as part of my learning journey in **Python, Data Analysis, and Data Visualization**.

If you found this project useful or interesting, consider giving the repository a ⭐.
