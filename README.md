# Collaborative_Filtering_from_scratch
### Implemented the approach by reading the research paper:
**Empirical Analysis of Predictive Algorithms for Collaborative Filtering**.
<br>
### Approach:
1)I converted the dataset into a data frame format where rows represent users, columns
represent movies and values represent ratings.
<br>2)Fitted the dataset into Nearest Neighbor algorithm
<br>3)Created a nn function which calculates 15 nearest neighbors of each user and then
calculates the weight similarities between two user pairs at a time in a 2D matrix using the
formula given in homework research paper.
<br>4)Created a prediction function which takes userid and movieid as input and calculates
predicted movie rating based on the formula in the paper.
<br>
### Time taken to execute:
Took around 4 hours to find predictions of all test data points
in Google collab, might take more time in other IDE and environment
### Results:
RMSE on test (100478) data points: 0.9886979
<br>MAE on test data points: 0.790226 
### Dataset:
Netflix movie dataset
### How to Run:
For each file, please edit the Dataset path in the codes. Run each cell in the notebook file
### Code files:
Please refer the ipynb files for the precomputed outputs of every code if you like.
<br>1)collaborative_filtering.ipynb file: 
<br>This file contains the implementation of Collaborative Filtering as per the equation and concepts mentioned in the research paper given in the homework file.
 - predictions.txt file contains predictions of ratings on test data
