
HELIX BANK CUSTOMER CHURN ANALYSIS FOR THE YEAR 2024


 <img width="1014" height="504" alt="image" src="https://github.com/user-attachments/assets/12bccfba-fc54-4cba-9493-826e46b6146e" />

INTRODUCTION
This project analyzes customer churn at Helix Bank for the year 2024 to understand patterns of customer attrition and identify high-risk segments. Using historical customer data, the analysis examines churn across key dimensions including age group, country, gender, activity status, credit score, account balance, and salary. An interactive dashboard was developed to visualize churn trends and support comparative analysis across segments. The study identifies age, geography, and customer engagement as the primary drivers of churn, while financial indicators show limited influence. The insights generated aim to support data-driven decision-making and guide targeted customer retention strategies. Ultimately, the project helps the bank focus retention efforts where they will have the greatest impact.
PRE-ANALYSIS BOARD
Project Split
Category 1: Independent Variables
•Customer ID
•Last name
•Record ID
•Gender
•Country
Category 2: Dependent Variables
•Account Balance
•Age 
•Credit Score
•Activity Status
•Estimated Salary
•Exit Status
•Tenure

Potential Analysis/Questions
1. What percentage of customers have exited the bank?
2. How does churn rate vary by geography?
3. What is the gender distribution among exited and retained customers?
4. Does age affect customer churn?
5. What is the average credit score of customers who exited vs. stayed?
6. Is balance a key factor in churn?
7. Are active members less likely to churn?
8. How does salary relate to churn?

Industry Type
Banking and Financial Services Industry.

Story of the Data
This dataset captures customer information and behavior in a bank. It  provides information on which customers are leaving  and  the  factors that may be responsible  like credit score, age, account balance, product usage, and activity status.
.

Stakeholders
•	Bank Executives
•	Customer Insights Team
•	Customer Retention Managers
•	Finance Teams
•	Marketing Teams

Definition of Success
For the banking and financial service industry, customer retention is a key success indicator.

Potential Insights
1.	Identification of the country with the highest churn.
2.	Determination of the role of  gender on customer churn.
3.	Assessment of the influence of age group on customer churn.
4.	Analysis of Impact of activity status on churn.
5.	Evaluation of the effect of credit score on churn.
6.	Evaluation of the impact of account balance on churn.
7.	Identification of the effect of income on churn.











IN-ANALYSIS BOARD
Analysis: Which Country has most churn?
  
Observations
1.	Germany has the highest churn ratio (32%). Nearly one out of every three customers in Germany has exited the bank, even though the customer base (2,509) is smaller than France.
2.	Spain shows a moderate churn ratio (17%). Less than one-fifth of Spanish customers have churned, with a customer count (2,477) similar to Germany.
3.	France has the lowest churn ratio (16%). France retains customers better than the other countries, despite having the largest customer base (5,014).
4.	Customer base size does not directly explain churn behavior. Germany and Spain have almost the same number of customers, yet Germany’s churn ratio is nearly double that of Spain.

Insights
1.	Germany is the highest-risk market for customer attrition. The significantly higher churn ratio may reflect customer dissatisfaction, stronger competition, or misalignment of products and services in the German market.
2.	France demonstrates strong customer retention at scale. Maintaining the lowest churn ratio while serving the largest number of customers indicates effective customer engagement and service delivery.
3.	Spain represents a relatively stable but improvable market. Spain’s churn ratio is moderate, indicating acceptable retention with room for improvement.
4.	Country-specific strategies are necessary. The large variation in churn ratios across countries shows that customer behavior differs by market, and a one-size-fits-all retention strategy may not be effective.

Analysis: Which Age Group Churns Most?
 
Observations
1. Customers aged 50–59 have the highest churn rate (56%). More than half of customers in this age group have exited, despite having a moderate customer base (869 customers).
2. Churn is also high among customers aged 60–69 (35%).The total number of customers is relatively small (375), over one-third have churned.
3. Middle-aged customers (40–49) show moderate churn (31%). This group has a large customer base (2,618 customers), making it a significant contributor to overall churn volume.
4. Younger customers (30–39) have the lowest meaningful churn rate (11%). This age group has the largest customer base (4,346 customers) and shows strong retention.
5. Very elderly customers (70–79) show low churn (10%) but very small population. The low churn rate may not be very impactful due to the small number of customers (136).
Insights
1. Customers above 50 years are far more likely to leave the bank, indicating possible dissatisfaction with services, digital platforms, or product relevance.
2. The 50–59 age group is a critical risk segment. This group combines high churn rate with a reasonable customer base, making it the most urgent segment for retention efforts.
3. Younger customers (30–39) are highly loyal. The low churn rate suggests current products, pricing, and digital services meet the needs of this age group.
4. Churn among 40–49 year olds has high business impact. Even with a lower churn rate than older groups, the large population means this segment contributes substantially to total churn numbers.
5. Low churn in 70–79 may reflect switching barriers, not satisfaction. Older customers may stay due to habit or difficulty switching banks rather than strong engagement.

Analysis: Which Gender Churns More?
 


Observations
1. Females make up 55.92% of churned customers.
2. Males make up 44.08% of churned customers.
Insights:
1. Females are more likely to churn than males in this dataset.
2. The bank may not be adequately meeting the financial service preferences or communication styles of female customers.

Analysis: Does Activity Affect Churn?
 
Observations
1. Inactive customers make up 26.85% of churned customers
2. Active customers make up 14.27% of  churned customers
Insights
1. Active users clearly have a lower churn rate.
2. Customer engagement strongly correlates with retention.
3. Keeping customers active  reduces churn probability.



Analysis: How does churn vary by credit score?
 
Observations
1. Churn ratio is almost identical across most credit score bands (≈20–21%). Customers with credit scores between 400 and 900 show very similar churn behavior, indicating little variation by credit score in this range.
2. The 500–599 and 400–499 bands have slightly higher churn (21%). These mid-to-low credit score groups experience marginally higher churn than higher score bands.
3. The 600–699 credit score band has the largest customer base (3,818 customers). Although its churn ratio is average (20%), its size means it contributes significantly to total churn volume.
4. Customers with very low credit scores (300–399) show 100% churn. All 19 customers in this band have exited, though the sample size is extremely small.
5. High credit score customers (800–900) still churn at a notable rate (20%).




Insights
1. The similar churn ratios across most score bands suggest that Credit score alone is not a strong driver of churn and other factors (such as service quality, fees, or engagement) may be more influential.
2. Both low- and high-credit customers are equally at risk of churn. Retention challenges are not limited to financially weaker customers; even premium customers are leaving.
3. The 300–399 credit score group is statistically unreliable
The 100% churn rate is driven by a very small number of customers and should be interpreted with caution.
4. Large customer segments with average churn deserve attention. The 600–699 and 700–799 bands, due to their size, represent the greatest absolute churn impact.

Analysis: How does churn vary by account balance?
 
Observations
1. Customers with higher account balances tend to show higher churn rates compared to lower balance groups.
2. Mid-balance customers (₦90,000–₦120,000 and ₦120,000–₦150,000) have relatively high churn (26% and 24%). These groups also have large customer counts (2,217 and 2,212 respectively), making them significant contributors to overall churn.
3. High-balance customers (₦180,000–₦210,000) show elevated churn (30%). Despite a smaller population (147 customers), nearly one-third have exited.
4. Very high-balance bands show extreme churn ratios, ₦210,000–₦240,000: 50% churn (12 customers), ₦240,000–₦270,000: 100% churn (1 customer)
5. Low-balance customers (₦30,000–₦60,000) also show high churn (26%). Although the customer count is small (143), churn is comparable to mid-balance segments.

Insights :
1. High account balance does not guarantee loyalty. Customers with larger balances are still leaving the bank, suggesting dissatisfaction with value, service quality, or pricing.
2. Mid-balance customers pose the greatest business risk. Moderate-to-high churn combined with large customer bases means these segments likely contribute most to total churn losses.
3.Extreme churn ratios in very high-balance groups are sample-size driven.The 50% and 100% churn rates are influenced by very small customer counts and should be interpreted cautiously.
4. Churn behavior is not linear across balance bands. Both low and high balances experience elevated churn, indicating multiple underlying drivers rather than a single cause.


Analysis: Does Salary affect Churn?
 


Observations
1. Churn ratio is almost identical across all salary bands (20–22%). Customer churn remains stable regardless of income level.
2. The highest salary band (160,000–200,000) shows only slightly higher churn (22%)
The difference is marginal and not significantly different from other salary groups.
3. Customer distribution is evenly spread across salary bands
4. No salary group stands out as a high-risk churn segment. There are no extreme churn ratios or sharp variations across income levels.
Insights
1. Salary level is not a strong determinant of churn
2. Churn is driven by non-income-related factors. Factors such as service quality, customer experience, product fit, or engagement are likely more influential than salary.
3. High-income customers are not more loyal than low-income customers
4. Uniform churn suggests system-wide retention issues. Since churn is consistent across salary bands, the root causes may affect all customers equally.

POST-ANALYSIS BOARD
Post-Analysis Observations
1. 2,038 out of 10,000 customers churned — representing a 20.38% churn rate.
2. The customer churn analysis indicates that churn is not evenly distributed across all customer segments. Clear patterns emerge across age, geography, and customer activity status, while financial capacity indicators show limited influence.
3. Churn is highest among customers aged 50–69, with the 50–59 age group consistently recording the greatest attrition. Younger customers, particularly those aged 30–39, demonstrate stronger retention and greater stability. This age-related churn pattern remains consistent even after filtering the data by country and gender, indicating that age is a primary churn driver.
4. From a geographic perspective, Germany records the highest churn ratio, despite having a customer base comparable to Spain and smaller than France. France shows the strongest retention performance, while Spain demonstrates moderate churn. Dashboard slicing confirms that Germany’s high churn is structural, not driven by a single demographic group.
5. Customer activity status is one of the strongest predictors of churn. Inactive customers are significantly more likely to exit than active customers across all slices, including Germany-only and Germany–female views. This highlights disengagement as a critical churn risk factor.
6. Financial indicators such as salary and credit score show minimal variation in churn ratios, suggesting that income level and creditworthiness are not strong standalone predictors of churn. Customers across most salary and credit score bands churn at similar rates.
7. Account balance presents a mixed pattern. Mid- to high-balance customers contribute significantly to churn due to their size and moderate-to-high churn ratios. Extremely high churn observed in very high balance bands is influenced by small customer counts.
8. Gender-based slicing shows that while churn volumes change, overall churn patterns remain consistent, confirming that gender is a secondary factor rather than a primary driver.

Post-Analysis Recommendations
1. Prioritize retention for high-risk age groups (50–69)
Develop tailored engagement and retention programs, including personalized financial advice, retirement-focused products, and enhanced relationship management.
2. Urgently address churn in the German market
Conduct a targeted root-cause analysis to identify country-specific drivers such as pricing, competition, service quality, or regulatory factors, and implement localized retention strategies.
3. Reduce churn by improving customer engagement
Focus on converting inactive customers to active users through targeted communication, usage incentives, simplified digital experiences, and proactive outreach.
4. Protect mid- and high-balance customers
Introduce loyalty benefits, premium support, and value-added services to prevent attrition among customers who represent significant revenue potential.
5. Avoid reliance on salary or credit score for churn prediction
Shift focus toward behavioral indicators such as activity status, tenure, and product usage, which provide stronger signals of churn risk.
6. Adopt segment-specific rather than one-size-fits-all strategies
Differences across age groups and countries indicate that tailored retention approaches will be more effective than uniform interventions.
CONCLUSION
This customer churn analysis successfully identified the key factors influencing customer attrition at Helix Bank. The findings show that churn is primarily driven by age, geography, and customer engagement, with higher churn observed among older customers, inactive users, and customers in specific markets such as Germany. In contrast, financial indicators including salary and credit score were found to have limited influence on churn behavior. The use of churn ratios and interactive dashboard slicing provided a more accurate and realistic understanding of churn patterns across customer segments. Overall, the insights generated from this analysis equip stakeholders with actionable, data-driven guidance to implement targeted retention strategies and improve long-term customer loyalty. 
Data source: Dataset from Kaggle

