# cindy
tarea

#makeCacheMatrix: This function creates a special "matrix" object that can cache its inverse.

#n=tamaño de la matriz
n=3
#v= vector de valores
v=c(2,1,1,4,2,-1,2,0,1)
v=c(1:9)

x = matrix()
x=matrix(v,n,n)

makeCacheMatrix <- function(x) {
    if (det(x)!=0) { 
      print(x)
    } else {
      print=c("no se puede, el determinante es igual a 0")
    }
  }
makeCacheMatrix(x)

cacheSolve <- function(x) {
x_1=solve(x)
x_1
}
