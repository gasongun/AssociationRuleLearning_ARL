# AssociationRuleLearning_ARL

![AssociationRuleLearning](https://user-images.githubusercontent.com/82174541/207074616-9937685b-bf64-4be2-90fd-d06ce7ef583c.JPG)

It is very important to examine the hidden patterns between the products at the point of contact with the customer and to examine which products can be presented together. Obviously, companies that make suggestions on associated products in their product offers will get more efficient results. Market Basket Analysis is one of the association rules. It enables us to offer products that can be recommended in the future by developing models from the relationships of products purchased in the past. Many techniques can be used to derive Association Rules such as Apriori, Eclat, FP-Growth, Assoc etc. The most widely used of these is the apriori algorithm.

Apriori Algorithm gives some metrics that can be use for prioritization. These can be seen in the project. The most used ones are support, confidence and lift.

• *Antecedents:* An item (for this dataset is product) found in data.

• *Consequents:* An item found in combination with the antecedent.

• *Antecedent_Support:* Probability of antecedent's occurrence.

• *Consequents_Support:* Probability of consequent's occurrence.

• *Support:* Probability of antecedent and consequent's together occurrence.

• *Confidence:* Probability of the items occurring together by the probability of antecedent's occurence. (Support / Antecedent Support)

• *Lift:* Proportion of the items occurring together and their expected probabilities. (Support/(Antecedent_Support*Consequents_Support)) This shows us that when the • antecedent item is purchased, the probability of purchasing the consequent item increases by lift.

• *Leverage:* Correlation between item sets by comparing the support of item sets under independence assumption. (Support-(Antecedent_Support*Consequents_Support))
Because of the difference in the formula, leverage favors item sets with higher support, while lift can find strong associations among less frequent item sets.

• *Conviction:* Antecedent item's expected value without consequent item. ((1-Support) / (1-Confidence))

## BUSINESS PROBLEM :

Recommend a product to users at the basket stage.

## DATASET STORY :

Online Retail II The dataset named is a UK-based online sales store's sales between 01/12/2009 and 09/12/2011 contains. The product catalog of this company includes souvenirs

## VARIABLES :

• InvoiceNo - Invoice Number (If this code starts with C, it means that the transaction has been returned)

• StockCode - Product (item) code

• Description - Product (item) name.

• Quantity - The quantities of each product (item) per transaction.

• InvoiceDate - Invice date and time.

• UnitPrice - Item price. Product price per unit in sterling 

• CustomerID - Unique customer number

• Country - Country name. The name of the country where a customer resides.


Dataset :
https://archive.ics.uci.edu/ml/datasets/Online+Retail+II
