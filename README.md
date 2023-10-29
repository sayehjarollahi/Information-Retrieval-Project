# Information-Retrieval-Project

This is the final project for the Advanced Information Retrieval Course at Sharif University of Science and Technology. 

This project is for Retrieving information from public Github repositories based on their `README.MD` and `requirements.txt` files. 

It consists of different phases:
1. Public repositories in GitHub are crawled and preprocessed.(Code available in `Part1` directory) Then different representations are used including:
  * Boolean
  * TF-IDF
  * A transformer-based module
  * Fasttext
2. A query is given to the project and most related repositories to that query are retrieved using the above representations.(Code available in `Part1` directory)
3. Clustering and classification methods are applied to the repositories based on their `requirements.txt` files. (Code available in `Part2` directory)
4. Link analysis between repositories is applied. In this part, two famous algorithms, `Page Rank` and `HITS` are used to rank outputs of the search based on their relation with the query and each other. 
