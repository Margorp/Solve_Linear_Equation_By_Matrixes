# Solve_Linear_Equation_By_Matrixes

# Example

![](https://latex.codecogs.com/gif.latex?3x+2y-5z=12)

![](https://latex.codecogs.com/gif.latex?x-3y+2z=-13)

![](https://latex.codecogs.com/gif.latex?5x-y+4z=10)

let A = 
![](https://latex.codecogs.com/gif.latex?\begin{bmatrix}3&2&-5\\\\1&-3&2\\\\5&-1&4\end{bmatrix})

let B = 
![](https://latex.codecogs.com/gif.latex?\begin{bmatrix}12\\\\-13\\\\10\end{bmatrix})

det(A) = 
![](https://latex.codecogs.com/gif.latex?3\times\begin{bmatrix}-3&2\\\\-1&4\end{bmatrix}-2\times\begin{bmatrix}1&2\\\\5&4\end{bmatrix}+5\times\begin{bmatrix}1&-3\\\\5&-1\end{bmatrix})

det(A)=
![](https://latex.codecogs.com/gif.latex?-3((-3)(4)-(2)(-1))-(2)((1)(4)-(2)(5))+(-5)((1)(-1)-(-3)(5)))

det(A)=
![](https://latex.codecogs.com/gif.latex?-88)

adj(A)=
![](https://latex.codecogs.com/gif.latex?\begin{bmatrix}+\begin{bmatrix}-3&2\\\\-1&4\end{bmatrix}&-\begin{bmatrix}1&2\\\\5&4\end{bmatrix}&+\begin{bmatrix}1&-3\\\\5&-1\end{bmatrix}\\\\-\begin{bmatrix}2&-5\\\\-1&4\end{bmatrix}&+\begin{bmatrix}3&-5\\\\5&4\end{bmatrix}&-\begin{bmatrix}3&2\\\\5&-1\end{bmatrix}\\\\+\begin{bmatrix}2&-5\\\\-3&2\end{bmatrix}&-\begin{bmatrix}3&-5\\\\1&2\end{bmatrix}&+\begin{bmatrix}3&2\\\\1&-3\end{bmatrix}\end{bmatrix}^T)

adj(A)=
![](https://latex.codecogs.com/gif.latex?\begin{bmatrix}+((-3)(4)-(2)(-1))&-((1)(4)-(2)(5))&+((1)(-1)-(-3)(5))\\\\-((2)(4)-(-5)(-1))&+((3)(4)-(-5)(5))&-((3)(-1)-(2)(5))\\\\+((2)(2)-(-5)(-3))&-((3)(2)-(-5)(1))&+((3)(-3)-(2)(1))\end{bmatrix}^T)

adj(A)=
![](https://latex.codecogs.com/gif.latex?\begin{bmatrix}-10&6&14\\\\-3&37&13\\\\-11&-11&-11\end{bmatrix}^T)

adj(A) = 
![](https://latex.codecogs.com/gif.latex?\begin{bmatrix}-10&-3&-11\\\\6&37&-11\\\\14&13&-11\end{bmatrix})

![](https://latex.codecogs.com/gif.latex?\begin{bmatrix}x\\\\y\\\\z\end{bmatrix}=\frac{1}{det(A)}\cdot(adj(A))\cdot(B))

![](https://latex.codecogs.com/gif.latex?\begin{bmatrix}x\\\\y\\\\z\end{bmatrix}=\frac{1}{-88}\cdot(\begin{bmatrix}-10&-3&-11\\\\6&37&-11\\\\14&13&-11\end{bmatrix})\cdot(\begin{bmatrix}12\\\\-13\\\\10\end{bmatrix}))

![](https://latex.codecogs.com/gif.latex?\begin{bmatrix}x\\\\y\\\\z\end{bmatrix}=\begin{bmatrix}\frac{-10}{-88}&\frac{-3}{-88}&\frac{-11}{-88}\\\\\frac{6}{-88}&\frac{37}{-88}&\frac{-11}{-88}\\\\\frac{14}{-88}&\frac{13}{-88}&\frac{-11}{-88}\end{bmatrix}\cdot(\begin{bmatrix}12\\\\-13\\\\10\end{bmatrix}))

![](https://latex.codecogs.com/gif.latex?\begin{bmatrix}x\\\\y\\\\z\end{bmatrix}=\begin{bmatrix}\frac{(-10)(12)+(-3)(-13)+(-11)(10)}{-88}\\\\\frac{(6)(12)+(37)(-13)+(-11)(10)}{-88}\\\\\frac{(14)(12)+(13)(-13)+(-11)(10)}{-88}\end{bmatrix})

![](https://latex.codecogs.com/gif.latex?\begin{bmatrix}x\\\\y\\\\z\end{bmatrix}=\begin{bmatrix}\frac{-91}{-88}\\\\\frac{-396)}{-88}\\\\\frac{}{-88}\end{bmatrix})



![](https://latex.codecogs.com/gif.latex?\displaystyle\begin{bmatrix}x\\\\y\\\\z\end{bmatrix}=\begin{bmatrix}\frac{36}{11}\\\\\frac{52}{11}\\\\-\frac{20}{11}\end{bmatrix})
