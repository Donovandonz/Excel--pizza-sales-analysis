# Excel--pizza-sales-analysis
🍕 Pizza Sales Analysis &amp; Dashboard - Excel Project


## Dataset used
-<a href="https://github.com/Donovandonz/Excel--pizza-sales-analysis/blob/main/pizza_sales.csv">RAW.pizza-sales</a>

-<a href="https://github.com/Donovandonz/Excel--pizza-sales-analysis/blob/main/order_detail.csv">RAW.order-details</a>

---

## 📊 Project Overview

This interactive Excel dashboard analyzes pizza sales data to provide actionable business insights. The dashboard visualizes key performance indicators (KPIs), sales trends, and product performance to help stakeholders make data-driven decisions.

---

## 🛠️ Tools Used

- **Microsoft Excel**
  - Pivot Tables for data aggregation
  - Pivot Charts for visualization
  - Slicers for interactive filtering
  - Conditional Formatting for highlighting trends
  - Formulas for calculations (SUMIFS, COUNTIFS, AVERAGE, etc.)
 
---

## 📋 Dashboard Features

### Main KPIs
- Total Revenue ($801,944.70)
- Average Order Value ($16.18)
- Total Pizza Orders (48,620)
- Average Pizza Sold Per Order (1.02)

### Visualizations
1. **Daily Orders by Time of Day** - Bar chart showing order distribution across Morning, Afternoon, Evening, and Night
2. **Sales by Category & Size** - Analysis of pizza categories and their preferred sizes
3. **Pizza Sales by Category** - Breakdown of sales across Chicken, Classic, Supreme, and Veggie
4. **Top 10 Best Sellers** - Performance ranking of top-selling pizzas
5. **Top 10 Worst Sellers** - Identification of underperforming products

---

## A) 🔍 Key Insights

### 📈 Sales Performance
- **Total Revenue**: $801,944.70
- **Peak Hours**: Afternoon & Evening (12 PM - 8 PM) generate the highest order volume
- **Slow Periods**: Morning & Night show significantly lower sales

### 🏷️ Category Analysis
- **Top Categories**: Classic and Supreme pizzas contribute the highest sales
- **Preferred Sizes**: Large (L) and Medium (M) pizzas are most popular
- **Sales Distribution**: Balanced performance across Chicken, Classic, Supreme, and Veggie categories

### 🏆 Product Performance
- **Best Sellers**:
  1. The Classic Deluxe Pizza
  2. The Barbecue Chicken Pizza
  3. The Hawaiian Pizza
  4. The Pepperoni Pizza
  5. The Thai Chicken Pizza

- **Underperformers**:
  - The Brie Carre Pizza
  - The Mediterranean Pizza
  - Various specialty pizzas need marketing attention
 
## B) 🔍 Key Insights

### 📈 Sales Overview
- **Total Orders**: 48,620 (Annual)
- **Daily Average**: 133 orders per day
- **Peak Time**: Afternoon leads with 23,622 orders (65/day)
- **Secondary Peak**: Evening with 18,339 orders (50/day)

### 🕒 Orders by Time of Day
| Time Period | Annual Orders | Daily Average |
|-------------|--------------|---------------|
| Morning     | 2,693        | 7             |
| Afternoon   | 23,622       | 65            |
| Evening     | 18,339       | 50            |
| Night       | 3,966        | 11            |

### 📏 Size Analysis
| Size | Total Orders | % of Total | Top Category |
|------|-------------|------------|--------------|
| S    | 14,137      | 15.8%      | Classic      |
| M    | 15,385      | 17.2%      | Classic      |
| L    | 18,526      | 20.7%      | Veggie       |
| XL   | 544         | 0.6%       | Classic      |
| XXL  | 28          | 0.03%      | Classic      |

### 🏷️ Category Performance
| Category | Total Orders | Top Size |
|----------|-------------|----------|
| Classic  | 14,579      | S (5,975)|
| Supreme  | 11,777      | M (3,977)|
| Veggie   | 11,449      | L (5,263)|
| Chicken  | 8,849       | L (4,799)|
 
---

## 💡 Business Recommendations

Based on the analysis:
1. **Promote slow-hour sales** with morning/night specials
2. **Optimize inventory** for top-selling pizzas (Classic Deluxe, BBQ Chicken)
3. **Consider menu optimization** for consistently underperforming items
4. **Bundle deals** combining best sellers with slower-moving inventory
5. **Target marketing** during peak hours (afternoon/evening) for maximum ROI

---

## Detailed Analysis

### Pizza Size & Category Analysis Report

## Overview
This report analyzes one year of pizza sales data (48,620 total orders) to understand customer preferences across different sizes and categories.

## 1. Size Analysis by Time of Day

### Morning (2,693 total orders)
| Size | Orders | % of Morning |
|------|--------|--------------|
| L    | 1,016  | 37.7%        |
| M    | 859    | 31.9%        |
| S    | 777    | 28.9%        |
| XL   | 38     | 1.4%         |
| XXL  | 3      | 0.1%         |

### Afternoon (23,622 total orders)
| Size | Orders | % of Afternoon |
|------|--------|----------------|
| L    | 9,021  | 38.2%          |
| M    | 7,466  | 31.6%          |
| S    | 6,878  | 29.1%          |
| XL   | 243    | 1.0%           |
| XXL  | 14     | 0.1%           |

### Evening (18,339 total orders)
| Size | Orders | % of Evening |
|------|--------|--------------|
| L    | 7,000  | 38.2%        |
| M    | 5,784  | 31.5%        |
| S    | 5,331  | 29.1%        |
| XL   | 215    | 1.2%         |
| XXL  | 9      | 0.05%        |

### Night (3,966 total orders)
| Size | Orders | % of Night |
|------|--------|------------|
| L    | 1,489  | 37.5%      |
| M    | 1,276  | 32.2%      |
| S    | 1,151  | 29.0%      |
| XL   | 48     | 1.2%       |
| XXL  | 2      | 0.1%       |

## 2. Category Analysis by Size

### Size S (14,137 orders)
| Category | Orders | % of S Size |
|----------|--------|-------------|
| Classic  | 5,975  | 42.3%       |
| Supreme  | 3,323  | 23.5%       |
| Veggie   | 2,634  | 18.6%       |
| Chicken  | 239    | 1.7%        |

### Size M (15,385 orders)
| Category | Orders | % of M Size |
|----------|--------|-------------|
| Classic  | 4,045  | 26.3%       |
| Supreme  | 3,977  | 25.9%       |
| Chicken  | 3,811  | 24.8%       |
| Veggie   | 3,552  | 23.1%       |

### Size L (18,526 orders)
| Category | Orders | % of L Size |
|----------|--------|-------------|
| Veggie   | 5,263  | 28.4%       |
| Chicken  | 4,799  | 25.9%       |
| Supreme  | 4,477  | 24.2%       |
| Classic  | 3,987  | 21.5%       |

### Size XL (544 orders)
| Category | Orders |
|----------|--------|
| Classic  | 544    |

### Size XXL (28 orders)
| Category | Orders |
|----------|--------|
| Classic  | 28     |

## 3. Key Findings

### Most Popular Combinations
1. **Classic (S)** : 5,975 orders - Best performing combination
2. **Veggie (L)** : 5,263 orders - Top large-size performer
3. **Chicken (L)** : 4,799 orders - Strong evening preference
4. **Supreme (M)** : 3,977 orders - Balanced across time periods

### Least Popular Combinations
1. **Chicken (S)** : Only 239 orders - Avoid promoting
2. **Classic (XXL)** : Only 28 orders - Consider removing
3. **Classic (XL)** : 544 orders - Low volume

## 4. Strategic Recommendations

### Menu Optimization
- Keep **S, M, L sizes** for all categories
- Consider **removing XL and XXL** or make them special order only
- Add **Chicken options in S size** to boost performance

### Marketing Focus
- Promote **Classic (S)** for lunch specials
- Target **Veggie (L)** for family dinner deals
- Bundle **Chicken (L)** with sides for evening promotions

### Inventory Planning
- Stock more **Classic ingredients** for S size
- Prepare for **Veggie demand** in L size
- Reduce **XL and XXL** ingredient orders

### Opportunities
- **Underperformers**: 10 pizzas contribute less than 5% of revenue
- **Slow Hours**: Morning and Night represent untapped potential
- **Bundle Potential**: Combine top sellers with underperformers

### Action Plan
1. Implement "Morning Special" promotions
2. Review menu for bottom 5 performers
3. Create combo deals for XL/XXL sizes
4. Highlight top sellers in marketing materials
5. Analyze customer feedback for underperformers
