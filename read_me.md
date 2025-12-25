# 🧾 BMW Sales Performance Analysis

-_Analyzing BMW Model Sales and Total Revenue using SQL, Python, and Power BI._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

<h2><a class="anchor" id="overview"></a>Overview</h2>

This project evaluates BMW Model Sales performance to drive strategic insights for purchasing and pricing. A complete data pipeline was built using SQL for ETL, Python for analysis, and Power BI for visualization.
---

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- CSV file located in `/data/` folder (BMW_sales_data_2010_2014)
- Summary table created from ingested data and used for analysis
---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- SQL (Common Table Expressions, Filtering)
- Python (Pandas, Matplotlib, Seaborn)
- Power BI (Interactive Visualizations)
- GitHub
---

h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
bwm-sales-analysis/
│
├── README.md
├── .gitignore
├── requirements.txt
│
│
├── scripts/                    # Python scripts for ingestion and processing
│   ├── bmw_sales.py
│
├── dashboard/                  # Power BI dashboard file
│   └── bmw_dashboard.pbix
```

---

<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. **Region**: Asia is the top continent for highest sales
2. **Top Model**: 7 Series is the top model in highest selling
3. **Sales Classification**: 7 Series is the only model whose sales classification is high
4. **Fuel Type**: Hybrid Model is highest demanding model
5. **Year Profitability**:
   - Top Year: 2022
   - Top Model in 2022: X5 Model

---
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

- Power BI Dashboard shows:
  - Top Highest Selling Model
  - Region wise Sales
  - Fuel _Type Model Sales
  - Top Selling Year

![bmw sales fdDashboard](images/bmw.png)

---
<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Load the CSVs and ingest into database:
```bash
python scripts/bmw_sales.py
```
2. Open Power BI Dashboard:
   - `dashboard/bmw_dashboard`
---
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Focus on Mileage and Price to increase selling
- Improve marketing for underperforming models

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Chander Mohan**  
Data Analyst  
📧 Email: raikwarmohan92@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/chander-mohan-bb3918313/)
