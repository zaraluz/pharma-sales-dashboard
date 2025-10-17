# 💊 Pharmaceutical Sales Performance Dashboard — Power BI  

![Executive Summary](./EXECUTIVE%20SUMMARY.png)

---

## 🧠 Introduction  
This project presents an interactive dashboard built in **Power BI** to analyze pharmaceutical sales performance, sales team efficiency, and distributor/customer insights.  

The report focuses on **clarity**, **data storytelling**, and **strategic decision-making**, integrating Python-based exploratory analysis and a polished visual design.

---

## 🎯 Objectives  
- Centralize key sales indicators into a unified dashboard.  
- Evaluate sales performance by product, region, and team.  
- Identify top-performing distributors and customers.  
- Enable quick, data-driven business decisions.  

---

## ⚙️ Project Workflow  

### 1. **Data Collection & Cleaning**  
Raw data was imported from **CSV/Excel** sources and preprocessed using **Python (Pandas & NumPy)** for missing value treatment, outlier detection, and column normalization.  

### 2. **Exploratory Data Analysis (EDA)**  
A full EDA was performed in Python (see the `EDA_pharma.ipynb` notebook) to uncover sales patterns and distributions before the modeling phase.  
Key steps included:  
- Data type inspection and value consistency checks.  
- Correlation analysis between product sales, regions, and teams.  
- Seasonal and trend pattern identification.  
- Visualization using **Matplotlib** and **Seaborn** for initial insights.  

The EDA phase guided metric selection and shaped the DAX measures later used in Power BI.

### 3. **Data Modeling & Transformation**  
- Relationship modeling between fact and dimension tables.  
- Calculations with **DAX** for KPIs such as Total Sales, Average Discount, and Top Products.  
- Hierarchies and date relationships for drill-down analysis.  

### 4. **Dashboard Development**  
- Page-by-page layout design using consistent colors and visual hierarchy.  
- Interactive filters for year, month, region, and product categories.  
- Dynamic visuals for sales by region, channel, and team.  

### 5. **Design & Customization**  
- Custom headers created in **Canva/Figma** with transparent backgrounds.  
- Personal branding added: 🇧🇷 **Zara Louise | Data Analyst**.  
- Unified theme with soft green, mustard, and petrol blue palette.  

---

## 📊 Dashboard Structure  

### 🧾 **1. Executive Summary**  
![Executive Summary](./EXECUTIVE%20SUMMARY.png)  
- Overview of key performance indicators (KPIs).  
- Top-selling products, cities, and regions.  
- Year-over-year sales evolution.  

### 👥 **2. Sales Team Performance**  
![Sales Performance](./SALES%20PERFORMANCE.png)  
- Sales by representative, region, and product.  
- Top-performing teams and contribution percentages.  
- Ranking of best-selling categories.  

### 🏢 **3. Distributor & Customer Analysis**  
![Distributor and Customer Analysis](./DISTRIBUTOR%20AND%20CUSTOMER%20ANALYSIS.png)  
- Detailed view of distributors and key customers.  
- Channel breakdown (retail, hospital, etc.).  
- Regional contribution and customer segmentation.  

---

## 🧩 Tools & Technologies  
- **Python** — data preprocessing and EDA (`pandas`, `numpy`, `matplotlib`, `seaborn`).  
- **Power BI Desktop** — modeling, DAX calculations, and visualization.  
- **Excel / CSV** — source data files.  
- **Canva / Figma** — visual design and custom headers.  

---

## 🎨 Visual Design & Branding  
- Main font: **Segoe UI Semibold** (in visuals).  
- Title font: **Montserrat Bold** (exported as transparent PNGs).  
- Color palette: muted greens, petrol blue, and mustard tones for professional balance.  
- Soft shadows and rounded visuals for better readability.  

---

## 🔍 Key Insights  
- **Ionclotide** was the best-selling product overall.  
- The **Hospital** channel contributed the most to total revenue.  
- **Butzbach, Germany** recorded the highest sales by city.  
- The **Delta** sales team achieved the top overall performance.  

---

## 📈 Results  
The dashboard successfully integrates data engineering, EDA, and business visualization techniques.  
It enables users to:  
- Track performance at multiple levels (product, team, and customer).  
- Identify strategic growth opportunities.  
- Present actionable insights in an executive-friendly format.  

---

## 👩‍💻 Developed by  
**Zara Louise Luz Batista**  
*Data Analyst & Business Intelligence Professional*  
📍 Combining analytics, design, and storytelling to deliver business insight.  

---
