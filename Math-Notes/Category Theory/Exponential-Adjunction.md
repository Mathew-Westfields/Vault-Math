#definition 
#category-theory 

# Definition
Let $A,B,C$ be Sets then we define the maps:
$$(\cdot)^{\vee}:Map(A,Map(B,C)) \lra Map(A \times B, C)$$ by mapping $f \lmt f^{\vee}$ with $f^{\vee}:A\times B \lra C$ by $f^{\vee}(a,b) = f(a)(b)$
$$(\cdot)^{\wedge}: Map(A \times B, C)\lra Map(A,Map(B,C))$$
by mapping $F \lmt F^{\wedge}$ with $F^{\wedge}:A\lra Map(B,C)$ by $F^{\wedge}(a) = F(a,\cdot)$
Are called the **Exponential Adjunction** on the Category $Set$.

# Elementary Properties

The Maps $(\cdot)^{\vee}$ and $(\cdot)^{\wedge}$ are bijective inverses to each other so:
$$ (f^{\vee})^{\wedge} = (f^{\wedge})^{\vee} = f $$

## Remark
$Map(X,Y) = Y^X$ is the [[Exponential-Object]] in the Category $Set$.
The Isomorphism above then reduces to the following **Exponential Law**
$$(C^B)^A \cong C^{A \times B}$$