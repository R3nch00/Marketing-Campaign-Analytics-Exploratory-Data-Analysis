# Marketing Campaign Analytics – Exploratory Data Analysis
Data‑driven analysis of marketing campaigns using EDA, visualization, and statistical methods. Reveals customer insights, product preferences, and channel performance to optimize targeting, improve ROI, and enhance marketing effectiveness.

## 📌 Overview
This project performs a comprehensive **Exploratory Data Analysis (EDA)** on marketing campaign data to uncover customer insights, segment profiles, and factors influencing campaign performance. It combines statistical analysis, **feature engineering**, and **data visualization** to support data‑driven marketing strategies and improve campaign ROI.

## 📂 Dataset
- **Source:** [Kaggle Marketing Campaign Dataset] (https://www.kaggle.com/code/jennifercrockett/marketing-analytics-eda-task-final/input)
- **Records:** ~2,240 customers  
- **Features:** Demographics, income, spending on product categories, purchase channels, and campaign responses  
- **Target Variables:**  
  - `Response` – Acceptance of the most recent campaign  
  - `AcceptedCmp1`–`AcceptedCmp5` – Acceptance of previous campaigns

## 🎯 Objectives
1. **Understand customer demographics** and spending behavior.
2. **Analyze campaign performance** across different customer segments.
3. **Identify key drivers** of campaign acceptance.
4. **Visualize trends** in product purchases and channel usage.
5. Provide **actionable recommendations** for marketing optimization.

## 🧩 Project Structure
```bash
Marketing-Campaign-Analytics-Exploratory-Data-Analysis/
│
├── marketing_data/        # Raw and processed datasets
├── notebooks/             # Jupyter notebooks for analysis
├── images/                # Plots and visualizations
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies
```

---

## 🛠 Methods
- **Data Cleaning:** Handling missing values, correcting data types, removing outliers.
- **Feature Engineering:** Creating `Dependents`, `TotalMnt`, `TotalPurchases`, `Year_Customer`.
- **One‑Hot Encoding:** For categorical variables.
- **Statistical Analysis:** Hypothesis testing, correlation analysis.
- **Visualization:** Seaborn & Matplotlib for campaign, product, and channel insights.
- **Modeling (Optional):** Linear Regression & feature importance (Permutation Importance, SHAP).

---

---

## 📈 Key Visualizations
1. **Campaign Success Rate** – Bar chart of acceptance % per campaign.
2. **Product Spending Distribution** – Boxplots for each product category.
3. **Channel Effectiveness** – Purchases by web, catalog, store, and deals.
4. **Recency vs. Spending** – Scatter plot with regression line.
5. **Income vs. Campaign Acceptance** – KDE plot by response.
6. **Customer Segment Heatmap** – Acceptance rate by marital status & education.

---

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/marketing-campaign-eda.git
   cd marketing-campaign-eda
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Open the notebook:**
   ```bash
   jupyter notebook notebooks/Marketing_Campaign_EDA_and_Insights.ipynb
   ```

## 🔮 Future Work
. Build predictive models for campaign acceptance
. Deploy an interactive dashboard (e.g., Streamlit, Dash)
. Integrate external datasets for richer customer profiling

## 🤝 Contributing
. Contributions are welcome!
. Fork the repo
. Create a new branch (feature/your-feature)
. Commit your changes
. Open a Pull Request
