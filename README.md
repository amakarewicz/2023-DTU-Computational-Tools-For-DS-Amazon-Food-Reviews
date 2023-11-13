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

## Tasks

* Create 3 graphs - Emi & Bartek (third in drive) - DONE
* NLP cleaning - Kuba - DONE
* NLP signatures + graph - Agata - TODO
** Embedding + cosine similarity
** Merging all texts of a user into one
** GPU
** Different libraries
* NLP sentiment - Emi & Bartek - TODO
* Time Series - Jacek - DONE

## TODO

* Sample 10% data
* 4th graph creation Agata
* 2 graphs (communities + degree distribution) Jacek + Bartek & Emi
* Sentiment/wordcloud Kuba
