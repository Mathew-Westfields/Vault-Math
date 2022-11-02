#topology 
#homotopy-theory 
#algebraic-topology 
#theorem 

# Adjunction
Let $(X,x_0),(Y,y_0),(Z,z_0) \in Top_*$ and Y [[Local Compactness#Strong Locally Compact|strong locally compact]].
Also with $q:X\times Y \lra X \wedge Y$ it follows that:
$$ [X \wedge Y,Z]_* \xleftrightarrow{1:1} [X,C_*(Y,Z)]_*$$
$$ [f] \lmt [(f \o q)^{\wedge}]$$
is a well defined bijection

# Homotopy Classes of Maps into H-Groups
Let $X \in Top_*$ and $Y$ [[H-Spaces#H-Group|H-Group]]  $\Lra [X,Y]_*$ is a Group with:
$$[f] \cdot [g] = [x \lmt f(x) \cdot g(x)]$$
$$1 = [x \lmt e]$$
$$[f]^{-1} = [( \hat \cdot) \o f]$$

# Homotopy Classes of Maps out of H-Cogroups
Let  $X$ [[H-Spaces#H-Cogroup|H-Cogroup]]  and $Y \in Top_*$ $\Lra [X,Y]_*$ is a Group with:
$$[f] * [g] = [\nabla_Y \o (f \vee g) \o \gamma]$$
$$1 = [c]$$
$$[f]^{-1} = [ f \o i]$$

# Abelian Homotopy Groups

Let  $X$ [[H-Spaces#H-Cogroup|H-Cogroup]]  and $Y$ [[H-Spaces#H-Group|H-Group]]  $\Lra [X,Y]_*$ is an abelian Group with 
$$[f] \cdot [g] = [f]*[g]$$

# Trading Suspensions for Pathspaces
Let $X,Y \in Top_*$ then using the [[Pointed Exponential Adjunction]]
$$ \alpha:[SX,Y]_* \lra [X, \Omega Y]_*$$
$$[f] \lra [ (f \o q)^{\wedge}]$$
is a Group-Isomorphism thus $[SX,Y]_* \iso [X, \Omega Y]_*$
