# 📺 Amazon Prime Video Exploratory Data Analysis (EDA)

> **A comprehensive Exploratory Data Analysis (EDA) project on the Amazon Prime Video Titles and Credits datasets using Python, Pandas, Matplotlib, and Seaborn.**

---
## 🖼️ Project Cover
<img width="1189" height="590" alt="Chart - 19 Average IMDb Score by Genre and Content Type" src="https://github.com/user-attachments/assets/27cf7cf0-47c4-4a82-8b2f-3d6efae90e5a" />

## 📌 Project Overview

This project performs an in-depth **Exploratory Data Analysis (EDA)** on the **Amazon Prime Video Titles** and **Credits** datasets. The objective is to analyze the platform's content library, identify meaningful patterns, and generate business insights that can support strategic decision-making.

The project follows the **UBM (Univariate, Bivariate, and Multivariate)** analysis approach and includes extensive **data cleaning**, **feature engineering**, **dataset integration**, and **business storytelling** through professional visualizations.

---

## 🎯 Business Objective

The primary objective of this project is to analyze Amazon Prime Video's content library and answer important business questions such as:

- Which content type dominates the platform?
- Which genres receive the highest audience ratings?
- Which genres are the most popular?
- How has the content library grown over time?
- Which actors and directors contribute the most?
- What factors influence IMDb ratings and popularity?

The insights generated from this analysis can help improve:

- 📈 Content Acquisition
- 🎬 Production Planning
- 🤖 Recommendation Systems
- 📊 Business Decision Making
- 👥 Audience Engagement

---

# 📂 Dataset Information

The project uses **two datasets**.

### 📄 Titles Dataset

Contains information about Amazon Prime titles including:

- Title
- Content Type
- Genres
- Runtime
- IMDb Score
- TMDb Popularity
- Release Year
- Country
- Age Certification

---

### 🎭 Credits Dataset

Contains information about:

- Actors
- Directors
- Roles
- Person ID
- Content ID

The datasets were merged using the **id** column to perform contributor-based analysis.

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- OpenPyXL

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- ✅ Duplicate Removal
- ✅ Missing Value Analysis
- ✅ Feature Engineering
- ✅ Dataset Integration (Merge)
- ✅ Exception Handling
- ✅ Data Validation

---

# 📊 Exploratory Data Analysis

The notebook contains **21 meaningful visualizations** covering:

## 🔹 Univariate Analysis

- Distribution of Content Type
- Content Release Trend
- IMDb Rating Distribution
- Runtime Distribution
- Top Genres
- Age Certification Distribution
- Credits Role Distribution
- Top Directors by Number of Titles

---

## 🔹 Bivariate Analysis

- Content Type vs IMDb Rating
- Runtime vs IMDb Score
- Correlation Heatmap
- Top Genres by Content Type
- Average IMDb Rating by Genre
- Content Growth Over Time
- Top Directors vs Average IMDb Score
- Top Actors by Number of Titles

---

## 🔹 Multivariate Analysis

- Average IMDb Score by Genre and Content Type
- Runtime vs IMDb Score by Content Type
- Average TMDb Popularity by Top Genres

---

# 🔑 Key Insights

- 🎬 **Movies** dominate the Amazon Prime content library.
- ⭐ **TV Shows** generally receive higher **IMDb ratings** than Movies.
- 🚀 **Sci-Fi**, **Action**, and **Thriller** have the highest **TMDb popularity**.
- 📚 **Documentary** content consistently achieves the highest audience ratings.
- 🎥 Producing more titles does **not necessarily** result in higher IMDb scores for directors.
- 👥 The merged analysis provides deeper insights into the contribution of actors and directors.

---

# 💼 Business Impact

The findings from this project can help streaming platforms:

- Improve Recommendation Systems
- Optimize Content Acquisition
- Identify High-Performing Genres
- Understand Audience Preferences
- Enhance Marketing Strategies
- Support Data-Driven Decision Making

---

# 📷 Sample Visualizations

<img width="1089" height="554" alt="Chart - 15 Content Growth Over Time by Content Type" src="https://github.com/user-attachments/assets/77de695b-5223-42d1-8c04-05363c7840e9" />

<img width="827" height="592" alt="Chart - 11 Correlation Heatmap of Numerical Features" src="https://github.com/user-attachments/assets/17f55b94-e55b-4b2b-8c56-4a8a70a542ee" />

<img width="972" height="554" alt="Chart - 17 Top Directors vs Average IMDb Score" src="https://github.com/user-attachments/assets/ab132172-4c4a-4a44-b9c6-749780c03afb" />

<img width="1189" height="590" alt="Chart - 19 Average IMDb Score by Genre and Content Type" src="https://github.com/user-attachments/assets/c7c94bb3-49e1-49e1-9c33-fa7251282696" />

<img width="988" height="590" alt="Chart 21 - Average TMDb Popularity by Top 10 Genres" src="https://github.com/user-attachments/assets/ca5b5a3f-1dd3-4a96-a8ac-c68b9d775fcd" />
---

```markdown
![Content Type](images/chart1_content_type.png)

![Heatmap](images/chart11_heatmap.png)

![Top Directors](images/chart17_directors.png)

![Average IMDb Score by Genre and Content Type](images/chart19_scores.png)

![TMDb Popularity](images/chart21_tmdb_popularity.png)
```

---

# 📁 Repository Structure

```
Amazon-Prime-EDA/
│
├── Amazon_Prime_EDA.ipynb
├── README.md
├── titles.xlsx
├── credits.xlsx
└── images/
```

---

# ▶️ Installation

Clone the repository:

```bash
[git clone https://github.com/Sakshantpatil/Capstone-Amazon-Prime-EDA.git](https://github.com/Sakshantpatil/Capstone-Amazon-Prime-EDA)
```

Move into the project directory:

```bash
cd Capstone Amazon-Prime-EDA
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

Run the notebook using **Google Colab** or **Jupyter Notebook**.

---

# 📈 Results

The project successfully transforms raw Amazon Prime streaming data into meaningful business insights using **Exploratory Data Analysis (EDA)**. Through **21 professional visualizations**, it identifies audience preferences, content trends, genre performance, and contributor analysis, enabling data-driven business decisions for streaming platforms.

---

# 🚀 Future Improvements

- Build an interactive **Power BI Dashboard**
- Develop a **Recommendation System**
- Predict IMDb ratings using Machine Learning
- Deploy the project using **Streamlit** or **Flask**
- Integrate additional OTT platform datasets for comparative analysis

---

# 👨‍💻 Author

**Sakshant Patil**

🎓 B.E. Computer & Data Science

📌 Data Analyst | Data Scientist | Power BI Enthusiast

**GitHub:** [https://github.com/Sakshant_Patil](https://github.com/Sakshantpatil)

**LinkedIn:** www.linkedin.com/in/sakshant-patil-021a56374

---

# ⭐ If you found this project useful, please consider giving it a Star!
