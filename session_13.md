# Linear Algebra
## Key Concepts
## Scalars
## Vectors
- Push or force in certain direction
- Lives in an abstract vector space
- Direction in abstract sense
- Can be 2D, 3D, ..., ND
- Notation basics
- Row vector, column vector
- Basis of vector
    - In terms of fundamental components: linear independance
    - Changing of basis
- Distance of a point from origin
- Magnitude/norms of vectors $L_1$ and $L_2$ norm, $L_p$ norm
- Unit vector
- Distance between points
    - Euclidean distance
    - Manhattan distance
- Dot product of vectors
    - $a \cdot b = \sum_i a_i b_i$
    - $a \cdot b = \Vert a\Vert \Vert b \Vert \cos \theta$
    - Angle between two vectors
    - Concept of orthogonality
- General equation of line/plain
    - why weights of general forms normal to the plane

- Operations on vectors
    - Projection of a vector $a$ into vector $b$ 
    - $d = \frac{a \cdot b}{\Vert b \Vert} = \frac{\Vert a \Vert \Vert b \Vert \cos \theta}{\Vert b \Vert} = \Vert a \Vert \cos \theta$

- Matrices as Transformation on vectors
- Matrix multiplication as reversible/irreversible AB!=BA
- Inverse of Matrix
- Eigen values and eigen vectors
- Matrix Factorization
    - SVD/UV


## Practice Problems on Vectors and Matrices

### 1. Basic Concepts of Scalars and Vectors
1. Identify which of the following quantities are scalars and which are vectors:  
   - (a) Temperature  
   - (b) Velocity  
   - (c) Force  
   - (d) Distance  

2. A force **F** = (3, -4) N is applied to an object. What is the magnitude of this force?

---

## 2. Vectors in Abstract Spaces
3. Given two vectors in 3D space:  
   $\mathbf{a} = (2, -1, 3), \quad \mathbf{b} = (-4, 2, 1)$
   
   Find:  
   - (a) Their sum **a + b**  
   - (b) Their difference **a - b**  
   - (c) $3\mathbf{a} - 2\mathbf{b}$  

---

## 3. Linear Independence and Basis
4. Are the vectors $(1,2)$ and $(2,4)$ linearly independent? Justify your answer.

5. Consider the vectors $(1, 2, 3)$, $(4, 5, 6)$, and $(7, 8, 9)$. Are they linearly independent?

6. Given the standard basis vectors  
   $e_1 = (1,0,0), \quad e_2 = (0,1,0), \quad e_3 = (0,0,1)$
   
   express $(4, -2, 7)$ as a linear combination of $e_1, e_2, e_3$.

---

## 4. Distance and Norms
7. Compute the **L1 norm** and **L2 norm** of the vector $v = (3, -4)$.

8. Compute the Euclidean distance between points $P(1,2)$ and $Q(4,6)$.

9. Find the Manhattan distance between $(3,5)$ and $(-1,2)$.

---

## 5. Dot Product and Orthogonality
10. Find the dot product of  
    $a = (2, -3, 1), \quad b = (-1, 4, 2)$

11. If two vectors **a** and **b** are orthogonal, what should their dot product be? Verify if  
    $(1, 2, 3) \quad \text{and} \quad (-2, 1, 0)$
    are orthogonal.

12. Given vectors **a** and **b**, show that:
    $a \cdot b = \|a\| \|b\| \cos \theta$
    
    and use this to compute the angle between  
    $a = (3,4), \quad b = (5,12)$

---

## 6. Vector Projection
13. Find the projection of  
    $a = (2, 3) \quad \text{onto} \quad b = (1,1)$

14. Compute the component of  
    $a = (4, 2, 6) \quad \text{along} \quad b = (1,1,1)$

---

## 7. Equations of Lines and Planes
15. Write the parametric equation of a line passing through points  
    $P(1,2,3) \quad \text{and} \quad Q(4,5,6)$

16. Find the equation of a plane passing through  
    $(1,2,3) \quad \text{and normal to the vector} \quad (4,-2,1)$

---

## 8. Matrix Transformations
17. If  $$A = \begin{bmatrix} 2 & 1\\ 0 & 3 \end{bmatrix}, \quad B = \begin{bmatrix} 1 & 4 \\ 2 & 0 \end{bmatrix}$$

Compute $AB$ and $BA$. Are they equal?

18. Find the inverse of  
    $$A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$$ 
    if it exists.

19. Compute the eigenvalues and eigenvectors of  
    $$A = \begin{bmatrix} 2 & 1 \\ 1 & 2 \end{bmatrix}$$


