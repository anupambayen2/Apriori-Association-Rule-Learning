Project Summary: Market Basket Analysis Using Apriori Algorithm

This project applies the Apriori algorithm, an association rule learning technique, to discover relationships between products purchased together. It is part of my daily machine learning practice uploads on GitHub.

📌 Objective

To identify frequent itemsets and generate association rules that help understand customer purchasing behavior.

📊 Dataset

Dataset used: Market_Basket_Optimisation.csv

Contains transactional data of customer purchases

Each row represents a single transaction

Items in a transaction are listed across columns

This dataset is ideal for market basket analysis.

🛠️ Steps Performed

Loaded and transformed transaction data into a suitable format

Applied the Apriori algorithm to extract frequent itemsets

Generated association rules based on:

Support

Confidence

Lift

Filtered strong rules using threshold values

📈 Key Insight

The algorithm identifies products that are frequently bought together.

Rules with high lift indicate strong associations beyond random chance.

These insights can be used for:

Product placement

Cross-selling strategies

Recommendation systems

🧪 Outputs

Frequent itemsets

Association rules with support, confidence, and lift

List of strong product-to-product relationships

🚀 Conclusion

Apriori is a powerful technique for uncovering hidden relationships in transactional data. This project demonstrates how association rule learning can provide actionable business insights from raw purchase data.
