# A Note for Abstract Algebra  
## Meterial List
* Lieback
* Rotman - Group
* Rings Notes 
* Midterm 

Additional material: e-book from wechat group contribute by Fanlue. It might be useful when having no problem sheets and solutions.

## Chapters and Contents
1. Lieback  
    * Chapter 19
    * Chapter 20
    * Chapter 25
    * Chapter 26
1. Rotman - Groups
    * Subgroup
    * Lagrange 
    * Cyclic Groups
    * Normal Groups
    * Isomorphism 
    * Correspondence 
    * Quotient Groups
    * Direct product 
    * Conjugates 
    * G_set 
    * Symmetric Groups
    * Corollay Burnside 
    * Burnside Lemma 
    * Burnside Colouring Flag
    * Burnside 4 $\times$ 4
    * Burnside Bracelet
2. Ring Notes 
    * Rings 1 - 8 
    * Rings 2.3 - 2.12
    * Foctorisation 
    * Ishort 
    * Division in quadratic integers

**Note that:** ***groups actions*** and ***Burnside's Lemma*** ( **Section factorisation in integral domains** ) are not examinable!!!
 
 ---
 
 
## **Groups**
 This part is the most important and abundant part. Problems mainly have no solutions.

 
1. ***Permutation* and *cycles***
2. ***Transportation***
3. ***Disjoint = Commute:***
    if $\alpha(x) \neq x$, then all $\beta(x)=x$
4. ***Cancellation Law:***  if either $\alpha\beta=\alpha \gamma$ or $\beta \alpha=\gamma\alpha$ $\beta=\gamma$
5. ***Regular permutation:*** $\alpha=1$ or $\alpha$ is a product of disjoint cycles.
6. ***Even/odd permutation:*** Even/Odd numbers of $r$-cycles, where $r$ is an even number.
7. ***Group:*** 
   * **Closure Axiom:** for any $\alpha, \beta \in G, \text{ then } \alpha \beta \in G$
   * **Associative Axiom:** for $\forall \alpha,\beta\in G, (a*b)*c=a*(b*c)$
   * **Identity Axiom:**  for $\exist e\in G, \text {such that } a*e=e*a=a$, for all $a\in G$
   * **Inverse Axiom** for $\forall a\in G$ there exist $b\in G,\, s.t., \, a*b=b*a=e$
8. ***Semi-group:*** Associative Axiom 
9.  $\bf{S_x\,S_n}$**: *Symmitric Group*** permutation groups
    $\bf{A_x\,A_n}$**: *Alternating Group*** ) **even** permutation groups
10. ***Comute=ablelian***
11. - [ ] ***Congruence Class*** $\bf{Z_m}$
12. - [ ] **Unit** in Ring 
13. ***Four Group***
14. ***Multiplication table***
    **NB:** $a_{row}*a_{colum}$
15. ***Homomorphism:*** $f(a*b)=f(a)\circ b$
16. ***Isomorphism*** $\cong$***:*** Homomorphism & Bijection  
    ***Imbedded:*** $S$ an be imebedded in $G$ $\Leftrightarrow$ $S \cong G'$, where $G'\leq G$ 
17. ***Subgroup:*** $S\leq G$ 
    **Determine:** 
    1. if $s,t \in S$, then  $s^{-1}\in S$ and $st\in S$ $\Rightarrow X\leq G$ 
    2. $1\in S$ and if $s,t \in S$ then  $st^{-1}\in S \Rightarrow S \leq G$
    3. G is a **finite** group and if $s,t\in G$ then $st\in S \Rightarrow S \leq G$
18. ***Cyclic (Sub)Group:*** $<a>$  
    ***Subgroup generated by $a$:*** $<A>$
19. ***Order: number of elements***  
    ***Index: $[G:S]$, number of (right) cosets of $S$ in $G$***  
    ***Exponent: $x^n=1$ for all $x\in G$***
20. ***Proper:*** Subgroup $\neq$ Group
21. ***Trivial:*** Subgroup $1$
22. ***Kernel:*** $kerf =\{a \in G : f(a)=1\}$
    ***Image:*** $Im f=
    \{h\in H : h=f(a)\}$
    **NB:** For $G \rightarrow S$, $kerf\in G$ and $Imf \in H$
23. ***Word:*** A conception to build $<X>$, for a subset X of a group G, $w=x_1^{e_1}x_2^{e_2}x_3^{e_3}x_4^{e_4} \cdot\cdot\cdot x_n^{e_n}$, where $x_i \in X, e_n=\pm1$, then $<X>$ is either 1 if $X=\empty$, or $<X>=\{$all *words* of $X\}$
24. ***General linear Group$GL(n,k)$:***  **N.B. $k$ is a *field*.**  $GL(n,k)=(A,\times)$, where $A=\{\textit{n×n matrix: all entries(or say elements) } a\in k \}$  
    ***Special Linear Group$SL(n,k)$:*** matrices have determine 1.  
    **N.B.** for $n=1, GL(n,k)$ is **abelian** and $n\geq 2,GL(n,k)$ is ***NOT* Abelian**  
25. ***(Right) Coset of S:*** $St=\{st:s\in S\}$, $t$ is called representative.










<br>  

---  

<br>  

## Rings  
1. ***Ring*:** $(F,+,\cdot )$ is a ring if:  
   * $(R,+)$ is a *Group*;
   * $(R,+)$ is a *Semigroup*;
   * $\forall a,b,c,\, a(b+c)=ab+ac$ and $(a+b)c=ac+bc$  
2. ***Devision Ring*:** $\forall a\neq 0, \exist b, \, s.t. \, ab=ba=1$
3. ***Field*:** Commutative division ring.
4. ***Subring:***   
    * $R$ is a *ring*, $S\subset R$
    *  $0,1\in S$
    *  for $\forall s,t \in S$, $s+t,st,s-t\in S$  
5. ***Integral domain*:** 
   1. $R$ is commutative
   2. $0\neq 1$
   3. $R$ has ***NO*** zero divisor
6. ***Examples:***  

    **Rings:**   
    * $\mathbb{Z,Q,R,C}$
    * $\mathbb{R}[x]$ (polynomials with real coeffcients)
    * $M_n(R)$ (Matrix ring, considering $GL(n,k)$) e.g. $M_2(R),M_3(R)...$
    * $\mathbb{Z}/m\mathbb{Z}=\{[0]_m,[1]_m,...[m-1]_m\}$ *(Residue Class Rings)* **N.B.: $m>1$ can be non-prime integer** e.g. $\mathbb{Z}/2\mathbb{Z},\mathbb{Z}/3\mathbb{Z},...$  

    **Division Rings:**  
    * $\mathbb{C,Q,R}$  

    ***NOT* Division Rings:**  
    * $\mathbb{Z}$
    * $\mathbb{R}[x]$  

    **Subrings**  
    * $\mathbb{Z}$ of $\mathbb{Q}$
    * $\mathbb{Q}$ of $\mathbb{R}$
    * $\mathbb{R}$ of $\mathbb{C}$
    * $\mathbb{Z}[\sqrt d]$ of $\mathbb{C}$
    * $\mathbb{Q}[\sqrt d]$ of $\mathbb{C}$ **(Also a field)**
7. ***Left/Right Zero Divisor*:** $a\neq 0$ is called left zero divisor if $\exist b \neq 0, s.t. \, ab=0$
8. ***Unit*:** ab=ba=1 **no need for left/right**  
    $R^*$: group of units.
9.  ***A finit integral domain is a field*:**  
    - [ ] *Proof*: Find inverse. 
      
    $\Rightarrow$ The ring $\mathbb{Z}/m\mathbb{Z}$ is a field iff $m$ is prime.  
10. 
11. ***Ring homorphism*:**  
    * $\gamma(0)=0,\gamma(1)=1$  
    * $\gamma(a+b)=\gamma(a)+\gamma(b)$
    * $\gamma(ab)=\gamma(a)\gamma(b)$