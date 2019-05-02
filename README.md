# Bankin Recovery - Regression Discontinuity

After a dept has been legally declared "uncollectible" by a bank, the account is considered to be "charged-off".  
But that doesn't mean the bank simply walks away from the dept. They still want to collect some fo the money they are owed. 
The bank will score the account to assess the expected recovery amount, that is, the expected amount that the bank may be able to
receive from the customer in the future (for a fixed time period such as one year).This amount is a fuction of the probability
of the customer paying, the total debt, and other factors that impact the ability and willingness to pay.

The bank has implemented different recovery strategies at different thresholds ($1000, $2000, etc.) where the greater 
the expected recovery amount, the more effort the bank puts into contacting the customer. 
For low recovery amounts (Level 0), the bank just adds the customer's contact information to their automatic dialer and 
emailing system. For higher recovery strategies, the bank incurs more costs as they leverage human resources in more 
efforts to contact the customer and obtain payments. Each additional level of recovery strategy requires an additional $50 
per customer so that customers in the Recovery Strategy Level 1 cost the company $50 more than those in Level 0. 
Customers in Level 2 cost $50 more than those in Level 1, etc.

The big question does the extra amount that is recovered at the higher strategy level exceed the extra $50 in costs?
In other words, was there a jump (also called a "discontinuity") of more than $50 in the amount recovered at the higher 
strategy level? 
