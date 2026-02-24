# 📚 Amazon Bestselling Books Analysis
![Amazon Bestselling Books Analysis Theme](assets/amazon-bestselling-books-analysis.png)
> **Exploratory Data Analysis | Python & Data Storytelling**
> *Uncovering the market dynamics of top-performing literature on the world's largest bookstore.*

## 📌 1. Background and Overview
In the highly competitive e-commerce landscape, understanding what drives a "Bestseller" status is vital for authors and publishers alike. This project performs a deep-dive Exploratory Data Analysis (EDA) on a dataset of Amazon's top-selling books to identify the relationship between **pricing strategies, genre popularity, and customer sentiment**.

The goal is to move beyond simple statistics and answer: *How do price and genre influence customer engagement and satisfaction?*

---

## 📊 2. Data Structure & Initial Checks
The analysis was conducted on a curated dataset of Amazon Bestsellers containing **550+ records** with the following key attributes:
* **User Rating**: Customer satisfaction score on a 5-star scale.
* **Reviews**: Total count of customer reviews (Engagement metric).
* **Price**: Retail price at the time of bestseller status.
* **Genre**: Categorised into Fiction and Non-Fiction.

**Initial Quality Checks:**
* Handled missing values and verified data types using **Pandas**.
* Checked for duplicate entries to ensure unique book representation.
* Performed outlier detection on pricing and review counts to normalise visualisations.

---

## 🚀 3. Executive Summary
The analysis uncovered distinct market behaviours between genres:
* **Market Dominance**: **Non-Fiction** books represent a larger share of the bestseller list, indicating a high demand for informative and self-help content.
* **Engagement Levels**: While Non-Fiction is more frequent, **Fiction** books generate significantly higher customer engagement, with a **higher average review count** per book.
* **Pricing Elasticity**: User ratings remain consistently high regardless of price, showing that customers are willing to pay a premium for quality content without impacting their satisfaction.

---

## 🔍 4. Insights Deep Dive

### 📈 Engagement by Genre
* **Metric**: Total Review Count (Customer Engagement).
* **Story**: Fiction readers are more vocal. Despite having fewer titles on the bestseller list, Fiction books drive the most conversation, suggesting a more emotionally invested audience.
* ![Reviews vs Genre](assets/reviews_vs_genre.png)

### 💰 Price vs. User Rating
* **Metric**: Price-to-Rating Correlation.
* **Insight**: There is a **weak correlation** between price and rating. High-ticket books receive the same 4.5+ star ratings as budget-friendly options, proving that "value" in books is determined by content, not the price tag.
* ![Price vs Rating](assets/price_vs_rating.png)

### ⭐ Rating Consistency
* **Metric**: Mean User Rating.
* **Insight**: Bestsellers maintain a strict quality floor; 90% of the list maintains a rating above 4.3, regardless of the year or genre.

---

## ✅ 5. Recommendations
* **For Publishers**: Focus on the **Non-Fiction** category for higher volume (frequency) on bestseller lists, but invest in **Fiction** for high-engagement brand building.
* **For Authors**: Pricing is flexible. You do not need to "undercut" the market to maintain high user ratings; focus on quality to justify premium pricing.
* **Marketing Strategy**: Utilise the high review volume of Fiction books as "social proof" in ad campaigns to drive further conversions.

---

## 🛠️ 6. Tools & Technologies
* **Python**: Primary language for data manipulation.
* **Pandas & NumPy**: For efficient data cleaning and numerical analysis.
* **Matplotlib & Seaborn**: Creating "cute" and interactive visualisations to make data storytelling approachable.
* **Jupyter Notebook**: For documented, step-by-step exploratory analysis.

---

## 7. 📂 Project Structure
``` bash
- notebooks/ — exploratory data analysis  
- assets/ — saved visualisations  
- datasets/ — source data  
- README.md — project overview
```

---

## ⚠️ 8. Caveats and Assumptions
* **Timeframe**: The data represents a specific historical window; current trends may vary with the rise of digital-only "Kindle Unlimited" titles.
* **Market Bias**: The analysis is restricted to "Bestsellers" (top tier); findings may not apply to new or niche releases.

---

## 9. ✅ Project Status
Completed — Exploratory Data Analysis
---
