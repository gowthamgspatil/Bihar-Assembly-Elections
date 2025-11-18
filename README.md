# 🗳️ Bihar Assembly Elections 2025 — Complete Candidate-Level Dataset & Analysis

This repository contains a **comprehensive, candidate-level dataset** of the **Bihar Assembly Elections 2025**, scraped directly from the **Election Commission of India (ECI)** official results portal.  
It includes data for all **243 assembly constituencies**, covering **every candidate**, their vote details, party affiliation, and vote share.  
The project also provides data cleaning scripts, exploratory data analysis (EDA), and visualizations for deeper insights.

---

## 📊 About the Dataset

This dataset contains **complete, verified results** from the **Bihar Assembly Elections 2025**, obtained directly from the official **ECI results portal**.

### 🔍 What Each Row Represents

Each row corresponds to the **performance of a single candidate** in a constituency, including:

- **Constituency Number**  
- **Constituency Name**  
- **Candidate Name**  
- **Party Affiliation**  
- **EVM Votes**  
- **Postal Votes**  
- **Total Votes** – (EVM + Postal)  
- **Vote Percentage**

### 📌 Dataset Coverage

The dataset includes:

- All major and minor political parties  
- Independent candidates  
- NOTA (None of the Above)  
- Vote distribution for all 243 constituencies  
- Verified counts from ECI  
- Consistent formatting and cleaned values  

---

## 🧹 Data Collection & Cleaning

### 🔗 Data Source  
- **Official Website:** Election Commission of India (ECI) – Results Portal  
- **Method:** Automated web scraping (Python: BeautifulSoup, Requests, Selenium)  
- **Verification:** Manual validation checks for accuracy & consistency  

### 🛠 Cleaning Steps Performed

- Standardized column names  
- Removed duplicates  
- Parsed and cleaned numeric fields  
- Filled missing values appropriately  
- Converted invalid or inconsistent entries  
- Prepared a final clean dataset ready for EDA & ML  

---

## 📈 Exploratory Data Analysis (EDA)

The notebook `02_eda_visualization.ipynb` includes:

- Distribution of votes  
- Vote percentage analysis  
- Party-wise performance comparison  
- EVM vs Postal votes comparison  
- Winning margin distribution  
- Constituency-level behavior analysis  
- Heatmaps, histograms, boxplots & bar charts  

Example questions explored:

- Which parties performed best across regions?  
- How competitive were the constituencies?  
- How many candidates received <5% vote share?  
- What patterns exist between EVM vs postal votes?  

---

## 🛠 Feature Engineering

The `03_feature_engineering.ipynb` notebook covers:

- Vote share ratios  
- Postal vote contribution  
- Party encoding (one-hot / frequency encoding)  
- Constituency-level aggregations  
- Handling high-cardinality categories  
- Creating an ML-ready dataset  

---

## 🤖 Machine Learning (Optional)

Optional ML experiments include:

### Tasks
- **Classification:** Predict winning party/candidate  
- **Regression:** Predict total votes or vote share  

### Models Used
- Logistic Regression  
- Random Forest Classifier  
- Random Forest Regressor  
- Linear Regression  

These provide baseline models for analyzing constituency trends and vote patterns.

---

## 📊 Visualizations

This project includes:

- Party-wise vote totals  
- Candidate vote distribution  
- Constituency-level heatmaps  
- EVM vs Postal vote patterns  
- Top/worst performing candidates  
- (Optional) Geographic visualizations  

---

## 🚀 How to Use This Repository

### 1. Clone the Repository
```bash
git clone https://github.com/gowthamgspatil/Bihar-Assembly-Elections.git
cd Bihar-Assembly-Elections

2. Install Dependencies
pip install -r requirements.txt

3. Open Jupyter Notebook
jupyter notebook

4. Run the Notebooks in Order

01_data_cleaning.ipynb

02_eda_visualization.ipynb

03_feature_engineering.ipynb

04_ml_baseline_models.ipynb (optional)

👤 Author

Gowtham Gs Patil
📧 Email: gowthamgshivamurthy@gmail.com

🐙 GitHub: gowthamgspatil

⚖️ License

This project is licensed under the MIT License.
Election data remains © Election Commission of India (ECI) and is used for educational and analytical purposes only.

⭐ Support This Project

If you found this project useful:

⭐ Star the repository

🍴 Fork it

🗣️ Share with the data science and civic analytics community
