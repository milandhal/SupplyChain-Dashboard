# SupplyChain-Dashboard
SupplyChain
🧾 Supply Chain Analytics – Demand, Inventory & Operations Optimization

Analyzing customer demand, procurement, production, and inventory performance to optimize supply chain efficiency using SQL, Python, and Power BI.

📌 Table of Contents
<a href="#overview">Overview</a>
<a href="#business-problem">Business Problem</a>
<a href="#dataset">Dataset</a>
<a href="#tools--technologies">Tools & Technologies</a>
<a href="#project-structure">Project Structure</a>
<a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
<a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
<a href="#research-questions--key-findings">Research Questions & Key Findings</a>
<a href="#dashboard">Dashboard</a>
<a href="#how-to-run-this-project">How to Run This Project</a>
<a href="#final-recommendations">Final Recommendations</a>
<a href="#author--contact">Author & Contact</a>
<h2><a class="anchor" id="overview"></a>Overview</h2>

This project analyzes end-to-end supply chain operations including customer demand, procurement, production, inventory, and sales performance. The goal is to identify inefficiencies and provide data-driven insights for better decision-making.

A complete pipeline was built using SQL for data transformation, Python for analysis, and Power BI for visualization.

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Supply chains often suffer from demand uncertainty, inefficient inventory usage, and operational delays. This project aims to:

Understand customer demand patterns over time
Optimize procurement and supplier performance
Align production with demand to avoid over/under production
Improve inventory management across facilities
Analyze investment vs revenue performance
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

The dataset consists of structured supply chain data with the following key fields:

Customer – End buyer information
Date – Transaction or activity timeline
Facility – Warehouse / production unit location
Product – Product category or item
Supplier – Vendor providing raw materials or goods
Inventory – Stock levels across facilities
Procurement – Purchase quantities and costs
Production – Units manufactured
Sales – Units sold and revenue generated
Investment – Operational and procurement investment
<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>
SQL (Joins, Aggregations, CTEs)
Python (Pandas, NumPy, Matplotlib, Seaborn)
Power BI (Interactive Dashboard & KPIs)
GitHub
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>
supplychain-analysis/
│
├── README.md
├── .gitignore
├── requirements.txt
├── Supply Chain Report.pdf
│
├── dashboard/
│   └── supplychain_dashboard.pbix
│
├── data/
│   └── supply_chain_data.csv
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>
Removed duplicate and inconsistent records
Handled missing values in sales, inventory, and procurement
Converted date column into proper datetime format
Standardized product and supplier names
Created derived metrics:
Inventory Turnover
Production Efficiency
Sales Growth Rate
ROI (Return on Investment)
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

Key Observations:

Demand fluctuates significantly across time periods
Certain facilities hold excess inventory while others face shortages
Production does not always align with sales demand
Some suppliers show inconsistent procurement patterns

Outliers Identified:

Extremely high inventory levels in specific facilities
Sudden spikes in procurement or production

Correlation Analysis:

Strong relationship between production and sales
Moderate link between procurement and inventory levels
Weak relationship between investment and profit in some cases
<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>
Demand Analysis: Customer demand shows seasonal variation
Inventory Efficiency: Overstock and stockouts observed across facilities
Production Alignment: Mismatch between production and actual sales
Supplier Performance: Some suppliers contribute to delays and inefficiencies
Investment Efficiency: Higher investment does not always yield higher returns
Facility Performance: Certain facilities outperform others in fulfillment
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>
Power BI Dashboard includes:
Customer Demand Trends
Inventory Distribution by Facility
Procurement vs Production Analysis
Sales & Revenue Insights
Supplier Performance Metrics
Investment vs ROI Analysis

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>
Clone the repository:
git clone https://github.com/yourusername/supplychain-analysis.git
Install dependencies:
pip install -r requirements.txt
Run data processing:
python scripts/data_processing.py
Open notebooks:
notebooks/exploratory_data_analysis.ipynb
notebooks/supply_chain_analysis.ipynb
Open Power BI Dashboard:
dashboard/supplychain_dashboard.pbix
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>
Align production planning with demand forecasting
Optimize inventory distribution across facilities
Improve supplier evaluation and procurement strategy
Reduce excess investment in low-performing areas
Implement data-driven decision-making for supply chain optimization
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

Milan Dhal
Aspiring Data Analyst / ML Enthusiast

Milan Dhal
Aspiring Data Analyst / ML Enthusiast

📧 Email: milandhal8@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/milan-d-a9a187361/
