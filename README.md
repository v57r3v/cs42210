java c
Optimization and Algorithms
November 25, 2021
Exam
1. Nonconvex function. (3 points) One of the following functions f : R → R is not convex:
(A) f(x) = (x2 − x)+ − x
(B) f(x) = − ((x+))2 + x2 + x
(C) f(x) = (x − x+)2 − x
(D) f(x) = ((x+))2 − x2 + x
(E) f(x) = x+ + x2 − x
(F) f(x) = (x + x+)2 − (x+)2
Which one?
Write your answer (A, B, C, D, E, or F) here:                                      
2. Least-squares. (2 points) Consider the following six optimization problems:

In each of the six problems above, the variable to optimize is x ∈ Rn. The matrices A and B, and the vector c are given. The scalar ρ is also given and is positive: ρ > 0.
One of the optimization problems above is not a least-squares problem.
Which one?
Write your answer (A, B, C, D, E, or F) here:                              
3. Optimal value of a constrained problem. (3 points) Consider the constrained problem

where the variable to optimize is (x1, . . . , xN ), with xn ∈ Rdfor 1 ≤ n ≤ N. The matrices Rn ∈ Rd×d are given for 1 ≤ n ≤ N. Assume that each Rn is a symmetric, positive-definite matrix. The vector s ∈ Rdis also given.
One of the following expressions is the minimum value that f attains over the feasible set, that is, one of the following expressions is the number min{f(x1, . . . , xN ): x1 + · · · + xN = s}:

Which one?
Write your answer (A,代 写Optimization and Algorithms 2021 ExamR
代做程序编程语言 B, C, D, E, or F) here:                              
4. Sparse linear regression with asymmetric loss. (4 points) Consider the optimization problem

where the variable to optimize is (s, r) ∈ Rn × R. The vectors xk ∈ Rn and the scalars yk ∈ R are given for 1 ≤ k ≤ K. The scalars α, β, and ρ are given and denote positive constants: α > 0, β > 0, and ρ > 0. The functions (·)− and (·)+ are defined as (z)− = max{−z, 0} and (z)+ = max{z, 0} for z ∈ R.
Show that the function f is convex.
5. A simple control problem. (4 points) Consider the optimization problem

where the variables to optimize are xt ∈ Rnfor 1 ≤ t ≤ T and ut ∈ Rpfor 1 ≤ t ≤ T − 1. The vector xinitial ∈ Rn and the matrices Dt ∈ Rn×p are given for 1 ≤ t ≤ T − 1. The scalar ρ is also given and denotes a positive constant: ρ > 0.
Give a closed-form. solution for the optimal {ut: 1 ≤ t ≤ T − 1}.
6. Moureau envelope. (4 points) Let f : R → R be a convex function. For λ > 0, we define a function eλ[f]: R → R as follows: for x ∈ R, the image of x under the function eλ[f] is the number min{f(u) + 2λ/1 (u − x)2: u ∈ R}.
That is, the function eλ[f] maps each number x to the number eλ[f](x), where eλ[f](x) is the minimum value attained by f(u) + 2λ/1 (u − x)2 as u varies in R.
Let λ1 > 0 and λ2 > 0. Show that
eλ1[eλ2[f]](x) = eλ1+λ2[f](x),
for each x ∈ R.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
