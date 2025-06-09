## A/B Testing Marketing Campaign Performance
This project analyzes the performance of two marketing campaigns — a **Control Campaign** and a **Test Campaign** — using A/B testing principles to evaluate effectiveness in driving customer conversions.

## 🎯 Objective

To identify which campaign performs better at converting target customers through the sales funnel: from impressions to purchases. The goal is to provide clear, data-driven insights for improving marketing strategy and return on ad spend (ROAS).

## 🧾 Dataset Features

| Feature              | Description                                            |
|----------------------|--------------------------------------------------------|
| Campaign Name        | Name of the campaign (Control or Test)                |
| Date                 | Date of the campaign activity                         |
| Spend                | Amount spent on the campaign (USD)                    |
| Impressions          | Total number of ad views                              |
| Reach                | Unique number of users who saw the ad                 |
| Website Clicks       | Number of clicks to the website                       |
| Searches             | Website search actions by users                       |
| View Content         | Product/content views on the website                  |
| Add to Cart          | Number of users who added products to cart            |
| Purchase             | Final purchases made                                  |

---

## 📈 Key Metrics Analyzed

- Click-Through Rate (CTR)
- View Content Rate
- Add to Cart Rate
- Purchase Conversion Rate
- Cost per Purchase
- Return on Ad Spend (ROAS)

---

## 🧪 Methodology

- Data Cleaning & Preprocessing (Pandas)
- Metric Calculation & Aggregation
- Visualization (Seaborn, Matplotlib)
- A/B Statistical Testing:
  - Two-sample t-test for metric comparison
  - Chi-square test for conversion counts
- Insights and Recommendations

---

## 🛠️ Tools & Libraries

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy, Statsmodels
- VS Code
