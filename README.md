# Book_Recommendation_system
This project aims to build a book recommendation system using collaborative filtering techniques, particularly K-Nearest Neighbors (KNN) algorithm.

Dataset
The dataset used for this project is http://www2.informatik.uni-freiburg.de/~cziegler/BX/, which contains 3 tables they are books,users and ratings. In which it contains 271360 books,278858 ussers and 1149780 ratings

Requirements
The following packages are required to run this project:
pandas
numpy
scikit-learn
Scipy

Usage
To run the recommendation system, you can simply execute the Book recommendation Syayem.ipynnb file. The system will prompt the user to enter a book title, and then return the top 5 recommended books based on collaborative filtering.

Methodology
The recommendation system is built using the K-Nearest Neighbors (KNN) algorithm, which is a popular technique for collaborative filtering.Here i narrowed the no of books,users based on no of books read by users>200 and no of ratings given to a book>50. The algorithm works by finding the k most similar items (in this case, books) to the user's input, and then recommending items that those similar items have been rated highly by other users.
Here we used sparse,csr_matrix packages to create a matrix in which contains user_id in columns and Title of book in rows and created a pivot table.


Conclusion
The book recommendation system built using collaborative filtering and KNN algorithm can effectively recommend books based on the user's input.
