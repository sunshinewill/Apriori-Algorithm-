# Apriori Algorithm-

There are 3 ways to measure association:

-Support
-Confidence
-Lift

Support: It gives the fraction of transactions which contains item A and B. Basically Support tells us about the frequently bought items or the combination of items bought frequently.

So with this, we can filter out the items that have a low frequency.

Confidence: It tells us how often the items A and B occur together, given the number times A occurs.

Lift: Lift indicates the strength of a rule over the random occurrence of A and B. It basically tells us the strength of any rule.

Lift explains the strength of a rule. More the Lift more is the strength.


Apriori Algorithm:
1, a subset of a frequent itemset must also be a frequent itemset.
2, a superset of a infrequent itemset must also be a infrequent itemset. 
