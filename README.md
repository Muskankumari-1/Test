# Business Optimization Power BI Dashboard (End-to-End | SQL Server Data Source)

## Problem Statement

Modern businesses generate large volumes of operational data, but without proper visualization, it becomes difficult to identify losses, shortages, and performance gaps.

This dashboard provides a comprehensive business performance overview, enabling decision-makers to:

-> Track total profit and total loss

->Monitor average daily loss

->Understand supply and demand patterns

->Identify product availability issues

->Detect total supply shortages

->Optimize operations using data-driven insights

The goal is to help businesses reduce losses, align supply with demand, and improve operational efficiency.


## Key KPIs Displayed
1. Financial Metrics

Total Profit: 22K

Total Loss: 97K

Average Daily Loss: 88.84

2. Supply & Demand Metrics

Average Demand per Day: 3.40

Average Availability per Day: 2.87

Total Supply Shortage: 579 units

These KPIs allow quick visibility into profitability and operational bottlenecks.

### Steps followed 

Step 1: Data Import

Loaded dataset into Power BI Desktop from CSV/Excel source.

Step 2: Power Query Data Cleaning

Checked column quality, distribution, and profile.

Removed blank or error rows.

Ensured correct data types for Date, Numeric, Category fields.

Step 3: Data Modeling

Created necessary relationships

Adjusted formats (decimal places, thousand separators)

Step 4: DAX Measures Created

Some key measures:

-Total Profit = SUM(Data[Profit])

Total Loss = SUM(Data[Loss])

Average Daily Loss = AVERAGE(Data[Daily Loss])

Average Demand Per Day = AVERAGE(Data[Demand])

Average Availability Per Day = AVERAGE(Data[Availability])

Total Supply Shortage = SUM(Data[Supply Shortage])

Step 5: Dashboard Design
Applied a dark modern theme with gradient cards.
Added KPI cards for high-level metrics.
Used consistent typography and spacing.
Applied a premium layout for professional appearance.
Placed brand identity section with:
 Logo
 Title: Insight BI
 Subtitle: Data Visualization for Business Optimization

Step 6: Publishing
Published the dashboard to Power BI Service.



# Insights

1. Profit vs Loss

Total Loss (97K) is significantly higher than Total Profit (22K).
 Indicates overall negative business performance — needs immediate intervention.

 2. High Average Daily Loss

Average daily loss of 88.84 shows operational inefficiency or demand-supply mismatch.

 3. Demand vs Availability

Average demand per day: 3.40

Average availability per day: 2.87

 Demand is consistently higher than availability → contributes to supply shortages.

  4. Supply Shortage

Total shortage is 579 units, signaling poor inventory planning or procurement delays.



           
## Conclusion

This dashboard helps business leaders:

Identify high-loss periods

Balance supply with demand

Reduce shortages through better forecasting

Improve profitability

Take corrective actions quickly using real-time metrics

It provides a holistic view of operational performance and enables data-driven decision making.

## Dashboard Snapshots

![Dashboard screenshot]((https://github.com/user-attachments/assets/c935438d-9fd5-471a-b2f4-b547246ab26e)
