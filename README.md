# Customer-Churn
Customers churn when they terminate services with a company. In the context of Banking, customers churn when they stop using the services provided by the bank. 
Reasons for churn:
* They simply no longer use their services
* They go to Bank's competitors

#
**For full rendered code and graphs use:** [Link](https://nbviewer.jupyter.org/github/MartinMwiti/Customer-Churn/blob/master/code.ipynb)

**For the GitHub version code:** [link](https://github.com/MartinMwiti/Customer-Churn/blob/master/code.ipynb)
#
### Active VS Churned
## 1. Gender proportion
![Gender proportion](https://github.com/MartinMwiti/Customer-Churn/blob/master/Presentation/newplot%20(2).png)
* 60% of our churned customers are female, this is not
necessarily a bad thing because females constitute 57% of
our current customer business.

## 2. Geographical stats
![Geographical stats](https://github.com/MartinMwiti/Customer-Churn/blob/master/Presentation/newplot%20(1).png)
* 60% of our churned customers are female, this is not
necessarily a bad thing because females constitute 57% of
our current customer business.

## 3. Number of Products stats(Active vs Churned)
![Number of Products stats(Active vs Churned)](https://github.com/MartinMwiti/Customer-Churn/blob/master/Presentation/newplot%20(8).png)

* By providing one or two products tends to have significantly more Active users compared to their respective churns.
* Three products offered to customers tends to have more customers who churn compared to those who're active for same number of products.
* All customers who had four products tend to exit the bank.

**Conclusion**: By maximizing on offering a maximum of two products per customers will help retain more customers

## 4. Number of Cards stats(Active vs Churned)
![Number of Cards stats(Active vs Churned)](https://github.com/MartinMwiti/Customer-Churn/blob/master/Presentation/newplot%20(9).png)

* Having one card tend to have a higher number of Active customers compared to those having two cards.
* As a business, we need to evaluate whether or not it is necessary to provide two cards to customers.

## Conclusion
* Although i have performed ML and ANN on this dataset, the data
provided is not enough to justify using predictive modeling. I would
need customer behavior over time such as

1. Where were they before joining the bank?

2. When did they join us

* We could extract features and throw it into an ML or ANN model but
since we only have one tuple per customer, building this classier isn't
really helpful given this data.
