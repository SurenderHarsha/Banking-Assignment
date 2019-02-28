# Marketing for acquiring customers

The purpose of this project is to reduce marketing costs and time by selecting a select group of customers who have something in
common and are more likely to make a deposit rather than making random calls.

The project is mainly a supervised model that can predict based on some input variables if the customer will make a deposit.


A basic analysis on input variables and outputs can reveal some common similarities on the properties of a customer.
Correlation may not imply causality. But in this case, the reasoning and this analysis make sense.

#### Jobs

![GitHub Logo](Jobs.png)
Correlation
A simple analysis shows that customers who are either retired or students are more likely to deposit, most likely for their future
and savings. This is the customer field we can target to the most.


### Marital Status

![GitHub Logo](Marital.png)

The correlation anaylsis shows that most single people are likely to make a deposit, again this makes sense as they are
saving up for their future.

### Education

![GitHub Logo](Education.png)

Compared to University degree customers, the other customers are less likely to agree to the deposit. This might be most likely due to being ignorant of its benefits.


### Credit Default

![GitHub Logo](Default.png)

Customers with a good credit score and who pay the bills right on time are more likely to make term deposits.

Similarly, in the case of housing, loan and contact. Customers who have housing and no loan and a cellular method of contact are more likely to respond positively.

Correlation in itself cannot be used to determine which variable effects the outcome.





## The supervised model

Therefore we use the supervised model to predict if a customer would agree to the deposit.
Each of these parameters has been given its own input layer so that we can determine based on the weights of regression, the importance of each of these input variables.

Therefore I would like to begin with this project of creating a supervised model and analyse the end results which allows us to categorize the customer based on their properties and make informed calls.
