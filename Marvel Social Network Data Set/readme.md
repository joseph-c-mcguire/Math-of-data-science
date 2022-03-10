# The Data
The original kaggle: https://www.kaggle.com/csanhueza/the-marvel-universe-social-network

## "hero-network.csv"
Contains two columns "hero1" and "hero2", two heros share a row in the data if they appeared in the same comic book as each other.
This will be the primary data set to focus on in this project.

## "nodes.csv"
This contains the names of heros and comic books, and their associated type.
For example, "8-BALL/" is a Hero type node, while "A '00" is a comic type node.

## "edges.csv"
This contains a list of heros that appeared in which comic book.
That is "3-D MAN/CHARLES CHAN" appeared in Marvel comic book "AVF 4".


# The Project

## Community Detection
This project will be largely an exploratory analysis of this data set, a very common application of community detection is applying these algorithms to social networks.
You're give a 'social network' of Marvel super heros
Using the 'hero-network.csv' data, explore the community structure of the network. Using CDLib or any other Python resources, explore different algorithms for community detection.

_Possible Questions:_
Describe any pattern you see in the communities.
Which are the more influential nodes inside the different communities.
(Harder) Is there a clear community structure in the bipartite graphs obtained from the 'nodes
