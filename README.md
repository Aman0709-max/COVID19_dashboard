# COVID19_dashboard

1. project objective(business problem)

The objective of this project is to analyze COVID-19 data to understand the spread, impact, and trends across different regions. 
The dashboard helps stakeholders monitor key metrics and make informed decisions based on real-time insights.

2. kpi & metrics(KPI indicator is a measurable value that shows how well a business or process is performing)

The following key performance indicators (KPIs) were created:
Total Confirmed Cases
Total Deaths
Total Recovered Cases
Active Cases
Death Rate (%)
Recovery Rate (%)
These KPIs provide a quick overview of the pandemic situation.

3.data sources and transformation


Data Source: Excel files containing COVID-19 data
Data Preparation:
Cleaned data using Power Query
Handled missing/null values
Standardized date formats
Structured and modeled data for analysis

4. dax and advanced features

Used DAX (Data Analysis Expressions) to create calculated measures:
Active Cases = Confirmed - Recovered - Deaths
Death Rate = (Deaths / Confirmed) × 100
Recovery Rate = (Recovered / Confirmed) × 100
Additional Features:
Data modeling relationships
Time-based analysis
 
5. visualization and story telling

Step 1: High-Level Summary (Top KPIs)

"At the top, we can see the overall impact — around 191M total cases, 529K new cases, and 4M total deaths. This gives a quick snapshot of the severity of the pandemic."

Step 2: Regional Impact (Pie Charts)

"Looking at the distribution by continent, we can see that regions like Europe and Asia contributed a significant share of total cases and deaths, indicating higher spread in these areas."

"This helps identify which continents were most affected."

Step 3: Country-Level Analysis

"At the country level, countries like the United States and India show the highest number of cases, highlighting them as major hotspots during the pandemic."

Step 4: Trend Over Time (Line Chart )


"The trend chart shows how cases increased over time, with noticeable peaks around 2021, representing major waves of COVID-19."

"For example, we can see a sharp rise in cases in countries like the United States and India, indicating rapid spread during specific periods."

Step 5: Additional Insights (Median Age Chart)

"The median age analysis across continents suggests that regions with higher median age might have experienced different impact patterns, possibly affecting severity and mortality."

Step 6: Final Insight (Conclusion)

"Overall, the dashboard highlights how COVID-19 spread globally, identifies the most affected regions and countries, and shows how the situation evolved over time."

Step 7: Business Impact

"This helps stakeholders identify high-risk regions, understand peak periods, and make data-driven decisions for better planning and response."
 

6. Business impact

This dashboard helps:
Identify high-risk regions
Track infection trends and peaks
Compare recovery and death rates
Support data-driven decision-making







Why I used these graphs?

Pie Charts (Continent-wise data)

"I used pie charts to show the proportion of total cases and deaths by continent, as they are effective for representing distribution and comparing shares."

Line Chart (Trend over time)

"I used a line chart to show the trend of COVID-19 cases over time, as it clearly highlights increases, peaks, and waves."

Bar/Area Chart (Country comparison)

"I used bar/area charts to compare total cases across countries, which makes it easy to identify top affected countries."

Scatter / Bubble Chart (Median age)

"I used this chart to analyze relationships, such as how median age varies across regions, helping to identify patterns."

KPI Cards

"KPI cards provide a quick summary of key metrics like total cases and deaths, so users can get insights at a glance."


