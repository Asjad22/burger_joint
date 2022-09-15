# burger_joint

## Warning: "This notebook could be slow without GPU"
## Note: "I'm using Nvidia GeForce 1050 ti, 4gb"

### Case Study:
To predict which customer is most likely to buy a burger joint deal, and which age group should be targeted, without having any relevent personal information/data.
I've implemented RNN to tackle multivariate time series

### Dataset Information:
The Dataset has been generated from faker.

The shape of Dataset is (2000, 6), 2000 rows and 6 variables.

The details of variables are as follow:
    
    transaction_date_time = The time of transaction.
    
    cust_id = Customer ID
    
    credit_card_number = credit card number.
    
    transaction_type = Assumed 4 different transaction types:
    
        a = food,
    
        b = medication,
    
        c = fuel,
    
        d = others.
    
transaction_amount = The total amount spent on transaction types.
    
    day_type = Assumed 2 day_types:
    
    w = Transaction occured on WEEKDAYS,
    
    s = Transaction occured on WEEKEND.
        
