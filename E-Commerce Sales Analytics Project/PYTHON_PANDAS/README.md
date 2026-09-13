# 🛒 E-Commerce Sales & Profit Analysis (Superstore)

An end-to-end exploratory data analysis (EDA) of a US-based Superstore's retail data to uncover revenue drivers, profitability patterns, and segment-level insights using **Python, Pandas, and Plotly**.

---

## 🎯 Business Questions Answered

1. How do sales and profit trend across the 12 months?
2. Which product categories and sub-categories drive the most revenue?
3. Which customer segment is most profitable?
4. What is the Sales-to-Profit ratio per segment?
5. Where is the business losing money?

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.13** | Core analysis language |
| **Pandas** | Data cleaning, grouping, aggregation |
| **NumPy** | Numerical operations |
| **Plotly Express** | Interactive visualizations |
| **Plotly Graph Objects** | Custom dual-axis charts |
| **Jupyter Notebook** | Reproducible analysis environment |

---

## 📊 Key Insights

- 📈 **Q4 dominates revenue** — November (352K) and December (325K) are peak sales months.
- 🏆 **Technology leads profit** at **₹145.4K**, followed by Office Supplies (₹122.5K) and Furniture (₹18.4K).
- ⚠️ **Furniture is barely profitable** — despite ₹742K in sales, it only generates ₹18.4K profit (2.5% margin).
- 📉 **Tables and Bookcases are loss-making sub-categories**, dragging down Furniture's overall profitability.
- 👥 **Consumer segment has the highest Sales-to-Profit ratio (8.66)** — meaning it takes ₹8.66 of sales to generate ₹1 of profit vs ₹7.13 for Home Office.
- 💡 **Home Office is the most efficient segment** — lowest ratio = best profit conversion.

---

## 📸 Visualizations

| Chart | Insight |
|-------|---------|
| Monthly Sales (Line) | Clear Q4 spike |
| Sales by Category (Pie) | Technology > Furniture > Office Supplies |
| Sales by Sub-Category (Bar) | Phones & Chairs lead |
| Monthly Profit (Bar) | December peaks at ₹43.4K |
| Profit by Sub-Category (Bar) | Tables & Bookcases negative |
| Sales vs Profit by Segment (Dual Bar) | Consumer = highest volume, lowest efficiency |

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/dishant1305-star/Ecommerce-project.git

# 2. Install dependencies
pip install pandas numpy plotly jupyter

# 3. Launch the notebook
jupyter notebook E-commerce_project.ipynb