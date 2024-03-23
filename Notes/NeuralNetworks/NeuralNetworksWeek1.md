# What is a Neural Network ?


# Binary Classification
### Vectors and matrices
A Matrix is a 2D rectancgular array , with m rows and n columns
A vector is a special type of matrix. A row vector is a matrix of 1 rows and n columns
A column vector is a matrice of m rows and 1 column
### Notation
(x,y) : single training sample
x -> x dim feature vector, y the label
m -> num training examples (x,y)...(x(m), y(m))


small x -> represent a single feature vector
In the case of an image it is the pixel values of all the channels stacked together in a row vector of len (image.shape * 3(3 colors channels))
looks like :
[255]
[117]
[34]
[56]
[nx]

big X -> (nx,m dim matrix)
Is the dataset of inputs 
A matrix (nx,m) matrix containing m samples of nx dim row vectors

looks like
[255][213][123][m]
[117][200][132][m]

Big Y (1, m) dim column vector 
[cat][dog][cat][m]
