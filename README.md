---

# DataCo Supply Chain Analysis

This repository contains the analysis of a supply chain dataset provided by DataCo. The aim is to extract actionable insights that can enhance business operations and optimize supply chain efficiency. This project includes data preprocessing, exploratory data analysis (EDA), and various visualizations to support our findings.

## Project Structure

The repository is structured as follows:

```
├── DataCo_Supply_01.ipynb
├── DataCo_Supply_02.ipynb
├── DataCo_Supply_Chain_Report.pdf
└── README.md
```

- `DataCo_Supply_01.ipynb`: Jupyter Notebook containing initial data exploration and preprocessing.
- `DataCo_Supply_02.ipynb`: Jupyter Notebook with advanced analysis and visualizations.
- `DataCo_Supply_Chain_Report.pdf`: Detailed report on the supply chain analysis.
- `README.md`: Project documentation.

## About

This project focuses on analyzing a Supply Chain dataset to extract valuable insights and optimize business operations. Through comprehensive data preprocessing, exploratory data analysis (EDA), and advanced visualizations, the project aims to provide actionable recommendations to enhance supply chain efficiency, improve financial performance, and mitigate risks related to fraud and late deliveries.

## Data Preprocessing

Initial data exploration involved:

- Identifying and handling missing values.
- Removing columns with excessive missing data.
- Addressing data discrepancies such as null values and incorrect data types.
- Harmonizing language inconsistencies.

## Key Analyses

1. **Exploratory Data Analysis (EDA)**
   - Top 10 Countries by Sale
   - Top 10 Categories by Sale
   - Products with Most Loss
   - Regions with Most Loss

2. **Financial Analysis**
   - Examined patterns in profits, sales, and discount rates.
   - Recommended maintaining discounts within 10-15% to enhance both profit ratio and sales.

3. **Late Deliveries Analysis**
   - Identified the highest likelihood of late deliveries in first-class shipments.
   - Recommended shifting focus to more reliable shipping methods like standard class.

4. **Market Analysis**
   - Analyzed geographical distribution of customer activities and sales.
   - Identified key regions for future expansion and areas needing improvement.

5. **Fraud Analysis**
   - Identified patterns in fraudulent transactions.
   - Recommended focused fraud prevention strategies based on region-specific insights.

6. **Customer Fraud Detection**
   - Highlighted recurrent instances of fraud associated with specific customer IDs.
   - Suggested stringent measures for identity verification to prevent future fraud.

7. **RFM Analysis**
   - Classified customers based on recency, frequency, and monetary factors.
   - Recommended strategies for re-engaging inactive customers and converting new customers into regular patrons.

## Actionable Insights

Based on the analysis, several recommendations have been made to optimize supply chain operations, improve financial performance, and mitigate risks related to fraud and late deliveries.

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/DataCo_Supply_Chain_Analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd DataCo_Supply_Chain_Analysis
   ```

3. Open the Jupyter Notebooks to explore the analyses:

   ```bash
   jupyter notebook DataCo_Supply_01.ipynb
   jupyter notebook DataCo_Supply_02.ipynb
   ```

## Requirements

- Python 3.6+
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Missingno

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn missingno
```

## Conclusion

This project provides a comprehensive analysis of a supply chain dataset, offering valuable insights to enhance business operations and optimize efficiency. The findings and recommendations serve as a strategic guide for decision-making in the supply chain domain.

---
