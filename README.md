PROJECT OVERVIEW
this project focuses on analyzing sales customer and operational data for a large retail
company goal is to support management decisions related to e-commerce expansion and physical store improvement by SQL analytical techiques
By applying SQL join and window funtion the analysis provide insights into product performence, customer purcharsing behavior and sales trends across different region and channel

OBJECTIVES
identify top-performing product by region and sales channel 
analyse customer buying patterns
evaluate sales growth trends over time 
provide data-driven recommendation for resource allocation

DATASET DESCRIPTION
sales data :product,revenue,month,region
customers data:customer id and total spending 
operational data: store and regional information

SQL CONCEPTS USED AND WINDOW FUNCTION
<img width="892" height="733" alt="image" src="https://github.com/user-attachments/assets/77a72d93-2b8b-4627-aec6-98811a1b8d28" />
<img width="926" height="795" alt="image" src="https://github.com/user-attachments/assets/ab3765bf-c728-4501-b303-ca15320f82f1" />
<img width="892" height="733" alt="image" src="https://github.com/user-attachments/assets/9734ab6d-a3a4-4563-9f51-66d587f0fa1f" />

SUCCESS CRITERIA &IMPLEMENTATION
identify top 5 product per region 
calculate running monthly sales totals 
funtion used :RANK()
OUTCOME:list of top 5 productcs by revevue in each region 
measure month-over -month growth
segment customers int quaritiles
function used :NTILE
OUTCOME:customers grouped four spending 
RESULTS ANALYSIS
descriptive analysis
the anyalysis shows that a small number of product and customers generate a large portion of total revenue sales generally increase over time with noticeable 
month-to-month variation and sesasonal patterns high speding custommers contribute the most to overall revenue

DIAGNOSTIC ANALYSIS
Top -performing product benefits from strong customers demadn and effictive placement across online physicalchannels revenue growth aligns with icreased
digital adoption and targeted reduced promotion or delayed store improvement 

PRESCRIPTIVE ANALYSIS
The company should prioritize high-revenue product and top-spending customers though personalized promotion and loyalty programs underperforming product should
be reviewedd for optimizztion or discontinuation a balance investment in digital platforms supply chain efficiency and physical store upgrades is recommended

TOOLS AND TECHNOLOGIES
SQL(Oracle,PostgreSQL,MYSQL,SQL serve)
window function
ER diagram

REFERENCES
Oracle corporation -oracle Database  SQL language reference 
POSTGRE global development group window funtion documentation 
 MYSQL 8.0  Reference manual window function 
 Microsft SQL sever analytical function 
 W3shcools -SQL JOIN and window funtion tutorial
 kimball ,R,and Ross.M(2013)then data warehouse toolkit





































