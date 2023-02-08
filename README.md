# smart_decomposition
Decomposition of a matrix into a product of elementary matrices ヾ(≧▽≦*)o


Where matrix M you can get by doing a single row operation like alpha * ri -> ri to an identity matrix. <br>
Example: <br>
I = [[1, 0], [0, 1]]  <br>
op = -2 * r1 -> r1 <br>
Use our op to I and we get: M = [[-2, 0], [0,1]] <br>


And matrix A you can get by doing a single row operation like alpha * ri + rj -> rj to an identity matrix. <br>
Example:  <br>
I = [[1, 0], [0, 1]] <br> 
op = -2 * r1 + r2 -> r2 <br>
Use our op to I and we get: M = [[1, 0], [-2,1]]
