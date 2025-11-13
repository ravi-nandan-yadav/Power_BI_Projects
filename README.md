📊 U.S. Heavy Haul Truck Market – Power BI Dashboard & Forecasting Analysis

This project presents a complete end-to-end analysis of the U.S. Heavy Haul Truck Market, starting from raw data forecasting in Excel to building an interactive analytics dashboard in Power BI. The goal is to visualize market trends, segment performance, and future growth insights for decision-making.

🔧 Project Workflow
1. Data Preparation (Excel)

Cleaned and structured historical U.S. heavy haul truck market data.

Applied forecasting logic to estimate market size for upcoming years.

Performed segment-wise and region-wise breakdowns.

Ensured consistency across units, categories, and year formats.

2. Forecasting Model

Used a time-series–based forecasting method to estimate future market values.

Calculated YoY growth, CAGR, and future demand outlook.

Built segment-level projections for better market understanding.

📊 Power BI Dashboard Overview
Key Visuals & Insights

Market Size Trend (Historical + Forecast)
Line chart showing actual vs. forecasted values.

CAGR & YoY Growth KPIs
KPI cards to highlight overall market performance.

Segment-wise Revenue Breakdown
Bar/column charts comparing different heavy haul truck segments.

Regional Market Distribution (U.S.)
Map or bar chart showing state/region dominance.

Future Market Projection
Forecast chart highlighting growth trajectory.

🧮 DAX Measures Used

(Adjust these if yours differ)

Total Market Size = SUM(Market[Value])

YoY Growth = DIVIDE([Current Year] – [Previous Year], [Previous Year])

Forecast Value (Custom Measure)

**CAGR = ( (End/Start) ^ (1/Years) ) – 1 **

Segment Contribution % = DIVIDE([Segment Value], [Total Market Size])

🎯 Purpose of This Dashboard

To give stakeholders a clear, interactive view of the U.S. heavy haul truck market, including historical trends, segment performance, and future demand potential. This dashboard helps in strategic planning, investment decisions, and industry forecasting.

🛠 Tools Used

Microsoft Excel → Data cleaning + forecasting

Power BI Desktop → Data modeling + DAX + dashboard

Power Query

DAX Measures
