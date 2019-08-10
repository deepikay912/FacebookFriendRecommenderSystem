# Facebook Friend Recommender System

CMPE256 Individual project 

Dataset - Facebook
Technologies - Python
Machine - Google collab
Algorithm - collaboratiev filtering
Methods - Recommend by mutual friends & recommend by influence


Algorithm steps :

1. Two nodes are chosen at random.
2. Their friendship is removed from the graph.
3. Friend recommendations for F1 and F2 are computed.
4. Rank of F1 in F2's list of recommended friends is calculated.
5. Rank of F2 in F1's list of recommended friends is calculated.
6. Average of both rank is computed.
7. Friendship is put back to the graph.

The conclusion is that recommendation by influence is efficient and accurate.

More technical details are in docs folder files. 

