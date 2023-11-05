# 2023-DTU-Computational-Tools-For-DS-Amazon-Food-Reviews

## Graph

Creation:
1. user - product (bipartite graph)
2. user - user (if both users reviewed same product)
3. product - product (if both products were reviewed by one user)
4. user - user (Each user is connected to top 5% most similar users based on jaccard similarity on signatures)

Ideas:
* Based on communities find frequent itemsets (3)
* Based on communities discover different styles of writting comments (4)

## NLP

Ideas:
* Time series analysis - how has the product reviews change in time
* Time series analysis - how users change their reviews in time
* Sentiment clustering
