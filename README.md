📊 Slooze Take-Home Challenge: Inventory, Purchase & Sales Analysis
📝 Project Overview

This project analyzes sales, purchases, and inventory data for a retail wine & spirits company.
The goal is to optimize inventory management, identify trends, and extract meaningful business insights.

The analyses include:

🔮 Demand Forecasting (Prophet time series model)

🏷️ ABC Analysis (categorizing inventory into A/B/C classes)

📦 Economic Order Quantity (EOQ) & Reorder Point (ROP)

⏳ Lead Time & Safety Stock Analysis

📉 Inventory Turnover & Slow Movers

📊 Profit Margin & Top Products

🚚 Supplier Efficiency Analysis

⚙️ How to Run

Clone this repository:

git clone https://github.com/<your-username>/Slooze_Inventory_Analysis.git
cd Slooze_Inventory_Analysis


Open the Jupyter Notebook:

jupyter notebook slooze.ipynb


Make sure required Python packages are installed:

pip install pandas numpy matplotlib seaborn prophet scikit-learn


Run all cells in the notebook.

📂 Repository Structure
Slooze_Inventory_Analysis/
│-- slooze.ipynb          # Main analysis notebook
│-- aging_inventory.csv   # Derived dataset - aging stock
│-- eoq_rop_data.csv      # EOQ and ROP results
│-- slow_movers.csv       # Slow-moving products
│-- top_margin_products.csv # High-margin products
│-- turnover_data.csv     # Inventory turnover insights
│-- README.md             # Project documentation

🚀 Insights & Outcomes

Identified top-performing products and slow movers.

Calculated optimal order quantities to reduce carrying costs.

Suggested safety stock levels to prevent stockouts.

Analyzed supplier efficiency and procurement lead times.

Built a forecasting model for future demand planning.
