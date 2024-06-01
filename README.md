# TATA Retail Store Analysis

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
1. **Total Revenue by Month:** We have revenue by month from January to December for the year 2011. November ranked the highest with the total of 1,509,496 revenue, while February is the least with 523,631 revenue.

![Screenshot (411)](https://github.com/DanielOladipupo/TATA-Retail-Store-Analysis/assets/155446588/9922016b-0d82-4cec-a11c-4266f80a4ef7)

2. **Total Revenue and Total Quantity by Country:** Among the top 10 countries which is excludig United Kingdom, Netherland ranked the highest country with the highest revenue and qunatity amounting to 285,446 and 200,937 respectively, while the least country is Japan having 37,416 revenue, and 26,016 quantity.

![Screenshot (412)](https://github.com/DanielOladipupo/TATA-Retail-Store-Analysis/assets/155446588/8078e5af-cc5d-46b9-8697-94974568a77b)

3. **Total Revenue by Customer ID:** We have the Customer with the ID 14646 as the customer that generate more revenue, that is the greatest revenue generating customer with the total of 280,206, while Customer with the ID 12346 generate the least revenue amounting to 77,183.

![Screenshot (415)](https://github.com/DanielOladipupo/TATA-Retail-Store-Analysis/assets/155446588/65a70ffa-a583-48bc-8395-1f498487313b)

4. **Total Quantity by Country:** The Country with the highest quantity is Netherland with the total of 200,937, while USA is the least with 2,458.

![Screenshot (416)](https://github.com/DanielOladipupo/TATA-Retail-Store-Analysis/assets/155446588/782e919c-4a50-4fa1-849a-e271f8c252ee)



