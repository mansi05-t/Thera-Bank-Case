# Thera-Bank-Case

This case is about a bank (Thera Bank) which has a growing customer base. Majority of these customers are liability customers (depositors) with varying size of deposits. 
The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). 

# Problem :
A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with minimal budget.

The classification goal is **to predict the likelihood of a liability customer buying personal loans.**

# Libraries:
 * Pandas
 * Numpy 
 * Seaborn
 * Matplotlib
 
# Classification Models:
  * Logistic Regression
  * Naive Bayes
  * K Nearest Neighbor
  * Decision Tree
  * Random Forest

To assess the effectiveness of my model,I have used K-fold validation.

**Data file:**
The file Bank.xls contains data on 5000 customers. The data include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.
