# sales-profit-discount-analysis
Sales, Profit and Discount analysis using Excel - Data Analysis Project
# 📊 Superstore Pricing & Discount Analysis

## 🔹 Project Objective

The goal of this project is to analyze how **product categories** and **discount strategies** affect **sales** and **profitability**.  
This analysis helps identify the categories and discount levels that generate the most profit and those which cause losses.

---

## 🗂️ Dataset Details

- **Source:** Superstore sales dataset  
- **Key Columns:** Category, Sales, Profit, Discount, Unit Price  
- **Tools Used:** Microsoft Excel (Pivot Tables + Charts)  

---

## 🔧 Data Preparation

- Cleaned missing values and standardized data  
- Grouped discounts into three categories:  
  - **Low:** 0–10%  
  - **Medium:** 10–20%  
  - **High:** 20%+  
- Created pivot tables for:  
  - Sales and Profit by Category  
  - Sales and Profit by Discount Level  
  - Profit by Category and Discount Level  
  - Average Unit Price, Discount, and Profit Margin by Category  
  - Overall Discount Margin Analysis  

---

# 📈 Analysis & Insights

---

## 1️⃣ Sales by Category

![Sales by Category](charts/Sales%20by%20Category.png)

| Category        | Sales (Millions) |
|-----------------|----------------|
| Technology      | 4.74           |
| Furniture       | 4.11           |
| Office Supplies | 3.78           |

### 🔍 Insights:

- Technology generates the **highest sales**  
- Furniture and Office Supplies follow  
- Technology is the main revenue driver  

---

## 2️⃣ Profit by Category

![Profit by Category](charts/Profit%20By%20Category.png)

| Category        | Profit (Millions) |
|-----------------|-----------------|
| Technology      | 0.66            |
| Furniture       | 0.28            |
| Office Supplies | 0.52            |

### 🔍 Insights:

- **Technology delivers the highest profit**  
- **Furniture shows the lowest profit**, indicating low margins  
- **Office Supplies** maintain moderate profit, better margins than Furniture  

**Business Interpretation:**  
Profit is not solely dependent on sales; Furniture requires a review of pricing strategy to improve margins.

---

## 3️⃣ Sales by Discount Level

![Sales by Discount Level](charts/Sales%20by%20Discount%20Categories.png)

| Discount Level | Sales (Millions) |
|----------------|----------------|
| Low (0–10%)    | 8.96           |
| Medium (10–20%)| 1.76           |
| High (20%+)    | 1.93           |

### 🔍 Insights:

- Low discounts generate the **highest sales**  
- High discounts contribute less to total sales  

**Business Interpretation:**  
Focusing on low discounts can maximize revenue.

---

## 4️⃣ Profit by Discount Level

![Profit by Discount Level](charts/Profit%20by%20Discount%20Categories.png)

| Discount Level | Profit (Millions) |
|----------------|-----------------|
| Low (0–10%)    | 2.11            |
| Medium (10–20%)| 0.17            |
| High (20%+)    | -0.81           |

### 🔍 Insights:

- **Low discounts maximize profitability**  
- **High discounts result in losses**, despite moderate sales  

**Business Interpretation:**  
Heavy discounting is harmful; controlled discounting ensures sustainable profitability.

---

## 5️⃣ Profit by Category & Discount Level

![Profit by Category and Discount Level](charts/Profit%20by%20category%20and%20discount%20levels.png)

| Category        | Low (0–10%) | Medium (10–20%) | High (20%+) |
|-----------------|------------|----------------|------------|
| Technology      | 835k       | 85k            | -257k      |
| Office Supplies | 697k       | 59k            | -238k      |
| Furniture       | 579k       | 28k            | -320k      |

### 🔍 Insights:

- All categories lose money under **high discount levels**  
- **Technology** performs best with low discounts  
- **Furniture** suffers the most from heavy discounts  

---

## 6️⃣ Category Pricing & Margin Analysis

| Category        | Avg Unit Price | Avg Discount | Profit Margin |
|-----------------|----------------|-------------|---------------|
| Technology      | 120.28         | 16.8%       | 5.0%          |
| Office Supplies | 35.49          | 13.7%       | 5.9%          |
| Furniture       | 135.84         | 13.5%       | 0.9%          |

### 🔍 Insights:

- Technology: highest sales and strong margin  
- Office Supplies: stable performer with consistent profit efficiency  
- Furniture: very low margin due to higher discounting  

**Business Interpretation:**  
Furniture pricing strategy needs review to improve profitability.

---

## 7️⃣ Discount Margin Impact

| Discount Level | Profit Margin |
|----------------|---------------|
| Low (0–10%)    | 25%           |
| Medium (10–20%)| 13%           |
| High (20%+)    | -61%          |

### 🔍 Insights:

- Heavy discounting causes **significant losses**  
- Controlled discounting ensures **sustainable profitability**

---

# 📌 Key Business Recommendations

- Focus on **low discount strategies (0–10%)** to maximize profits  
- Avoid **high discount campaigns** that lead to negative margins  
- Prioritize **Technology** category for promotions and inventory planning  
- Review **Furniture pricing strategy** to improve margins and reduce losses  
- Maintain **Office Supplies** as a stable profit contributor  

---

# 🎯 Conclusion

This analysis demonstrates that **profitability depends more on discount strategy than total sales**.  
By applying controlled discounts and focusing on high-performing categories, businesses can **significantly improve margins**, **reduce losses**, and make informed pricing and marketing decisions.

---

## 📎 Repository Structure

```markdown
superstore-pricing-discount-analysis/
├── Pricing_Profit_Analysis.xlsx           # Excel dataset with pivot tables
├── README.md                              # Project report and insights
└── charts/                                # Folder containing all chart images
    ├── Sales by Category.png              # Chart: Sales by Category
    ├── Profit by Category.png             # Chart: Profit by Category
    ├── Sales by Discount Categories.png   # Chart: Sales by Discount Level
    ├── Profit by Discount Categories.png  # Chart: Profit by Discount Level
    └── Profit by Category and Discount Level.png # Chart: Profit by Category & Discount Level
