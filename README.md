# Market Basket Analysis

Market Basket Analysis is one of the key techniques used by large retailers to uncover associations between items. It works by looking for combinations of items that occur together frequently in transactions. To put it another way, it allows retailers to identify relationships between the items that people buy.


- Sample code snippets:

    ```python
    from mlxtend.frequent_patterns import apriori, association_rules

    freq = apriori(one_hot_df, min_support=0.01, use_colnames=True)
    rules = association_rules(freq, metric="lift", min_threshold=1.2)
    #Nour El-Rouby
    ```
