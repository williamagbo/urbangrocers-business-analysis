# UrbanGrocers Ltd Business Analysis

### 📝 Introduction
UrbanGrocers Ltd. is a large retail supermarket chain operating in multiple urban centers across Ghana. The company is struggling with high inventory costs, frequent stockouts, inefficient workforce management, and inadequate forecasting accuracy. Senior management is relying on you to develop predictive analytics solutions to dynamically manage inventory, optimize workforce allocation, and improve operational efficiency.

### 🧾 Datasets
Three years (Jan 2022 - Dec 2024) of daily data from 10 retail locations across Ghana, including:
- [Sales_Data.csv](data/raw/sales_data.csv)
- [Inventory_Data.csv](data/raw/inventory_data.csv)
- [Workforce_Data.csv](data/raw/workforce_data.csv)
- [External_Events.csv](data/raw/external_events.csv)

### 🔧 Analytics Tasks
#### 📊 Predictive Analytics Tasks
- Develop sales forecasting models using variables such as seasonality, promotions, weather, and external events.
- Predict optimal inventory levels accounting for demand fluctuations and lead-time variability.
- Build workforce optimization models to align staff allocation with sales performance trends.
- Create interactive dashboards using Power BI or Python Dash that reflect predictive insights in real-time.

#### ❓ Critical Business Questions
- How accurately can daily sales be predicted given external events, promotions, and weather patterns?
- What are the major predictive drivers of inventory wastage, and how can this be dynamically minimized?
- What staffing model best balances labor costs with meeting sales targets
- How can holidays and external events improve inventory forecasting accuracy?

#### 📦 Deliverables
- A comprehensive business report: UrbanGrocersLtd_Predictive_Analytics_Report.pdf
- A Power BI (.pbix) file and a Jupyter notebook (.pynb) file
	- [UrbanGrocers Dashboard](reports/powerbi/urbangrocers_dashboard.pbix)
	- [UrbanGrocers Jupyter Notebook](notebooks/urbangrocers.ipynb)
- The visualization dashboard includes visualizations of sales forecasts, inventory predictions, and workforce allocation models.

### 🔄 The Process
I used four main datasets spanning January 2022 to December 2024. My sales dataset captured daily transactions from ten retail locations, tracking timestamps, product IDs, quantities, and amounts. I collected inventory data on opening/closing balances, receipts, waste, supplier lead times, and costs. The workforce dataset recorded employee schedules, hours, shifts, roles, and attendance. I also incorporated external factors like weather conditions and public events—holidays, festivals, market days, and major sports events.

I built everything in Python using Pandas, Scikit-learn, Matplotlib, and XGBoost. For sales forecasting, I developed time series models that account for seasonality, promotions, weather, and events. My inventory optimization models calculate rolling demand averages, safety stock buffers, and optimal levels based on supplier variability. I used tree-based machine learning for workforce optimization, predicting staffing needs based on demand and external factors.

I created interactive Power BI dashboards that visualize all model outputs with dynamic filtering by store, date, product, weather, and event type. The dashboards support real-time decision-making across sales, inventory, and workforce operations.

### 📌 Findings and Conclusion
The report illustrates the transformational possibilities of predictive analytics and decision intelligence for UrbanGrocers’ operational challenges.
- Demand forecasting models reported, on average, demand was underestimated, usually considerably so, during significant events like holidays and festivals and identified areas to improve promotional planning and revolutionizing prediction of demand.
- Inventory analysis indicated unnecessary stock from inadequate lead times and incorrect order quantity and replenishment decisions.
- An analysis of labour identified chronic mismatches between the amount of scheduled hours, and optimal labour indicated both over and understaffing were near equal proportions across the organization.

