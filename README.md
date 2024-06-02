# TATA Retail Store Analysis

## Table of Contents
- [Problem Statement](#problem-statement)
- [The Data](#the-data)
- [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Insights](#insights)
- [Recommendations](#recommendations) 



### Problem Statement
An online store faces challenges in its revenue data management which has hindered decision making and limited the ability to capitalise on business opportunities. Some of the key issues as communicated by the CEO/CMO, include:
- The region generating the highest revenue, and region with the lowest revenue.
- To determine monthly trend revenue and ascertain which months have faced the biggest increase/decrease.
- The months generated the most revenue, and to know if there is a seasonality in sales.
- Knowing the Top customers and how much they contribute to the total revenue.

### The Data
The dataset for this project was collected from [Forage](https://www.theforage.com/virtual-experience/MyXvBcppsW2FkNYCX/tata-group/data-visualisation-p5xo/framing-the-business-scenario). It comprises 53,1283 rows and 8 columns containing the following information:
- Stock Code
- Description
- Unit Price
- Customer ID
- Country
- Revenue
- Invoice Date

### Tools
- Power Query - Data Cleaning
- Power BI - Creating Visualization 

### Data Preparation
After downloading and opening the data in Power Bi, several steps were taken to ensure it was ready for analysis. Firstly, a new version of the data was created to preserve the original dataset. Then, the following actions were carried out:
- **Data type check:** The columns were reviewed to ensure they were assigned the appropriate data types. Where necessary, columns were converted to text or numbers.
- **Negative values:** The quantity column was reviewed to remove the negative values (below 1 unit), and removal of unit prices which were input in error (below $0).
- **Duplicate check:** No duplicate rows were found in the dataset.
- **Categorical variables:** All categorical variables were inspected for spelling errors or unexpected values. No issues were found.
- **Outliers:** No outliers were detected in the dataset.

### Exploratory Data Analysis
Once preparation was done, it was time for exploration and analysis, as such, the following were considered:
- What are the time series of the revenue data for the year 2011 only?
- What are the top 10 countries which are generating the highest revenue, excluding United Kingdom?
- Who are the top 10 customers generating revenue?
- Which of the countries have the highest demand of the products?

### Insights
1. **Total Revenue by Month:** We have revenue by month from January to December for the year 2011. November ranked the highest with the total of 1,509,496 revenue, while February is the least with 523,631 revenue. My analysis shows that there are some months of the year where exceptional growth is witnessed. The data shows that the revenue in the first 8 months is fairly constant as the average revenue generated for these 8 months is around $685k. The increase in revenue starts in the month of September, where the revenue increases by 40% over the previous month. This trend continues till the month of November where it reached 1.5 million USD, the highest during the entire year. The data is incomplete for the month of December, therefore, no conclusion can be drawn from it, unfortunately. This analysis shows that the retail store sales are impacted by the seasonality which usually occurs in the last 4 months of the year.

![Screenshot (411)](https://github.com/DanielOladipupo/TATA-Retail-Store-Analysis/assets/155446588/9922016b-0d82-4cec-a11c-4266f80a4ef7)

2. **Total Revenue and Total Quantity by Country:** Among the top 10 countries which is excludig United Kingdom, Netherland ranked the highest country with the highest revenue and qunatity amounting to 285,446 and 200,937 respectively, while the least country is Japan having 37,416 revenue, and 26,016 quantity. This shows how the top 10 countries which have opportunities for growth are performing. This data does not include the UK as the country already has high demand.The analysis shows that countries such as the Netherlands, Ireland, Germany and France have high volumes of units bought and revenue generated. 

![Screenshot (412)](https://github.com/DanielOladipupo/TATA-Retail-Store-Analysis/assets/155446588/8078e5af-cc5d-46b9-8697-94974568a77b)

3. **Total Revenue by Customer ID:** We have the Customer with the ID 14646 as the customer that generate more revenue, that is the greatest revenue generating customer with the total of 280,206, while Customer with the ID 12346 generate the least revenue amounting to 77,183. This has been performed on the top 10 customers who have purchased the most from the store. The data shows that there is not much of a difference between the purchasesmade by the top 10 customers. The highest revenue generating customer only purchased 17% more than the 2nd highest which shows that the business is not relying only on a few customers to generate the revenue. This shows that the bargaining power of customers is low and the business is in a good position.

![Screenshot (415)](https://github.com/DanielOladipupo/TATA-Retail-Store-Analysis/assets/155446588/65a70ffa-a583-48bc-8395-1f498487313b)

4. **Total Quantity by Country:**  The map chart shows the regions that have generated the most revenue compared withthe regions that have not. It can be seen that apart from the UK, countries such as Netherlands,Ireland, Germany, France and Australia are generating high revenue and the company shouldinvest more in these areas to increase demand for products. The map also shows that most ofthe sales are only in the European region with very few in the American region. Africa and Asia do not have any demand for the products, along with Russia. A new strategy targeting these areas has the potential to boost sales revenues and profitability.The Country with the highest quantity is Netherland with the total of 200,937, while USA is the least with 2,458.

![Screenshot (416)](https://github.com/DanielOladipupo/TATA-Retail-Store-Analysis/assets/155446588/782e919c-4a50-4fa1-849a-e271f8c252ee)

### Recommendations
- **Marketing Campaigns:** Given the significant increase in revenue from September to November, it is recommended to develop targeted marketing campaigns starting in late August. This will help capitalize on the seasonal uptick in sales.
- **Inventory Management:** Ensure that inventory levels are adjusted to meet the increased demand during these peak months. This might involve ramping up production or increasing stock levels in preparation for the high sales period.
- **Promotional Offers:** Introduce special promotions, discounts, and bundles during the peak months to further drive sales and maximize revenue.
- **Targeted Growth Initiatives:** Concentrate efforts on the Netherlands, Ireland, Germany, and France, where there is already substantial volume and revenue. This can include localized marketing campaigns, partnerships with local retailers, and tailored product offerings.
- **Customer Engagement:** Enhance customer engagement through loyalty programs, personalized communications, and localized customer service to build stronger relationships and drive repeat purchases.
- **Customer Retention:** Implement retention strategies such as loyalty programs, regular follow-ups, and personalized offers to maintain a steady revenue stream from the existing customer base.
- **Enhanced Analytics:** Invest in advanced data analytics tools to gain deeper insights into customer behavior, market trends, and operational efficiency. This will support better decision-making and strategic planning.



