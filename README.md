# Laboratory-Work1-Activity-PowerBI

# Verify Data in Data View
○ Are all columns visible?
  - Yes, you should be able to see all five columns: Region, Category, Year (or Date), Sales, and a unique identifier like Product Name
○ Is “Date” formatted as Date?
  - I’ve already formatted the Date column correctly
○ Is “Sales” formatted as Decimal Number?
  - Yes, the Sales column should be a Decimal Number so that the visuals can correctly calculate totals, like $220.23K.

# Quick Visualization
### Quick Visualization
![Quick Visualization](https://github.com/daisyjaneabasolo/Laboratory-Work1-Activity-PowerBI/blob/6ff2609e3e86f4f85a56c22a67b2b0eeae022e34/Quick%20Visualization.png)

# Answers to Questions
● What type of chart was created?
  - This is a Bar Chart.
● What does it show?
  - Total Sales: The chart represents the "Sum of Sales," which is the total amount of money made.

# Create a Sales by Region Chart
### Region Chart
![Region Chart](https://github.com/daisyjaneabasolo/Laboratory-Work1-Activity-PowerBI/blob/0038261cbef931c2a79377192d906d7bb832b5a3/Region%20Chart.png)

# Answers to Questions
● Which region has highest sales?
  - The West is the highest sales in the graph.

# Sales by Category
### Sales by Category
![Sales by Category](https://github.com/daisyjaneabasolo/Laboratory-Work1-Activity-PowerBI/blob/bfde732183fe7176fa9ab887e5db210bc4b0ad9b/Sales%20by%20Category.png)

# Answers to Questions
● Which category dominates?
  - Electronics is the largest part of the pie chart, with 90K in sales, making up 40.82% of the total.
● Is the distribution balanced?
  - The sales are not balanced. Office Supplies make up only 19.99% of sales, which is about half of the other two categories. Electronics (40.82%) and Furniture (39.19%) are almost equal, but the low sales of Office Supplies make the distribution uneven.

# Sales Over Time
### Sales Over Time
![Sales Over Time](https://github.com/daisyjaneabasolo/Laboratory-Work1-Activity-PowerBI/blob/670fd15e2e216c23848e8f898b89ab98f278c6ad/Sales%20Over%20Time.png)

# Answers to Questions
● Is there growth?
  - There is no growth. Sales went down a lot between the two years.
● Any noticeable trend?
  - The Sum of Sales by Year chart shows that sales are going down fast. Sales started high in 2024 at around 80K, but they dropped quickly in 2025 to just above 10K.

# Basic Data Insight Interpretation
# Question:
● Which region contributes most revenue?
  - The West region contributes the most revenue, totaling approximately $59,000.
● Which product category performs best?
  - The Electronics category performs the best, making $90,000 in sales, which is 40.82% of the total.
● Are sales consistent across dates?
  - No, sales are very inconsistent. They dropped a lot, from about $80,000 in 2024 to around $10,000 in 2025.
● What business recommendation can you suggest?
  - The most important action is to find out why sales dropped almost 87% in 2025. The business should also focus its marketing budget on the West and East regions, and on Electronics and Furniture, since these bring in the most sales.

# LABORATORY QUESTIONS
# Part A – Technical Questions
 1. What are the five columns in the dataset?
  - The charts show these columns: Region, Category, Year, and Sales. Usually, a dataset like this also has a fifth column, like Date or Product Name.
 2. What data type is assigned to the “Sales” column?
  - The Sales column is set as a Decimal Number. This is shown by the numbers (0K to 200K) and the fact that we can add or calculate them.
 3. Which Power BI view allows you to see raw data?
  - Data View in Power BI shows the raw data in a table, so you can see all the numbers and values clearly.
 4. What chart type is best for showing trends over time?  
  - A Line chart is the best type for showing trends over time, as demonstrated in the "Sum of Sales by Year" visual.
 5. What aggregation is automatically applied to Sales?
  - The Sum aggregation is automatically applied, as seen in the titles of all provided visuals like "Sum of Sales".

# Part B – Analytical Questions
 6. Which region has the highest total sales?
  - The West region has the highest total sales, reaching nearly $60,000.
 7. Which category has the lowest performance?
  - Office Supplies is the lowest-performing category, making up only 19.99% ($44K) of the total sales.
 8. Are sales increasing, decreasing, or stable?
  - Sales are decreasing. They fell from about $80,000 in 2024 to around $10,000 in 2025.
 9. If you were a manager, which region would you prioritize?
  - I would prioritize the North region for growth, as it is currently the lowest-performing region ($46K) and represents the largest opportunity for market expansion.
 10. Provide one actionable recommendation based on the data.
  - Investigate the drop in 2025 sales. Check right away why sales fell by about 87% in one year to avoid the business shutdown.

# Add a Card Visualization
### Card Visualization
![Card Visualization](https://github.com/daisyjaneabasolo/Laboratory-Work1-Activity-PowerBI/blob/5406d213b6b1934bdad20d5a241a6c677beb45a0/Card%20Visualization.png)

# Answers to Questions
● What is the total sales amount?
  - The total sales amount is 220.23K

# Add Slicer
### Add Slicer
![Add Slicer](https://github.com/daisyjaneabasolo/Laboratory-Work1-Activity-PowerBI/blob/034334b9d0bced4693fb38063371c433866ee5cc/Add%20Slicer.png)

# Answers to Questions
● What happens to other visuals when you click a region?
  - When you click East in the slicer, all the other charts automatically update to show only the East region’s data, including the total sales, category breakdown, and sales trend.
● Why is filtering important in BI?
  - Filtering is important in Business Intelligence because it helps users focus on relevant data, identify problems, understand specific details, and make clearer and faster decisions.

# Sort Sales
# Answers to Questions
● Does sorting improve readability?
  - Yes, sorting greatly improves a chart’s readability, especially in the Region Chart, because it organizes the data in a clear order, making comparisons easier to understand.
● Why?
  - In the "Sum of Sales by Region" chart, the bars are sorted in descending order (West, East, South, North). This allows the viewer to immediately identify the highest and lowest performers without having to scan back and forth.

# Identify Outliers
● Which region is significantly higher or lower?
  - The West ($59K) and East ($58K) regions are significantly higher, while the North ($46K) region is significantly lower.
● What might explain that difference?
  - The difference may be due to the West and East being more established markets with larger customer bases, stronger demand for popular products like Electronics, fewer stores or a smaller sales team in the North, or supply chain issues that impacted the North more than the other regions.
