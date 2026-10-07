The primary analysis is contained in the R Markdown file:
 
- `Multivariate_Statistics_and_Machine_Learning.Rmd`

This repository contains a third-year undergraduate assessment completed as part of Multivariate Statistics and Machine Learning at the University of Manchester.

This is was assessment of PCA transformation in R to reduce a 3,000 image MNIST subset of digits 5, 6 and 7 from 784 to 20 dimensions, however there is also a use of K-means and hierarchical clustering against true labels (of the respective digits).

To run the code, download `digit.txt` and ensure that its file path is correctly specified in the script: 
read_mat <- as.matrix(read.table("digit.txt", sep = ","))
