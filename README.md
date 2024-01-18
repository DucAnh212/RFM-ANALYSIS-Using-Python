# RFM-ANALYSIS-Using-Python
## I. INTRODUCTION
### 1.About RFM Analysis
### Why RFM?
- RFM is a marketing analysis technique that stands for Recency, Frequency, and Monetary Value.
    - Recency: measures how recently a customer has made a purchase.
    - Frequency: measures how often a customer has made purchases.
    - Monetary Value: measures the total amount of money a customer has spent on purchases.
- RFM is used to identify and categorize customers based on their purchasing behavior and how recently and frequently they have made purchases, as well as the monetary value of those purchases
### How?
- In RFM analysis, customers are scored based on three factors (Recency - how recently, Frequency - how often, Monetary - how much), then labeled based on the combination of RFM scores
### Reference
- [RFM Analysis For Successful Customer Segmentation](https://www.putler.com/rfm-analysis)https://www.putler.com/rfm-analysis
  ### 2. Business Problem:
- SuperStore Company is a global retail company - Global. So the company has a lot of customers. On the occasion of Christmas and New Year, the Marketing Department wants to run marketing campaigns to thank customers for supporting the company in the past time. As well as exploit potential customers to become loyal customers.
- However, the Marketing Department has not yet been able to group each customer this year because the data set is too large to be processed manually as in previous years, so we asked the Data Analysis Department to assist in implementing a classification problem. segment of each customer to deploy each marketing program suitable for each customer group.
- The Marketing Director also proposed using the RFM model, but in the past, when the company was small, the team could calculate and classify it by themselves using Excel. Currently, the amount of data is too large, so it is expected that the Data Department will build a flow to implement Segmentation evaluation through Python programming.
  ### 3. Step to approach the problem:
- Step 1: Prepare a data set suitable for the RFM model. Step 2: Determine how to calculate and calculate the R, F, and M scores of each customer. Step 3:  Provide a calculation with a score corresponding to a scale of 1 to 5 using the quintile method of Statistics."
- Based on the classification table to group each customer
- Visualize the number of segment sets with data dimensions - Dimension
- Analyze the current situation of the company and give suggestions to the Marketing team
- Suggestions to the Marketing and Sales team with the retail model of the Superstore company, which index should be most interested in in the 3 R, F, and M indexes?
## II. Data Visualization
- Customer Distribution based on Recency
  ![image](https://github.com/DucAnh212/RFM-ANALYSIS-Using-Python/assets/151928789/5b7d4378-0496-4b1c-8055-134dd9ca1400)
- Customer Distribution based on Frequency
  ![image](https://github.com/DucAnh212/RFM-ANALYSIS-Using-Python/assets/151928789/428ed572-ebb3-4cdc-92f6-60cfa2efdfe3)
- Customer Distribution based on Monetary:
  ![image](https://github.com/DucAnh212/RFM-ANALYSIS-Using-Python/assets/151928789/c0f61b3f-c533-4afe-86db-775e5802114c)
- Treemap of customer segmentation (Count the number of customer types)
  ![image](https://github.com/DucAnh212/RFM-ANALYSIS-Using-Python/assets/151928789/fe5f4655-dd70-4588-b088-ecba9e8036cb)
- Seaborn Countplot of customer segmentation (label)
  ![image](https://github.com/DucAnh212/RFM-ANALYSIS-Using-Python/assets/151928789/9d308521-b5f9-467a-82f0-c1ddee1dbe85)
- Treemap of Total Sales in customer segmentation
  ![image](https://github.com/DucAnh212/RFM-ANALYSIS-Using-Python/assets/151928789/141e1587-3101-48eb-82b4-db47446b7ef4)
- Relationship between Recency and Frequency
  ![image](https://github.com/DucAnh212/RFM-ANALYSIS-Using-Python/assets/151928789/793ea7c0-a8ac-4646-857c-d66bd001e640)
- Definition and recommended action for each customer segment:
  ![image](https://github.com/DucAnh212/RFM-ANALYSIS-Using-Python/assets/151928789/3a011511-0d0d-4216-9b8e-2eb381ae2412)
## III. Insights:
1. The most important index of the 3 indicators that the SuperStore company needs to pay attention to is R and F: because the rate of customers buying products often in a short time range is very high -> That shows that the customer retention rate at the company is still low.

2. About Customer Segmentation: The company is mainly "Champions" >"Hibernating customers">"Lost customers". -> This again shows that we need to pay attention to the index F.

3. Revenue  from "Champions" is the highest.
## IV. Recommendations
- Firstly, Businesses should take more focus on the Champion and Loyal customer
These customers had taken an enormous of the RFM segment. As well as These customers have been shown that they bought company products recently, and often spend the most.
-> Recommendations to improve these customers are:
  - For Champion customer: - Giving them exclusive offers - Implementing loyalty rewards or increasing their loyalty rewards - Providing them with early access to new products - Inviting them to leave you a review
  - For Loyal Customers: Pitch your top-tier loyalty rewards- Tell them about new product releases- Invite them to follow on social media or send them information about the latest discount to enhance the brand experience
- Secondly, There were having 3 types of customers that were: Hibernating, Lost, and at-risk customers. Businesses should take notice of them by promoting some strategies
  - For hibernating customers who have not purchased in a while, send a win-back email or offer that encourages them to return to our business.
  - Offer a special discount or promotion that is personalized based on their past purchases.
  - For customers who have made multiple purchases in the past but have not made one recently, send personalized email campaigns that showcase new products or services that may be of interest to them.
  - For high-value customers who have not purchased in a while, send a personalized email or offer that highlights new products or services that may be of interest to them and offer a special discount or promotion that is tailored to their past purchase history.


