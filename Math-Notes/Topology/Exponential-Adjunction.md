# Exponential-Adjunction
## Definition
Let $A,B,C$ be Sets then we define the maps:
$$(\cdot)^{\vee}:Map(A,Map(B,C)) \lra Map(A \times B, C)$$ by mapping $f \lmt f^{\vee}$ with $f^{\vee}:A\times B \lra C$ by $f^{\vee}(a,b) = f(a)(b)$
And

$$(\cdot)^{\wedge}: Map(A \times B, C)\lra Map(A,Map(B,C))$$
by mapping $F \lmt F^{\wedge}$ with $F^{\wedge}:A\lra Map(B,C)$ by $F^{\wedge}(a) = F(a,\cdot)$
Are called the **Exponential Adjunction** on Set.

The Maps $(\cdot)^{\vee}$ and $(\cdot)^{\wedge}$ are 

### Remark
Often one uses the Notation $Map(X,Y) = Y^X$
Then this breaks down to 
$$(C^B)^A \cong C^{A \times B}$$