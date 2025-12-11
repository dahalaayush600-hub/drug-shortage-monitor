# Monitoring Drug Shortages to Improve Medicine Supply Chain

Drug shortages disrupt treatment plans, delay surgeries, and put patients at risk.  
Healthcare providers often lack early warnings or clear visibility into which medicines are becoming scarce.

This project analyzes FDA drug shortage data to uncover which drugs, therapeutic areas, and root causes drive the majority of shortages — helping inform better planning, purchasing, and policy decisions.

---

## What This Project Does

Using real-time FDA Drug Shortage API data, this project:

- Identifies the Top 10 drugs most frequently in shortage
- Highlights the therapeutic categories most impacted
- Breaks down the primary reasons for shortages, including manufacturing and supply chain issues
- Visualizes trends in shortages over time to spot spikes or recurring patterns

These insights help pharmacists, hospitals, and policymakers anticipate shortages earlier and improve the availability of critical medicines.

---

## Key Insights

- A small group of medicines accounts for a disproportionately high share of shortages, indicating systemic manufacturing pressure.
- Certain therapeutic categories, such as injectable medications and critical-care drugs, experience shortages more consistently.
- “**Other**” is the most common shortage reason, which reflects incomplete reporting and highlights a major transparency gap in the FDA data.
- Shortages tend to cluster in certain months, suggesting seasonal or operational bottlenecks.

Understanding these patterns provides a foundation for predicting and managing future shortages.

---

## Methodology

1. **Data Collection**  
   - Queried the FDA Drug Shortage API  
   - Saved raw and processed datasets in reproducible folders  

2. **Data Cleaning**  
   - Removed or standardized missing values  
   - Exploded list-based columns  
   - Converted all date fields to consistent formats  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized frequency of drug shortages  
   - Analyzed root causes  
   - Categorized shortages by therapeutic class  
   - Plotted monthly/annual trends  

4. **Insights & Interpretation**  
   - Identified implications for healthcare supply chains  
   - Highlighted data limitations and future expansion opportunities  



