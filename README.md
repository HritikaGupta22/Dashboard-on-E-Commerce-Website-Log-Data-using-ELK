# Dashboard-on-E-Commerce-Website-Log-Data-using-ELK

## About Dataset

#### Overview
This dataset contains log data from an e-commerce website, created for practicing exploratory data analysis (EDA) and data visualization. It captures detailed information about user interactions, demographics, and financial transactions. Analysts can explore patterns in website engagement, sales, and return rates to gain insights into user behavior and platform performance.

#### Features
- **Session Data**:
  - `duration_(secs)`: Duration (in seconds) for which the website was accessed.
  - `network_protocol`: Network protocol used (e.g., HTTP, HTTPS).
  - `ip`: IP address of the accessing user.
  - `bytes`: Total data (in bytes) transferred during the session.
  - `accessed_from`: Platform from which the website was accessed (e.g., mobile, desktop).

- **User Demographics**:
  - `age`: Age of the user.
  - `gender`: Gender of the user.
  - `country`: Country of the user.
  - `language`: Preferred language of the user.

- **Transaction Data**:
  - `membership`: Type of membership (e.g., free, premium).
  - `sales`: Total sales amount during the session.
  - `returned`: Whether the product was returned (`Yes`/`No`).
  - `returned_amount`: Value of returned items.
  - `pay_method`: Payment method used (e.g., credit card, PayPal).


The dataset offers a comprehensive view of user behavior, transaction patterns, and platform usage, making it suitable for analyzing engagement, sales trends, and return rates. It is ideal for understanding consumer behavior, platform performance, and revenue generation strategies in the e-commerce domain.

## Question on this data
#### **Sales and Revenue Analysis**
- **Trends Over Time**: How have sales evolved across different time periods?  
- **Geographic Contribution**: Which countries contribute the most to overall sales?  
- **Payment Methods**: What are the sales trends for different payment methods?  
- **Gender Comparison**: How do sales trends differ between male and female users?  
- **Membership Impact**: How do different membership types (free vs. premium) affect sales trends?  
- **Network Protocol Analysis**: Is there a relationship between network protocols and sales generated?  


#### **User Behavior Trends**
- **User Growth**: How has the number of users changed over time?  
- **Session Duration**: What is the average session duration for different age groups?  
- **Country Distribution**: How many users are present in each country?  
- **Data Usage by Browsers**: What is the total bytes consumption across different browsers?  
- **Demographic Insights**: What percentage of users are grouped by language and gender?  
- **Protocol Preferences**: How do users vary based on the network protocols they use?  



#### **Returns and Refunds**
- **Recent Returns**: How many transactions were returned in the last 30 minutes?  
- **Protocol Trends**: What is the trend of returned amounts by network protocol?  
- **Browser Insights**: What is the total returned amount for each browser?  



#### **Performance Metrics**
- **Peak Data Usage**: What are the peak hours for data usage, segmented by membership type?  
- **Country-Wise Consumption**: How is data consumption distributed across different countries?  
