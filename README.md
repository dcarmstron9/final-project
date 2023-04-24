# final-project
Our goal was to simulate the Netflix recommendation system to be able to give suggestions of other shows and movies that a user should watch based on their previous watch history. To accompolish this, we used two different algorithms: cosine similarity and jaccard similarity. Cosine similarity is used to measure the cosine of the angle between vectors, which is a value between 1 and -1, projected in a multi-dimensional space. To measure the cosine similarity, you take the dot product and divide it by the magnitudes of each vector. In the context of our machine learning algorithm it is used to compare the similarity of the movies/shows. A value closer to 1 indicates high similarity and a value closer to -1 indicates low similarity. The Jaccard similarity is found using this formula: J(A,B)= |A∩B| / |A∪B|. Where |A∩B| is the intersection of A and B, which gives the number of members shared between both sets.
|A∪B|, which is the union of A and B, gives the total number of members in both sets (shared and unshared). The Jaccard Similarity will be 0 if the two sets don't share any values and 1 if the two sets are identical. The set may contain either numerical values or strings. We can also use this formula to find the dissimilarity between two sets by calculating d(A,B)=1–J(A,B). 

To run the program, you input a tv show or movie and the algorithm will use either cosine similarity or jaccard similarity and return suggested films or tv shows. 


Group Member Contributions:
We completed the project on zoom with everyone in attendance for all meetings and we worked through all of the code and complications that we faced together. Everyone also contributed to the slides as well as the code and creating the graphics for the presentation. When we received feedback from instructors, we collaborated to decide what our best course of action would be to complete the project. 
