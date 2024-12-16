# Dashboard-on-E-Commerce-Website-Log-Data-using-ELK
## Methodology
The dataset has taken from Kaggle(https://www.kaggle.com/datasets/kzmontage/e-commerce-website-logs/data). The dashboard is constructed using ELK in Kibana. 

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

#### **General Questions **
- **What is Total Sales?**
- **What is Average Duration(secs)?**
- **What is the most occurence IP Address?**
- **What is the Total Returned Amount?**
  
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


## Dashboard

https://github.com/user-attachments/assets/300ec9c6-59ba-4bd0-8249-54281dcba083


## Interpretations

#### **Sales and Revenue Analysis**
- **Top Contributing Countries**: The United States, Canada, the United Kingdom, Germany, and France are the largest markets for sales, indicating high engagement in these regions.  
- **Payment Preferences**: Credit card is the most popular payment method, followed by cash and debit card, reflecting a strong preference for digital payment options.  
- **Gender Distribution**: Sales are nearly evenly split between male (49.92%) and female (50.08%) users, highlighting broad gender appeal.  
- **Membership Types**: Most sales come from "Normal" membership users, followed by "Premium" members, indicating the standard service offering is widely preferred.  
- **Network Protocol Trends**: HTTP and TCP protocols dominate sales across accessed websites like Android_App, Chrome, and IOS_App, emphasizing the need for optimized performance on these channels.  

---

#### **User Behavior Trends**
- **User Growth**: The number of users has steadily increased over time, with significant peaks signaling growing interest and adoption.  
- **Session Duration**: Users aged 30-40 exhibit the longest session durations, showing high engagement within this demographic.  
- **Top User Locations**: User distribution mirrors sales trends, with the United States, Canada, the United Kingdom, Germany, and France leading.  
- **Data Consumption by Platforms**: Android_App and Chrome browsers are the highest data consumers, highlighting the need for optimization for these popular platforms.  
- **Language Preferences**: English is the predominant language, with 36.85% of female and 24.81% of male users favoring it, suggesting a strong focus on English-speaking markets.  
- **Network Protocol Usage**: The TCP protocol has the highest number of users, followed by HTTP and ICMP, requiring a focus on reliability and performance for TCP-based services.  

---

#### **Returns and Refunds**
- **Return Rate**: Most transactions were not returned, indicating high customer satisfaction.  
- **Protocol-Specific Returns**: UDP protocol has the highest returned amount, followed by TCP and HTTP. Analyzing UDP-specific issues could uncover opportunities to reduce returns.  
- **Platform-Specific Returns**: Android_App and Chrome browsers have the highest returned amounts. Addressing user experience issues on these platforms can help minimize returns.  

---

#### **Performance Metrics**
- **Data Usage Peaks**: "Normal" membership users show the highest data usage peaks, signifying they are the most active consumer group.  
- **Regional Consumption**: North America and Europe lead in data consumption, aligning with their dominance in user count and sales contribution.  


## Managerial Implications
