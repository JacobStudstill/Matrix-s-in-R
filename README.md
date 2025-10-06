# Matrix-s-in-R

A <- matrix(c(2, 0, 1, 3), ncol = 2)
B <- matrix(c(5, 2, 4, -1), ncol = 2)

matrixAddition <- A + B

matrixAddition

matrixSubtraction <- A - B

matrixSubtraction

D <- diag(c(4, 1, 2, 3))

D

E <- diag(3,5)

E[-1,1] <- -2

E[1,-1] <- -1

E
