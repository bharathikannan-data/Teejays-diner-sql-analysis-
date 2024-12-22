# TeeJay's Diner: SQL Data Analysis

## 📖 Project Overview
TeeJay's Diner is a small restaurant specializing in sushi, curry, and ramen. This project uses SQL to analyze business data and generate actionable insights to enhance customer experience and business decisions.

### Goals:
- Understand customer visiting patterns.
- Identify the most popular and profitable menu items.
- Analyze customer spending habits.
- Optimize the loyalty program to drive engagement.

---

## 📊 Datasets
This project uses the following datasets:
1. **Sales**: Tracks all customer purchases (`customer_id`, `order_date`, `product_id`).
2. **Menu**: Provides details of products (`product_id`, `product_name`, `price`).
3. **Members**: Contains loyalty program data (`customer_id`, `join_date`).

### ER Diagram:
![ER Diagram](docs/ERD.png)

---

## 🔍 Key Analyses
- **Total Sales by Product**: Helps identify popular items.
- **Revenue by Product**: Reveals the most profitable menu items.
- **Non-Members**: Identifies customers to target for the loyalty program.
- **Orders After Membership**: Measures the success of the loyalty program.

Key SQL Queries are available in the [`queries/`](queries/) folder.

---

## 📈 Insights
Key insights from the analysis:
1. Ramen is the most ordered item.
2. Loyal customers spend significantly more than non-members.
3. Clear potential to expand the loyalty program to non-members.
4. Curry generates the highest revenue among menu items.

---

## 🛠️ Technologies Used
- **SQL**: Data analysis and query execution.
- **MySQL**: Database platform for SQL queries.
- **Microsoft PowerPoint**: To present findings.

---

## 🧰 Project Structure
- `datasets/`: Contains the raw data files (CSV format).
- `queries/`: Includes all SQL queries used in the analysis.
- `outputs/`: Contains the insights and visualizations derived from the analysis.
- `docs/`: Project documentation (e.g., ER diagrams, normalization details).
- `ppt/`: The PowerPoint presentation for this project.

---

## 📂 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/username/TeeJays-Diner-SQL-Analysis.git
   cd TeeJays-Diner-SQL-Analysis
