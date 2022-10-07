# Market-Basket-Analysis
Market Basket Analysis or MBA attempts to identify the items that are frequently purchased together. 
The association rule is an if-then statement. “If” is the antecedent and “then” is the consequent. 
The Apriori algorithm is used in rule mining. 
It assumes that the subset of a frequent itemset is also a frequent itemset. 
The minimum support threshold in the project is 0.001 and confidence will be 0.9. 
The top ten rules passing the support and confidence criteria are declared as strong associations, but only if their lift is more than 1. 
The support metric assures that there is a minimum fraction of transactions in the data that contain an itemset. 
On the other hand, the confidence metric measures how often item Y appears in the transactions that also have item X. 
If the algorithms are able to find rules that satisfy the given support and confidence metrics, then it means that there is an association among the items of the basket.
In python, MLxtend library is used for rule mining. It is a great data mining tool, which contains important association rule mining packages such as apriori and association_rule. 
In R, the arules library was used for the association rules extraction. It is designed for manipulating, analyzing, and representing transactional data. 
