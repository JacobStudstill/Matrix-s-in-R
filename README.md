# Matrix-s-in-R

A <- matrix(c(2, 0, 1, 3), ncol = 2)
B <- matrix(c(5, 2, 4, -1), ncol = 2)

matrixAddition <- A + B

matrixAddition

<img width="144" height="69" alt="image" src="https://github.com/user-attachments/assets/07079b16-c42b-49f1-8392-3e561aabb63c" />


matrixSubtraction <- A - B

matrixSubtraction

<img width="179" height="78" alt="image" src="https://github.com/user-attachments/assets/233ca00a-0f19-4a21-b373-f43819392e5a" />


D <- diag(c(4, 1, 2, 3))

D

E <- diag(3,5)

E[-1,1] <- -2

E[1,-1] <- -1

E
