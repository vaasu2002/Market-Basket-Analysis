# Market Basket Analysis (MBA)
```ruby
!pip install apyori
from apyori import apriori
```
```
items=frozenset({'sugar', 'spread cheese'}), 
support=0.00040098910646260775, 
ordered_statistics=[OrderedStatistic(items_base=frozenset({'spread cheese'}), 
items_add=frozenset({'sugar'}), 
confidence=0.06, 
lift=3.3878490566037733)
```

- Market Basket Analysis is one of the key techniques used by large retailers to uncover associations between items. It works by looking for combinations of items that occur together frequently in transactions. To put it another way, it allows retailers to identify relationships between the items that people buy.
- It is based on theory that if you buy certain groups of items, you are more likly to buy another group of items.
- To find the association rules from the given data. 

**Works on Sequential Frequent Patters**

- Example - When we buy laptop only it recommends us to buy anti-virus and other accessories like mouse, cooling pad etc to buy with it. But when we just buy anti-virus it does not recommends us to buy laptop for it. 

**Primary Objective -**
1) Improve effectiveness of marketing
2) Improve sales tactics using customer data collection

**MATEMATICAL CONCEPT-**
1)  SUPPORT      -    Probability of event 1 union event 2
2)  CONFIDENCE   -    Probability of a event given probability of other event.

**SUPPORT** - Probability of person buying phone in an online website.

**CONFIDENCE** - Probability of person buying screenguard if person buys phone.
