# 📦 Supply Chain Risk Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing supply chain risks, order delays, supplier reliability, and disruption patterns using data analytics.

The objective is to identify high-risk orders, evaluate supplier performance, understand the impact of different disruption types, and analyze order value exposure to support better business decisions.

The project was developed using **Microsoft Excel** and **Tableau Public**, with an interactive dashboard to present key performance indicators (KPIs) and business insights.

## 🎯 Business Objectives

- Identify high-risk orders and measure the overall supply chain risk rate.
- Analyze order distribution by disruption severity.
- Identify suppliers with the highest risk rates.
- Compare supply chain risk across shipping modes.
- Analyze order value exposure by disruption type.
- Provide actionable recommendations to improve supply chain operations.

## 📊 Dataset Overview

The dataset contains **1,000 order records** with information about:

- Order ID and order value
- Delay days
- Disruption type and severity
- Supplier ID and reliability score
- Historical disruption count
- Supply risk flag
- Shipping mode
- Product category
- Delayed flag

## 🛠️ Tools & Technologies

- **Microsoft Excel** – Data cleaning, analysis, PivotTables, charts, and dashboard creation.
- **Tableau Public** – Data visualization and interactive dashboard development.
- **GitHub** – Project documentation and version control.

## 🧹 Data Preparation

The following data preparation activities were performed:

- Checked and verified dataset structure.
- Checked for missing values and duplicate records.
- Replaced the `None` disruption category with `No Disruption`.
- Verified data types and categorical values.
- Created and validated the `Delayed_Flag` field.
- Prepared data for analysis and dashboard development.

## 📈 Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Orders | 1,000 |
| High-Risk Orders | 514 |
| Supply Chain Risk Rate | 51.40% |
| Total Order Value | $25,290,073.67 |
| Average Order Value | $25,290.07 |
| Average Delay | 2 Days |
| Average Supplier Reliability Score | 0.75 |

## 🔍 Key Business Insights

**1. Overall Supply Chain Risk**
- 514 out of 1,000 orders were classified as high-risk.
- The overall supply chain risk rate is 51.40%.

**2. Supplier Risk Analysis**
- Supplier S21 recorded the highest risk rate at 69.23%.
- Supplier S15 followed with a risk rate of 63.64%.
- These suppliers may require closer monitoring and performance reviews.

**3. Shipping Mode Analysis**
- Rail recorded the highest risk rate at 53.73%.
- Sea followed at 53.54%.
- Air had the lowest risk rate at 47.53%.

**4. Disruption Severity Analysis**
- 486 orders had no disruption.
- 248 orders experienced low-severity disruptions.
- 152 orders experienced medium-severity disruptions.
- 114 orders experienced high-severity disruptions.

**5. Financial Exposure Analysis**
- Shortage-related orders had the highest order value exposure at approximately $3.49 million.
- Weather-related disruptions accounted for approximately $3.22 million in order value exposure.
- These figures represent the value of affected orders, not confirmed financial losses.

## 💡 Business Recommendations

- Monitor high-risk suppliers and conduct regular supplier performance evaluations.
- Develop contingency plans for shortage-related disruptions.
- Review shipping strategies for rail and sea transportation.
- Strengthen supplier reliability monitoring.
- Track disruption severity and order delays regularly.
- Establish early-warning indicators to identify potential supply chain risks.

## 📊 Project Dashboards

### Excel Dashboard
[View Excel Dashboard](Excel/Supply%20chin%20risk%20analysis.xlsx)

### Tableau Dashboard

**Dashboard PDF:** [View PDF Dashboard](Tableau/Supply%20Chain%20Risk%20Analysis%20Dashboard.pdf)

**Dashboard Preview:** [View Dashboard Image](Tableau/Supply%20Chain%20Risk%20Analysis%20Dashboard.png)

**Tableau Workbook:** [Download TWB Workbook](Tableau/Supply%20Chain%20Risk%20Analysis.twb)

**Packaged Workbook:** [Download TWBX Workbook](Tableau/Supply%20Chain%20Risk%20Analysis.twbx)

## 📁 Repository Structure

```text
Supply_Chain_Risk_Analysis/
│
├── Data/
│   └── data.csv
│
├── Excel/
│   └── Supply chin risk analysis.xlsx
│
├── Tableau/
│   ├── Supply Chain Risk Analysis Dashboard.pdf
│   ├── Supply Chain Risk Analysis Dashboard.png
│   ├── Supply Chain Risk Analysis.twb
│   └── Supply Chain Risk Analysis.twbx
│
└── README.md
```

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Data cleaning and preparation.
- Exploratory data analysis.
- KPI calculation and business metrics.
- PivotTables and Excel dashboards.
- Tableau dashboard development.
- Data visualization and business insight generation.
- Translating analytical findings into business recommendations.

## 👨‍💻 Author

**Darshan Patel**

- GitHub: [darshanpatel-IT](https://github.com/darshanpatel-IT)
- LinkedIn: [Darshan Patel](https://www.linkedin.com/in/darshan-patel-a75124288/)

---

⭐ If you find this project useful, feel free to explore the dashboards and share your feedback.
