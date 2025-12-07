# Coke-Sales-Analysis

This project focuses on analyzing Coca-Cola sales data across key American retailers using Excel. The objective is to extract actionable insights from transactional and operational metrics like total sales, units sold, and operating margin. The analysis dives into regional performance, retailer efficiency, and sales trends to identify areas of strength and opportunities for improvement.
The analysis aims to understand:
How Coca-Cola sales vary by retailer, region, and time
The relationship between pricing, volume, and profitability
Trends in operating margins across different markets


We analyze transactional data from thousands of retail locations to understand how sales performance varies by retailer, region, and product.We look at how price per unit affects both units sold and total revenue, and we explore operating margins to identify which markets are strong and which ones need improvement.By combining these insights, the goal is to help Coca-Cola focus investment on high-performing regions, adjust pricing strategies where needed, and improve overall profitability across the retail network.

Data Understanding & Preparation
Describe the structure and key features of the dataset?
The dataset is a collection of Coca-Cola sales records from different U.S. retailers. Each row shows where the product was sold, which brand it was, how many units were sold, the price per unit, the total sales amount, and the operating profit
Demonstrate data cleaning and standardization processes?
To prepare the data for analysis, we first clean and organize it. This helps make sure all the numbers and names are correct before we start working on them.
Fix column names--We make all column names clear and consistent so they are easy to understand.
Check for missing values--If any important information is empty—like units sold or price—we either fill it in using averages or remove the row.
Correct data types--Some numbers may be stored as text. We convert everything into the right format so calculations work properly.
Remove duplicate rows--If the same row appears more than once, we delete the extra copies.
Fix wrong or strange values--We look for mistakes like negative units or incorrect sales amounts and correct them.
Standardize names--Sometimes the same retailer is written in different ways. We make all names consistent—for example, changing “WALMART” and “Wal-Mart” to “Walmart.”Recalculate important metrics --We make sure totals are correct by checking that:Total Sales = Units Sold × Price per Unit
Justify choices for filtering or transformation
We apply filtering and transformations to make the data more reliable and easier to analyze. These steps help remove noise and focus only on information that supports accurate insights.
Filtering out incomplete or wrong data--Rows with missing or incorrect values can give false results. By removing or fixing them, we make sure our analysis is based on proper information.
Filtering by date or region--Sometimes we only want to study a specific time period or region. Filtering helps us focus on the part of the data that matches our business question.
Transforming values into the right format--We convert text to numbers, fix date formats, and standardize names so calculations and charts work correctly.
Recalculating metrics--We calculate fields like Total Sales or Operating Margin to maintain consistency. This helps us compare retailers and regions more fairly.
Standardizing categories--Cleaning and standardizing product names or retailer names avoids confusion and prevents duplicates in analysis.
Exploratory Data Analysis (EDA)
Explore sales patterns across geography and time
To understand how Coca-Cola performs in different parts of the U.S., we look at sales across both geography and time.
1. Geographic Patterns--We compare sales across regions such as the West, Midwest, South, and Northeast. This helps us see which areas have strong demand and which areas may need more attention. By looking at units sold, total sales, and operating profit, we can quickly identify high-performing regions and spot regions where sales are low or profit margins are weaker.
2. Retailer Performance by Region--Some retailers may perform better in certain regions. For example, Walmart might sell more in the South, while Target performs better in the West. These geographic differences help Coca-Cola plan distribution and marketing more effectively.
3. Time-Based Patterns--We look at monthly or weekly sales trends to understand how demand changes over time. Line charts help us see whether sales increase during certain months—such as summer—or drop during the winter. This reveals seasonal patterns and peak periods.
4. Combining Geography and Time--By analyzing both together, we can see which regions grow faster over time and which ones remain stable. For example, sales might rise sharply in the West during summer but stay steady in the Midwest.
Use visual tools to identify trends, spikes, or anomalies
To better understand the sales data, we use visual tools in Excel. These visuals make it easier to spot patterns that might be hard to see in raw numbers.
1. Line Charts for Trends--We use line charts to track monthly sales and profit over time.This helps us quickly see whether sales are going up, going down, or staying steady across the year.
2. Bar Charts for Comparing Retailers and Regions--Bar charts make it easy to compare sales between different retailers or regions.They help us identify which retailers consistently perform well and which ones are falling behind.
3. Heatmaps for Regional Insights--Conditional formatting heatmaps show shades of color based on performance.Darker colors indicate higher sales or margins, helping us visually spot strong and weak areas across the U.S.
4. Pivot Charts for Deep Exploration--Pivot charts allow us to filter by month, retailer, or region.By adjusting the filters, we can see when a spike happened, which area caused it, and whether it is normal or unusual.
Surface preliminary insights that guide deeper analysis
After exploring the data with charts and summaries, we start to notice early patterns. These preliminary insights help us decide what areas need deeper investigation.
1. Regional Differences--We may see that some regions, like the South or West, have much higher sales than others. This tells us we should explore what is driving the strong performance—such as higher demand, better retailer partnerships, or larger population.
2. Retailer Performance Patterns--Early charts might show that retailers like Walmart or Costco consistently have higher sales. This insight encourages a closer look at why these retailers perform better—maybe due to pricing, store size, or customer traffic.
3. Seasonal Trends--Line charts might show sales rising in the summer months. This early pattern suggests we should check how temperature, holidays, or promotions influence demand.
4. Profitability Issues--We may notice that some locations have high sales but low profit margins. This insight tells us to explore cost structures, pricing strategies, or operational inefficiencies.
5. Outliers or Unexpected Values--If we spot sudden spikes or drops in sales, it signals that something unusual happened. This could be a promotion, a holiday, or an error in the data. These points help guide where to double-check or explore further.
Apply descriptive statistics and Excel formulas to dissect key metrics
Descriptive statistics help you summarize and understand your data. For Coca-Cola sales, this means looking at numbers to see patterns like which stores sell the most or which months have higher sales.
Total Sales – How much money each store or product made.
Average Sales – Typical sales for a store, product, or month.
Maximum & Minimum Sales – Best and worst sales figures.
Count – How many transactions, stores, or products are in the dataset.
Use comparisons, groupings, and aggregations to evaluate performance
Compare – Look at numbers side by side to see which store, product, or month is doing better or worse.Example: Compare sales of Store A vs Store B.
Group – Combine data by category to make analysis easier.Example: Group sales by region or product type.
Aggregate – Add, average, or summarize data to see overall performance.Example: Total sales per region, average sales per product.
Excel tools: SUM, AVERAGE, MAX, MIN, Pivot Tables
Justify analytical approach and interpret results in context
Justify Analytical Approach
Why use descriptive statistics, comparisons, and grouping?
To summarize large data quickly.
To identify top-selling products, stores, or regions.
To spot trends, patterns, and anomalies that guide business decisions.
Why Excel formulas and Pivot Tables?
They are fast, simple, and visual, making it easy to analyze and present results.
Interpret Results in Context
Look at your numbers and summaries and ask:
Which products or stores are performing best?
Are there months with unusually high or low sales?
Are there regions that need more focus or support?
Example:“Store A has the highest total sales, so marketing efforts there are working well.”
“Sales drop in July across all regions, so we might plan promotions during that month.”
Translate findings into actionable business recommendations
1. Price differently in each region
Northeast: Prices can stay high (people pay more).
South & West: Lower prices a bit to sell more.
2. Push top sellers
Coca-Cola and Dasani Water make the most money.
Stock more of these in stores.
3. Fix weaker products
Fanta and Powerade sell poorly in some places.
Try new flavors or promotions in those areas.
4. Get ready for summer
Sales jump in June–August.
Run ads and promotions before summer starts.
5. Work closely with stores
Sodapop: Do joint ads (they give good profit).
BevCo: Offer deals for buying in bulk.
Western stores: Talk often to improve what’s on shelves.
6. Watch your profit per product
Not all products make good money.Focus on those that do (like Dasani in the South).
Simple plan:Charge more where you can.Sell more of what’s profitable.Promote ahead of hot seasons.Talk to stores and adjust together.
Link insights directly to Coca-Cola’s retail and sales strategy
What Coca-Cola should do:
Charge more in the Northeast — people will pay it.
Charge less in the South — sell more bottles.
Put Coca-Cola and Dasani Water in the front — they make the most money.
Start summer ads in May — before it gets hot.
Give special drinks to some stores, bulk deals to others.
Help weaker drinks like Fanta sell better in slow areas.
Watch which drinks make money, not just which sell fast.
This will help sell more, make more money, and keep stores happy.
Highlight impactful data points and explain their implications
New York = High profit area. Keep prices high there.
Texas = Sell lots of Dasani Water. It makes great money.
West Coast = Fanta & Powerade sell poorly. Try new flavors or bundles.
Summer = Sales boom. Start ads and stock up early.
Prices should change by region. Don’t charge the same everywhere.
Dasani is a money-maker — especially in the South. Put it in more coolers.
Some slow sellers still make good profit — don’t drop them too fast.
Communication & Storytelling
Present a logical and clear narrative from data to insights
By analyzing Coca-Cola’s 2021 U.S. retail sales data across five major retailers, we uncovered clear patterns in regional pricing, product performance, and seasonal trends. New York customers respond well to premium pricing, while Texas favors bulk, low-price purchases. High-margin products like Dasani Water drive profitability, even as some brands such as Fanta and Powerade underperform in specific markets. Sales consistently peak during summer months, providing predictable revenue opportunities, and retailer performance varies, requiring tailored strategies. These insights show that Coca-Cola’s success comes not from a single approach but from managing regional differences, product portfolios, seasonal trends, and retailer-specific strategies—allowing the company to make targeted decisions that maximize profits and growth.
