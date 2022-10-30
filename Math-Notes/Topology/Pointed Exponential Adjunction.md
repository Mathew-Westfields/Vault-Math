#definition 
#topology 
#algebraic-topology 
#homotopy-theory 

# Recall
Recall [[Topological Pairs#Pointed Spaces]] as well as [[Exponential-Adjunction#Definition]].
Write $C_*(X,Y) := C(X,*_X;Y,*_Y) \subset C(X,Y)$ as subset of CO-Top
# Definition
Let $(X,x_0),(Y,y_0),(Z,z_0) \in Top_*$
Then the [[Exponential-Adjunction#Definition| exponential adjunction]] in $Top_*$ is given by:
$$ (\cdot)^\vee:C_*(X,C_*(Y,Z)) \lra C_*(X \wedge Y,Z)$$
since  given a pointed map $f: X \lra C_*(Y,Z)$
$$ f^\vee:X \times Y \lra Z \text{ sends } X \vee Y \lmt z_0 $$
And clearly 
$$g \in C(X \times Y, X\vee Y; Z,z_0) \Lra g^{\wedge}:X \lra C(Y,Z) \in C_*(X,C_*(Y,Z))$$


# Identification
Let $(X,x_0),(Y,y_0),(Z,z_0) \in Top_*$
## Bijection
and Y [[Local Compactness#Strong Locally Compact|strong locally compact]] then it follows that:
$$ C_*(X \wedge Y,Z) \xleftrightarrow{1:1} C_*(X,C_*(Y,Z))$$
in the subspace topology of the CO-Top
## Homeomorphism
and X,Y [[Local Compactness#Strong Locally Compact|strong locally compact]] then it follows that:
$$ C_*(X \wedge Y,Z) \homeo C_*(X,C_*(Y,Z))$$
in the subspace topology of the CO-Top