# Bank Looking For Clients

**Source of data:**
https://www.kaggle.com/itsmesunil/bank-loan-modelling
<br><br>
**Files:**<br>
00_main.ipynb - main flow of analysis<br>
expolaratory_report.html - exploratory report<br>
explanatory report.pdf - explanatory report
<br><br>
The case is The Bank has a customers Data with various characteristics of the customers. The management built a new product - Personal Loan, and ran a small campaign towards selling the New Product to their clients. 
After some time, 9% of customers have Personal Loan from The Bank.


### The GOAL IS!
> - To sell more Personal Loan products to Bank customers.
> - To devise campaigns to better target marketing to increase the success ratio with a minimal budget.
> - To identify the potential customers who have a higher probability of purchasing the loan. 

Increase the success ratio of advertisement campaign while at the same time reduce the cost of the campaign.


### The Questions for Analysis
As soon as we got 9% of customers who bought the Product, we got the following questions:

> - Is there some associations between personal characteristics and the fact that customer bought the Product? If so:
>
> - What are those Main Characteristics that have an association with the Product and what is the strength of the association?
> - What are the Segments of Main Characteristics, that have a higher strength of association with the Product?
> - What is the sample of Data with customers from Main Segments?
 

### Approach

We made the simple step-by-step analysis of customer's characteristics to identify patterns to effectively choose the subset of customers who have a higher probability to buy new product "Personal Loan" from The Bank. 
<br><br>
We performed the following steps:
> - We check all twelve characteristics whether or not each of them has an association with the fact the product been sold.
> - We find FIVE main characteristics that have higher than moderate strength of association with the product.
> - We analyze main characteristics and get segments in each with different strength of association with the product.
> - We tried to make a subset of customers with ideal characteristics who has the highest probability to buy the product. Unfortunately, our dataset does not contain such information. So...
> - We build a simple algorithm to make a subset of data to get the customers IDs who have a high probability to buy the product.

### Technologis

- Python
- Pandas
- Numpy
- Seaborn
- Matplotlib
