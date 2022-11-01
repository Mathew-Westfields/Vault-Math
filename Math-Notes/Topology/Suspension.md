#definition 
#topology 
#homotopy-theory 

# Definition
Let $X \in Top_*$ be a [[Topological Pairs#Pointed Spaces|pointed space]] we then call
$$ SX := X \wedge S^1$$ 
**the reduced suspension of $X$**

## Alternative construction
 We can also construct $SX$ by the quotient
 $$SX \homeo \frac{X \times I}{ X\times \partial I\cup \{x_0\} \times I} \homeo \frac{\Sigma X}{ q(\{x_0\} \times I)}$$
 So in a way the reduced suspension collapses Parts of the Domain of our Homotopy on which we want it to be constant, since we are working relative to a basepoint.

## Suspension Coordinates
For $q: X \times S^1 \lra X \wedge S^1$  and $\eta: I \lra S^1$ write:
$$x \wedge t := q(x,\eta(t))$$

# H-Cogroup Structure
The map $\gamma:SX \lra SX \vee SX$
$$\gamma(x\wedge t) =
\left\{
	\begin{array}{ll}
		(x\wedge 2t, *)  & \mbox{if } x \geq \frac{1}{2} \\
		(*,x\wedge 2t -1) & \mbox{if } x \leq \frac{1}{2}
	\end{array}
\right.$$
And the inverse mapping
$$ SX \lra SX$$
$$x \wedge t \mapsto x\wedge (1-t)$$
define an [[H-Spaces#H-Cogroup|H-Cogroup]] structure on $SX$.


# Remark
The [[Suspension#Alternative construction]] shows how it relates to the [[Unreduced Suspension]]