This project performs a comprehensive analysis of India's banking payment infrastructure and transaction behavior using official data from the Reserve Bank of India (RBI). The analysis explores how different types of banks—Public, Private, Foreign, Payment, and Small Finance—operate across digital and physical banking channels.

Using Python for exploratory data analysis, MySQL for deeper querying, and Power BI for visualization, the project uncovers trends in ATM networks, card usage, digital payment adoption, and infrastructure efficiency across the Indian banking ecosystem.

The repository includes the processed dataset, analysis notebooks, and a Power BI dashboard used to generate insights.



Project Overview
1. Banking infrastructure data was collected from RBI’s official statistics portal and cleaned for analysis.
2. Exploratory Data Analysis was conducted to understand relationships between banking infrastructure (ATMs, PoS terminals, QR codes) and transaction behavior.
3. Comparative analysis was performed across different bank types to identify differences in digital adoption, card usage, and infrastructure utilization.
4. SQL queries were used to validate Python findings and perform deeper aggregations and efficiency calculations.
5. A Power BI dashboard was built to present insights in an interactive and interpretable format.



Repository Structure
1. bank_data.csv - Cleaned dataset derived from RBI’s bank-wise ATM, PoS, and card transaction statistics.
2. bank_analysis.ipynb - Jupyter notebook containing data preprocessing, exploratory data analysis, visualizations, and insight generation using Python.
3. bank_dashboard.pbix - Power BI dashboard visualizing transaction volumes, digital adoption trends, and infrastructure comparisons across banks.



Technologies Used
1. Python – Pandas, Matplotlib
2. MySQL – Data querying and validation
3. Power BI – Dashboard visualization and reporting
4. Jupyter Notebook – Data analysis and experimentation



Analysis Workflow
1. Data Collection from RBI banking infrastructure statistics
2. Data Cleaning and Preparation using Python
3. Exploratory Data Analysis and Visualization
4. SQL Query Analysis for validation and deeper insights
5. Infrastructure Efficiency and Transaction Pattern Analysis
6. Interactive Dashboard Development using Power BI



Key Insights
1. Private and foreign banks show significantly higher digital adoption compared to public sector banks.
2. Public sector banks dominate physical banking infrastructure such as ATM networks and debit card issuance.
3. Credit card usage drives higher transaction values despite lower card volumes compared to debit cards.
4. Foreign banks handle fewer transactions but significantly higher average transaction values due to premium customer segments.
5. Several large banks maintain underutilized ATM networks, reflecting the shift toward digital payment channels.
6. PoS and card ecosystems have the strongest correlation with overall transaction activity across banks.



Results

The analysis reveals a clear structural divide in India's banking ecosystem. Public sector banks provide broad infrastructure coverage and financial inclusion, while private and foreign banks lead digital payment innovation and transaction efficiency.

By combining Python analytics, SQL querying, and Power BI visualization, this project delivers a complete end-to-end analysis pipeline that transforms raw infrastructure data into actionable insights about India's evolving digital banking landscape.
