#theorem 
#analysis

# Theorem
Let $f\in C^k(\R^n,\R)$ and $a \in \R^n$ then there exists a function $R_\alpha:\R^n \lra \R$ such that
$$ f(x) = \sum_{|\alpha| \leq k} \frac{D^{\alpha}f(a)}{\alpha!}(x-a)^{\alpha} + \sum_{|\alpha| = k+1}R_{\alpha}(x)(x-a)^{\alpha}$$

## Error Term Estimate
If $f\in C^{k+1}(B^n_r(a),\R)$ one can find a formular for $R_\alpha$ and estimate it's size.
$$R_\beta(x) = \frac{|\beta|}{\beta!} \int_0^1 (1-t)^{|\beta| -1}D^{\beta}f(a+t(x-a))dt$$
with the estimate
$$ |R_\beta(x)| \leq \frac{1}{\beta!}\max_{|\alpha| = |\beta|}\max_{y \in B^n_r(a)}|D^\alpha f(y)|\text{ for }x\in B_r^n(a)$$

# Algebro-Geometric Interpretation
Taylors Theorem tells us that the [[Sheaf]] of Differentiable Functions  around a point looks like the [[Sheaf]] of Polynomial functions.
So for$f,g \in \mathcal{A}_M$ on a differentiable Manifold $M$ locally around $p \in M$ look like their Taylor Polynomials.
That is $$\mc{A}_p / I_{k+1,p} \cong \R[z_1\ldots z_n]/(z_1, \ldots, z_n)^{k+1}$$
This is the essential Motivation for the definition of [[k-Jets]].
Especially this implies the following for the [[Cotangent Sheaf]]
$$\mathcal{T}^* \cong Hom(Der(\mc{A}),\R)$$




