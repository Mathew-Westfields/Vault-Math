
Convention: $X^Y := C(X,Y)$ with $CO$-Topology

# Hom-Functors are well defined in CO-Top
For arbitrary spaces $X$,$Y$ with the maps $\phi:Y \lra Z$, $\psi: X \lra T$, the maps
$$\phi^X: Y^X \ra Z^X$$
$$ f \lmt \phi \o f $$
$$ Y^\psi:Y^T \lra Y^X$$
$$ f\lmt f \o \psi$$
Are **always continous**.

# Restriction of Domain and of Image
Let $i:A \hra X$ be an Inclusion of $A \subset X$ then:
$$Y^i:Y^X \lra Y^A$$ 
$$ f \lmt f \o i$$
is a continous function (Obviously $Y^i(f) = f|_A$ is the [[Presheaf#Definition|restriction map]]]).
And:
$$i^Y:A^Y \lra X^Y$$
$$ f \lmt i \o f $$
is a continous embedding. (so in a way $A^Y =C(Y,A) \subset C(Y,X) = X^Y$)

# C(X,Y) with Products and Sums
Let $(Y_i)$ be a family of top spaces and $X$,$Z$ top spaces.
If $X$ is [[Local Compactness#Strong Locally Compact|strong locally compact]] the map
$$C(X,\prod_{i\in I}Y_i) \lra \prod_{i \in I}C(X;Y_i) $$
$$ f \lmt (p_i \o f)_{i\in I} $$
is a homeomorphism.
The map:
$$C(\coprod_{i\in I}Y_i,Z) \lra \prod_{i \in I}C(Y_i,Z) $$
$$ g \lmt (g \o j_i)_{i\in I} $$
is always an homeomorphism
