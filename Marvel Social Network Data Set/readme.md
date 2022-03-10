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
This project will be largely an exploratory analysis of this data set.
A very common application of community detection is applying these algorithms to social networks, either for marketing or data mining purposes.

You're given a 'social network' of Marvel super heros, explore some topics in social network analysis applied to this graph.
Using the 'hero-network.csv' data, generate a network and explore this network.

If you use any algorithms not described in class, make sure to include an explanation.

_Possible Questions:_
- Describe any pattern you see in the communities. Is there a clear pattern to the clustering? 
- Describe the network, how connected are the groups? What is a good quantification for what you're seeing?
- Which are the more influential nodes inside the different communities?
- (Hard) Create a directed graph with the 'hero-network' data set and explore this network.
- (Harder) Create a bipartite graph with the 'nodes.csv' and 'edges.csv' data, explore this bipartite graph.

## Possible Resources
Python
- Google Colab, for collabrative coding environment https://colab.research.google.com/
- Networkx, for generating graphs https://networkx.org/
- CDLib, for community detection https://cdlib.readthedocs.io/en/latest/

Useful Links:
- 'Marvel Universe looks almost like a real social network' (Alberich et al., 2002) https://arxiv.org/pdf/cond-mat/0202174.pdf
- https://en.wikipedia.org/wiki/Social_network_analysis
