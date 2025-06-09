# 🧥 Customer & URL Analytics for Men’s Fashion Retail

This project presents a comprehensive **data-driven analysis** of customer behavior and marketing channel performance for a men's fashion retailer, along with a **deep-linking investigation** for the Marks & Spencer Ireland website. It aims to optimize marketing strategy by identifying high-value demographics, refining acquisition channels, and enhancing campaign targeting through smart URL structures.

---

## 📊 Part 1: Data Analysis – Customer & Channel Insights

### 🎯 Objective

To determine **where and how the fashion retailer should focus its marketing efforts** by analyzing customer data across acquisition channels, demographic groups, and behavioral patterns.

---

### 📌 Key Findings

#### 1. **Channel Performance**
| Metric                  | Best Performing Channel    | Notes                                                                 |
|------------------------|----------------------------|-----------------------------------------------------------------------|
| ROI                    | ✅ Paid Search (ROI = 0.63) | Profitable – for every €1 spent, €1.63 is earned                     |
| CLV                    | ✅ Paid Social (€60.73)     | Highest long-term customer value                                     |
| Conversion Rate        | ✅ Paid Social (66%)        | Highly effective in converting visitors to repeat buyers             |
| Underperforming Channel| ❌ Affiliates               | Negative ROI and lowest CLV despite good conversion rate             |

**📌 Recommendation**:  
- Increase budget for **Paid Social**.  
- Optimize **Paid Search**.  
- Re-evaluate or reduce spend on **Affiliates**.

---

#### 2. **Demographic Differences**

- **Age 26–35** is the most profitable group (€603K total profit), followed by **36–45**.
- **Age 18–25** relies more on promotions.
- **Dublin** is the dominant market (> €1M in profit), with high multi-channel engagement.

**📌 Recommendation**:
- Target **26–45 age group** with retention and loyalty programs.  
- Focus Paid Social campaigns in **Dublin** and expand into **Galway/Cork** with regional offers.  
- Personalize offers for the **18–25 group** with seasonal promotions.

---

#### 3. **Customer Behavior**

- **Promotional Sensitivity**:
  - 17.85% of customers are high-promo users.
  - 82.15% are low-sensitivity and need non-discount incentives.

- **Churn Risk**:
  - High churn from **Direct** and **Organic Search**.
  - **Paid Social** and **Affiliates** bring more loyal customers.

**📌 Recommendation**:
- Send **targeted promotions** to high-sensitivity users.
- Offer **exclusive previews** and **early access** for low-sensitivity segments.
- Improve post-purchase experience and remarketing for **Organic Search** traffic.

---

### 🧪 Tools Used

- **Excel** (for customer segmentation, ROI/CLV calculations, churn analysis)
- **Python/Pandas** (optional for deeper analysis)
- Charts/visuals embedded in the accompanying workbook

---

## 🌐 Part 2: URL Deep-Linking Analysis – Marks & Spencer

### 🎯 Objective

Identify **11 direct, deep-link URLs** for shirts based on **fit** and **color** on the M&S Ireland site: https://www.marksandspencer.com/ie

---

### 🔍 URL Structure Summary

- URLs are dynamically generated using **filters**, not the search bar.
- Filtering by *Fit* (Regular/Slim) and *Color* (Blue, White, Green) produces unique paths.
- Each URL can include tracking data like `#intid=...` for campaign attribution.
