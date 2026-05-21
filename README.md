# 🛒 Retail Product Positioning — Data Analysis

Exploratory data analysis on a retail store dataset to uncover how product placement, category, pricing, and customer demographics drive sales — with actionable business recommendations for store managers and retail strategists.

---

## 📌 Problem Statement

Retail stores make constant decisions about *where* to place products and *who* to target. This project answers:

> *How does product positioning, category, and price point interact with customer demographics to influence sales volume and foot traffic?*

**Business impact:** Findings can directly inform shelf layout decisions, promotional strategies, and inventory planning.

---

## 📊 Dataset

- **Source:** Kaggle (public retail dataset)
- **Features:** Product category, store position (front/aisle/back), price, competitor price, sales volume, foot traffic, customer age group, seasonality indicators, ratings

---

## 🔍 Key Findings

### Product Category
- **Clothing** has the highest overall sales potential and volume
- **Food** has the lowest sales despite high ratings — prices are noticeably higher than competitors, which visibly suppresses volume
- Both **clothing and food** are highly seasonal; **electronics** are not

### Store Positioning
- Placing a product at the **front of the store does not guarantee high sales**
- **Aisle placement** consistently correlates with the highest sales volume

### Customer Demographics
- **College students** drive the most sales — they tend to buy decisively rather than browse
- **Families** have the highest foot traffic but do not convert to the highest sales
- **Young adults** have the lowest foot traffic and spending, with a preference for electronics
- **Seniors** also show a strong preference for electronics

---

## 📋 Business Recommendations

1. **Expand seasonal stock** — increase clothing and food variety around peak seasons
2. **Student electronics discount** — college students show interest; a targeted promotion could convert that into higher electronics sales
3. **Age-friendly electronics** — stock more accessible tech products to better serve the senior segment
4. **Reprice food** — current pricing is above competitors and is measurably hurting sales volume
5. **Prioritise aisle placement** for high-margin products over defaulting to front-of-store displays
6. **Lean into premium pricing** where it's already working — high-price products are performing well in certain categories

---

## 🛠️ Tech Stack

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Plotly`

---

## 📁 Project Structure

```
PRODUCT-POSITION-DATA-ANALYSIS/
│
└── DATA_ANALYSIS_PRODUCT_POSITIONING.ipynb   # Full EDA: loading → cleaning → visualisation → insights
```

---

## 💡 What This Project Demonstrates

- Translating raw data into **business language** — not just charts, but decisions
- Multivariate EDA across category, position, price, demographics, and seasonality
- Clear, structured recommendations a non-technical stakeholder could act on

---

## 👤 Author

**Navnee Sharma** — [LinkedIn](https://linkedin.com/in/navneesharma) | [navnee.sharma30@gmail.com](mailto:navnee.sharma30@gmail.com)
