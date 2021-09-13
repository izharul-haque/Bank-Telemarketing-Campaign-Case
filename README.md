# Bank-Telemarketing-Campaign-Case
EDA done using python on this bank telemarketing campaign data set to infer knowledge that where bank has to put more effort to improve it's positive response rate.

# Problem Statement:
The bank provides financial services/products such as savings accounts, current accounts, debit cards, etc. to its customers. In order to increase its overall revenue, the bank conducts various marketing campaigns for its financial products such as credit cards, term deposits, loans, etc. These campaigns are intended for the bank’s existing customers. However, the marketing campaigns need to be cost-efficient so that the bank not only increases their overall revenues but also the total profit. You need to apply your knowledge of EDA on the given dataset to analyse the patterns and provide inferences/solutions for the future marketing campaign.

The bank conducted a telemarketing campaign for one of its financial products ‘Term Deposits’ to help foster long-term relationships with existing customers. The dataset contains information about all the customers who were contacted during a particular year to open term deposit accounts.

# What is the term Deposit?

Term deposits also called fixed deposits, are the cash investments made for a specific time period ranging from 1 month to 5 years for predetermined fixed interest rates. The fixed interest rates offered for term deposits are higher than the regular interest rates for savings accounts. The customers receive the total amount (investment plus the interest) at the end of the maturity period. Also, the money can only be withdrawn at the end of the maturity period. Withdrawing money before that will result in an added penalty associated, and the customer will not receive any interest returns.

Your target is to do end to end EDA on this bank telemarketing campaign data set to infer knowledge that where bank has to put more effort to improve it's positive response rate.

# Pairplot of salary, balance and age. 

![image](https://user-images.githubusercontent.com/76435558/133123092-f652a4e5-1b16-43f9-a368-c4bfcf383118.png)

# Bargraph of job categories percentage

![image](https://user-images.githubusercontent.com/76435558/133125858-3d9eb07d-5a53-42b1-b149-5be8682feffe.png)

# Heatmap of job and marital status

![image](https://user-images.githubusercontent.com/76435558/133126523-e1084343-f28f-4d6b-975c-5f97813f28af.png)


# Conclusion
By doing data cleaning and handling outliers, we can get some information about market behaviour and characteristic of this bank. First, the class of job such as entrepreneur, umployed, housemaid, student, admin, etc has shown blue-collar (21.53%), management (20.92%), and technician(16.80%) on top three. While the marital variable tells that mostly blue-collar and management segment had married. Blue-collar and management have a contrary in education class, which more than 15% of management segment has tertiary education history and blue-collar is less than 0.5%, dominated in secondary class education.

If we see the summary of balance (mean), we’ll notice that actually management segment has the biggest contribution in deficit balance (-) but also in top 5 for the highest amount of balance.

Now, let’s analyze poutcome variable which explains the outcome of previous marketing campaign. It can show probability of target market whether they will subscribe a term deposit or not. According to heatmap, management segment generates the highest rate of success, it also dominated in other categories of poutcome along a year, significantly in March, September, and November. While blue-collar segment doesn’t really show big impact for succesfull rate market. On the other side, technician contributes accountable success rate in August and stable performance in every category of poutcome.

Conclusion: It is important to strengthen the exposure for target market at the right time, reconsider the capability of each segment whether they’d subscribe a term deposit or not. For example, blue-collar segment has a big number of unsubscribed deposit while management segment looks promising. So, it will be a wise desicion to put this market segment into top priority.
