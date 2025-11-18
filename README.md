```markdown
#  Bihar Assembly Elections 2025 — Complete Candidate-Level Dataset & Analysis

This repository contains a **comprehensive, candidate-level dataset** of the **Bihar Assembly Elections 2025**, scraped directly from the **Election Commission of India (ECI)** official results portal.  
It includes data for all **243 assembly constituencies**, covering **every candidate**, their vote details, party affiliation, and vote share.  
The project also provides data cleaning scripts, exploratory data analysis (EDA), and visualizations for deeper insights.


##  About the Dataset

This dataset contains **complete, verified results** from the **Bihar Assembly Elections 2025**, obtained directly from the official **ECI results portal**.

###  What Each Row Represents

Each row corresponds to the **performance of a single candidate** in a constituency and contains:

- **Constituency Number**  
- **Constituency Name**  
- **Candidate Name**
- **Party Affiliation**
- **EVM Votes**
- **Postal Votes**
- **Total Votes** – (EVM + Postal)
- **Vote Percentage**

###  Dataset Coverage

The dataset includes:

- All major and minor political parties  
- Independent candidates  
- NOTA (None of the Above)  
- Vote distribution for all 243 constituencies  
- Verified counts from ECI  
- Consistent formatting and cleaned values  

---

##  Data Collection & Cleaning

###  Data Source  
- **Official Website:** Election Commission of India (ECI) – Results Portal  
- **Method:** Automated web scraping (Python, BeautifulSoup/Requests/Selenium)  
- **Verification:** Manual verification checks for data accuracy and consistency  

### 🛠 Cleaning Steps Performed
- Standardized column names  
- Removed duplicates  
- Parsed numerical fields  
- Filled missing values appropriately  
- Converted invalid entries (e.g., malformed counts)  
- Prepared the dataset for analysis & modeling  

---

##  Exploratory Data Analysis (EDA)

The `02_eda_visualization.ipynb` notebook includes:

- Distribution of total votes  
- Vote percentage analysis  
- Party-wise performance  
- Comparison of EVM vs Postal votes  
- Winning margin visualizations  
- Constituency-level vote behavior  
- Heatmaps, histograms, boxplots, bar charts  

Example insights you can explore:

- Which party dominated specific regions?  
- How many candidates received 0–5% vote share?  
- How competitive were each of the 243 constituencies?  
- Patterns in postal ballots vs EVM votes  

---
##  Feature Engineering

The feature engineering notebook includes:

- Vote share ratios  
- Postal-vote share  
- Party dummy encoding  
- Constituency-level group statistics  
- Handling high-cardinality categorical features  
- ML-ready dataset creation  

---

##  Machine Learning (Optional)

Baseline models included (if enabled):

- **Classification:** Predict winning candidate/party  
- **Regression:** Predict total votes or vote share  
- **Models Used:**  
  - Logistic Regression  
  - Random Forest Classifier  
  - Random Forest Regressor  
  - Linear Regression  

These models allow experimenting with electoral predictions and constituency-level performance.

---

##  Visualizations

This project includes:

- Party-wise total votes  
- Candidate-level vote distribution  
- Constituency vote heatmaps  
- EVM vs Postal vote comparison plots  
- Top/worst performing candidates  
- Geographic visualization (optional extension)  

---

##  How to Use This Repository

### **1. Clone the Repository**
```bash
git clone https://github.com/gowthamgspatil/Bihar-Assembly-Elections.git
cd Bihar-Assembly-Elections
````

### **2. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **3. Open Jupyter Notebook**

```bash
jupyter notebook
```

### **4. Run the Notebooks in Order**

1. `01_data_cleaning.ipynb`
2. `02_eda_visualization.ipynb`
3. `03_feature_engineering.ipynb`
4. `04_ml_baseline_models.ipynb`

---

##  Future Improvements

Planned / suggested enhancements:

*  **Geospatial analysis** of constituency-wise results
*  **Time-series comparison** with previous elections (2020, 2015)
*  **Interactive Dashboard** using Streamlit / Power BI / Tableau
*  **Advanced ML modeling** for pattern detection or predictions
*  **Automated pipeline** for scraping & updating future elections

---

##  Author

**Gowtham Gs Patil**
 Email: **[gowthamgshivamurthy@gmail.com](mailto:gowthamgshivamurthy@gmail.com)**
 GitHub: [gowthamgspatil](https://github.com/gowthamgspatil)


