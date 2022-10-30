#theorem 
#analysis 

# Theorem
Let $x,y \in U \subset \mathbb{R}^n$ open such that: $[x,y] \subset U$ and $f: U \longrightarrow \mathbb{R}$ differentiable.
Then there exists a $\xi \in [x,y]$ such that:
$$\Longrightarrow f(y) - f(x) = \nabla f(\xi)\cdot(y-x)$$

## Inequality
$$|f(y) - f(x)| = |\nabla f(\xi)||y-x| \Longrightarrow |f(y) - f(x)| \leq \sup_{v \in [x,y]} |f(v)||y-x|$$

## Integral Version
Let $f: [a,b] \longrightarrow \mathbb{R}$ continous and $g: [a,b] \longrightarrow \mathbb{R}$ integrateable
with $sgn(g) \equiv const$ then there exists a $\xi \in [a,b]$ such that:
$$\int_a^b f(x)g(x)dx = f(\xi) \int_a^b g(x)dx $$
Especially for $g \equiv 1_{[a,b]}$
$$\Longrightarrow\int_a^b f(x)dx = f(\xi)|b-a| $$
