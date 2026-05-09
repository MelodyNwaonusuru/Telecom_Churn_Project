**ConnectPlus Telecom — Project Background**

**Overview**

ConnectPlus Telecom is a California-based telecommunications provider serving residential customers across the state's major metropolitan areas, including Los Angeles, San Diego, San Jose, Sacramento, and San Francisco etc. The company offers a range of internet, phone, and billing services across multiple contract types, payment methods, and service tiers generating rich customer behavioural data that forms the foundation of this analysis.

**Problem Statement**

ConnectPlus Telecom was experiencing an elevated customer churn rate with limited analytical clarity on who was leaving, why they were leaving, and what commercial value was being lost as a result. Without a structured view of churn drivers whether rooted in contract structure, service type, tenure stage, or competitor pressure the business had no reliable basis for designing targeted retention strategies or prioritising interventions where they would have the greatest impact.

**Project Objective**

This project delivers a thorough diagnostic of ConnectPlus Telecom's customer base, with a primary focus on understanding churn behaviour and identifying the demographic, behavioural, and service-level patterns that most strongly predict customer exit. By translating raw transactional and customer data into clear, evidence-backed narratives, this project equips ConnectPlus leadership with the intelligence needed to reduce churn, protect revenue, and build a more loyal and commercially valuable customer base.

**Key Areas of Analysis**

1. **Customer Profile Overview**: A baseline understanding of the total customer base covering volume, gender distribution, city concentration, senior citizen representation, average tenure, and average charges to establish a clear commercial starting point.
2. **Churn Rate Analysis**: A focused investigation into the churn rate across the business, identifying which customer segments, service types, contract structures, and payment behaviours carry the highest churn risk.
3. **Internet Service & Payment Method Breakdown**: A cross-analysis of churn rates by internet service type and payment method, to identify whether specific product or billing configurations are systematically driving exit behaviour.
4. **Churn Reason Deep Dive**: A granular review of stated churn reasons and associated lost revenue, identifying whether churn is primarily competitor-driven, service-quality-driven, or pricing-driven and what the business can realistically address.

**Data Structure & Initial Checks**

The ConnectPlus dataset was structured as a file containing 7,043 customer records across California, with each row representing one customer and their full service profile. Data cleaning and exploratory analysis were conducted in Microsoft Excel prior to dashboard development in Power BI.
Cleaning steps performed in Excel included:

1. Removed duplicate records and confirmed row-level uniqueness by Customer ID
2. Standardised categorical fields including Contract Type, Internet Service, Payment Method, and Churn Label to ensure consistent grouping
3. Created calculated columns including Tenure Band (bucketed into six intervals: 0–12, 13–24, 25–36, 37–48, 49–60, 61–72 months).
  
You can download the cleaned dataset used in this project here:
[⬇️ Download Telecom_Clean_dataset.xlsx](https://github.com/MelodyNwaonusuru/Telecom_Churn_Project/raw/refs/heads/main/Telecom_Clean_dataset.xlsx)

Download the Power BI report file to explore the interactive dashboard:

[⬇️ Download Telecom_Churn_Project.pbix](https://github.com/MelodyNwaonusuru/Telecom_Churn_Project/raw/main/Telecom_Churn_Project%20(2).pbix)

> ⚠️ Requires [Power BI Desktop](https://powerbi.microsoft.com/desktop/) to open.



The cleaned dataset was then imported into Power BI for modelling and dashboard development.

**Executive Summary — Customer Insights Dashboard**

1. ConnectPlus serves 7,043 total customers, of whom 5,174 are active and 1,869 have churned representing a 26.54% churn rate, a commercially significant level of customer attrition that warrants urgent attention.
2. The average charges for the customer base is $455.67k.
3. Customer demographics show a balanced gender distribution, while non-senior citizens make up the majority of subscribers (83.79%), highlighting stronger engagement among younger customers and an average customer tenure of 32.37 months.
4. Los Angeles leads all cities in total customer volume (305), with San Diego, San Jose, Sacramento, and San Francisco forming the secondary tier, confirming Los Angeles as the company's most commercially dense market.
5. Month-to-month contracts dominate the customer base at 3.9K customers, significantly outpacing two-year (1.7K) and one-year (1.5K) arrangements — a structural vulnerability, as shorter contracts offer customers the lowest barrier to exit.
6. Electronic check is the most commonly used payment method, with 2,365 customers, likely due to its convenience, ease of recurring bill payments, and the increasing preference for digital transaction methods among telecom subscribers.
7. The highest customer concentration is within the 0–12 months tenure group (2,186 customers), followed by the 61–72 months group, showing a mix of newly acquired customers and long-term retained subscribers.

The below is the dashboard of customer insights dashboard

![image alt](https://github.com/MelodyNwaonusuru/Telecom_Churn_Project/blob/main/Screenshot%202026-05-09%20103032.png?raw=true)

**Insight Deep Dive — Customer Churn & Retention Analysis** 

Key Findings

1. Customer churn stands at 26.54%, with 1,869 customers lost and 5,174 remaining active. Churned customers generated approximately $2.86 million in total charges, emphasizing the financial impact of customer attrition.
2. Fiber Optic customers exhibit the highest churn rate (41.89%), indicating a higher risk of customer loss within this service category compared to DSL (18.96%) and customers without internet service (7.40%) lower-engagement product relationships produce more stable customer behaviour though this segment likely represents lower commercial value.
3. Churn distribution is gender-balanced, suggesting that both male and female customers are equally likely to discontinue the service
4. Customer churn is highest during the first year at 47.4%, but drops significantly to just 6.6% for long-term users. This indicates that the first 12 months are a critical "danger zone" where targeted engagement is most needed to secure long-term loyalty.
It shows that a customer who survives the first year is nearly 7x more likely to stay than a brand-new user.
5. Customers using electronic checks exhibit the highest turnover at 45.3%, while those on automated credit card billing are the most stable with a churn rate of only 15.2%. Electronic checks are more prone to failure due to insufficient funds or manual entry errors. Automated methods provide a more seamless experience, reducing "involuntary churn" caused by payment issues.
6. The data reveals that aggressive competition on speed and data volume is the primary driver of customer loss, while external market offers are pulling users away, internal service friction from support staff is further accelerating these departures.

To improve retention, the focus must shift toward matching competitor technical specs while simultaneously addressing the quality of customer interactions.

![image alt](https://github.com/MelodyNwaonusuru/Telecom_Churn_Project/blob/main/Screenshot%202026-05-09%20103318.png?raw=true)

**Recommendations**

Strategic Priorities

**1. Financial Impact of Churn ($2.86M Lost)**
$2.86M in lost revenue is not a metric to monitor — it is a mandate to act. Every retention initiative must be benchmarked against CLV recovery targets, not vanity engagement metrics, so the business can measure what it is actually winning back.


**2. Fiber Optic Churn (41.89%)**
Fiber customers represent your highest commercial value and your highest attrition risk that contradiction is costing the business more than any other single segment. Waiting for a cancellation request to make a loyalty offer is already too late.


**3. First-Year Danger Zone (47.4%)**
A customer who survives their first year is nearly seven times more likely to stay which means the entire retention strategy should be front-loaded around that window. The first year is not a grace period — it is the highest-leverage intervention point in the entire customer lifecycle.

**4. Electronic Check Churn (45.3%)**
Nearly half of electronic check users are churning, and a significant portion of those exits are involuntary triggered by payment failures, not genuine dissatisfaction. The cost of a switching incentive is negligible against the revenue being silently lost every billing cycle.

**5. Competition, Market Offers & Internal Friction**
The business is losing customers from both ends external competitors are pulling them out while poor internal service experiences are pushing them toward the door. A customer who has already received a rival offer and contacted support is not a churned customer yet but they are close.

**Tools Used**

**Tool Purpose**

Microsoft Excel : Data cleaning, deduplication, null handling, tenure band creation, exploratory data analysis (EDA)

Power BI Desktop : Data modelling, DAX measure development, dashboard design and layout

DAX Measures :Churn Rate %, Total Charges Churned, Average Churn Score, Customer Count by Segment, conditional formatting 

logicPower Query (M): Data transformation, column structuring, data type enforcement

Custom Calculated Columns : Tenure Band grouping (6 intervals), Churn flag validation, segment-level aggregations
