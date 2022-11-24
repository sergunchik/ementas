## Elliptic modular forms and their applications

### Program:

1. Modular groups, modular functions, modular forms. Fundamental domains. Finite dimensionality of spaces of modular forms.
2. Eisenstein series. The discriminant, Ramanujan’s Delta and tau functions. Dedekind’s eta-function.
3. Theta-series.
4. Hecke eigenseries and L-series.
5. Differential operators: derivatives of modular forms, Rankin-Cohen brackets, quasi-modular forms.
6. Complex multiplication.

Possible bonus topics: Jacobi modular forms and heat equation.
Functional equation for Riemann's zeta-function
(as a quick corollary of modularity of Jacobi theta function).

#### For whom

Course might be useful for those interested in applications of classical complex analysis to arithmetics and geometry, combinatorics, algebra, differential equations, algebraic geometry and mathematical physics.



#### Teaser: modular form as the fifth element

Fermat Last Theorem claims that the equation $x^n+y^n=z^n$ does not have natural solutions for $n>2$.
Based on Frey's trick, Serre and Ribet reduced it to *modularity conjecture* of Taniyama, Shimura and Weil,
whose solution was announced/finished in 1994/2001 by Wiles, Taylor, Diamond, Conrad, Breuil,
and which is now known as *modularity theorem*.

> Ken Ribet: The argument by Wiles and Taylor–Wiles made crucial use of *modular forms*, a magic power of number theory that was described by Martin Eichler (1912–1992) as the fifth fundamental operation of number theory.

> Andrew Wiles: There's a saying attributed to Eichler that 
**there are five fundamental operations of arithmetic: addition, subtraction, multiplication, division, and modular forms.**

> Barry Mazur: *Modular forms* are functions on the complex plane that are inordinately symmetric. They satisfy so many internal symmetries that their mere existence seem like accidents. But they do exist.

> Ken Ribet: Modular forms are special functions that are analogous to the trigonometric functions like $\sin, \cos, \tan,...$ in that they are periodic in the same way that $\sin$ is periodic. (Recall the formula $\sin(z + 2π) = \sin(z)$.) Modular forms have the periodicity of the trigonometric functions plus enough extra symmetries that they are essentially unchanged under a large group of substitutions.
Because of the symmetries, it is possible to write modular forms as Fourier series
$\sum_{m=0}^\infty a_m q^m$, where the “q” here is a shorthand for $\exp(2πiz)$.

In fact, in Eisenstein's approach the exponential $\exp$ and the trigonometric functions
are constructed from scratch as a toy model for further development of the theory of modular forms,
with new proofs of some beautiful formulae of Leonhard Euler. Weil retells this story in first chapter of his book.


The theory of modular forms and elliptic functions / curves was started in early 19th century in the works of Abel, Jacobi, Riemann, Eisenstein, Kronecker, Dedekind, Weierstrass.

By the end of 19th century modular forms were conceptualized as the simplest example of automorphic form
by Klein, Fricke, and Poincaré. 
Early 20th century saw important contributions by Ramanujan (and Hardy, Littlewood),
and especially Hecke.  These three periods of the development of the theory of modular forms that took
a little more than a century is the classical core of the course.

A part of the theory of modular forms, a theory of theta-series
is much related to the theory of integer quadratic forms.
It starts from Gauss's study of binary and ternary quadratic forms in his Disquisitiones Arithmeticae,
includes the construction of E8 lattice of Korkin-Zolotarev in 19th century,
and Leech lattice and Niemeyer's lattices of rank 24 in 20th century.
One of the application of basic theory of modular forms is an easy proof of classification
of Niemeyer lattices by Boris Venkov, one of the short applications in the course.
The last decade's proofs that Korkin-Zolotarëv and Leech lattices provide
the densest sphere-packings in dimensions 8 and 24 by Viazovska, Radchenko and others
is also based on construction of explicit nice modular forms.


In 20th century important development is the program of Langlands (1960s-now)
of which Modularity Theorem is now seen as one of first solved parts,
and Mostrous Moonshine,
a relation between modular forms and sporadic finite simple groups
discovered by McKay, Thompson, Conway and Norton,
and explained by Borcherds, partially by mathematical realizations
of some ideas originating in quantum field theory.


### Prerequisites
I assume basic working proficiency with
the first four fundamental arithmetic operations,
complex numbers and basic trigonometry (functions exp and tan/cot),
substitution in polynomials/series/functions,
differentiation (Leibniz law),
integration (change of coordinate formula),
limits and (infinite) summation.
You shall know how to find a linear dependence between e.g. 4 polynomials (of one variable) of degree 2 (in [1]),
and have an idea about common eigenvectors of commuting operators/matrices (in [4]).
These seem to be covered by courses of the basic cycle and/or school.

Modular forms have many faces, in particular they can be considered either
as holomorphic functions on the upper half-plane or as Fourier series,
thus making desirable some basic skills of either complex or Fourier analysis.

In particular, I hope you to understand the proof of Liouville's theorem

> If $f(z)$ is bounded and entire, then Mr. Cauchy’s theorem implies that
$f'(a) = \lim_{R\to\infty}\big(\frac{1}{2πi} \int_{|z|=R} \frac{f(a+z)}{z^2} dz \big) = 0$
for every $a$ in the complex plane, so $f(z)$ is constant.

but not of Little Picard Theorem 

> An integral function never 0 or 1 is constant.

In fact, Picard's original proof is an application of Liouville's theorem to a _modular function_
$\lambda = 16 q - 128 q^2 + 704 q^3 - 3072 q^4 + ...$ 

Similarly we will use Poisson summation formula,

> $\sum_{n\in\mathbf{Z}} f(n) = \sum_{m\in\mathbf{Z}} \hat{f}(m)$

where $\hat{f}(x) = \int_{-\infty}^{\infty} f(y) \exp(2πiy) dy$ is the Fourier transform,
and I hope you either understand its straight-forward proof
(see e.g. <http://empslocal.ex.ac.uk/people/staff/mrwatkin//zeta/bump-poisson.htm>),
or can convince yourself that you understand it.

The student interested in applications to number theory, combinatorics or algebraic geometry,
but without training in either complex or harmonic analysis
is suggested to try the course anyway, but to write down all new analytic theorems or techniques,
and study simultaneously in the courses of introduction to Fourier analysis and complex variable
(which I strongly suggest to everybody anyway).


### Bibliography

The course will loosely follow Zagier's text.

#### Principal
- Don Zagier: Elliptic modular forms and their applications. 
Pages 1-103 in
"The 1-2-3 of Modular Forms: Lectures at a Summer School in Nordfjordeid, Norway (Universitext)
Springer Berlin Heidelberg, 2008."

#### Complementary
Since modular forms are so central and classical, and widely applied,
there are many good textbooks from different epochs suited for various purposes.
The students might consult other treatments according to their tastes.

- Robert C. Gunning: Lectures on Modular Forms.
Notes by Armand Brumer. Annals of Mathematics Studies, No. 48 Princeton University Press, Princeton, N.J. 1962 iv+86 pp
"One of the first, and perhaps still the best, treatments of the basic material. [J.Milne]"
<https://archive.org/details/lecturesonmodula00gunn>
- Jean-Pierre Serre: A Course in Arithmetic. 1973.
<https://link.springer.com/book/10.1007/978-1-4684-9884-4>
Relevant chapters are Chapter V "Integral Quadratic Forms with Discriminant ± 1" (pp. 48-58)
and Chapter VII "Modular Forms" (pp. 77-111).
- Goro Shimura: Introduction to Arithmetic Theory of Automorphic Functions. 1971.
- Andre Weil: Elliptic Functions according to Eisenstein and Kronecker. 1976. 94 pages.
<https://link.springer.com/book/10.1007/978-3-642-66209-6>
"This book contains a wealth of mathematics.  It proves that history of mathematics can be made genuinely interesting to active mathematicians; but that it will have to be done by an active mathematician, and by a master at that."
- Herbert Clemens: A Scrapbook of Complex Curve Theory. 1980.
Chapters 2,3,4. (pp. 37-145).
<https://link.springer.com/book/10.1007/978-1-4684-7000-0>
- Neal Kobliz: Introduction to Elliptic Curves and Modular Forms. 1993. 252 pages.
<https://link.springer.com/book/10.1007/978-1-4612-0909-6>
- Peter Sarnak: Some Applications of Modular Forms. 1990.
Chapters 1 and 4.
- John Horton Conway: The Sensual (quadratic) Form. 152 pages.
<https://bookstore.ams.org/car-26/>
Also <https://www.maths.ed.ac.uk/~v1ranick/papers/conwaysens.pdf>.
- John Milnor, Dale Husemoller: Symmetric Bilinear Forms. 1973. 150 pages.
<https://link.springer.com/book/10.1007/978-3-642-88330-9>
- Andrew Ogg: Modular Forms and Dirichlet Series, Benjamin, New York, 1969.
- Igor Dolgachev: Lectures on Modular Forms, Fall 1997/1998, Dec 23, 2014. 173 p.
<http://www.math.lsa.umich.edu/~idolga/modular.pdf>
- James Milne: Modular Functions and Modular Forms (Elliptic Modular Curves),
v 1.31, March 22, 2017. 134 pages.
<http://www.jmilne.org/math/CourseNotes/MF.pdf>
- Fred Diamond, Jerry Shurman: A First Course in Modular Forms.
Graduate texts in mathematics, 228. 2005. 436 p.
<https://link.springer.com/book/10.1007/978-0-387-27226-9>
- William Stein: Modular Forms, A Computational Approach.
<https://wstein.org/books/modform/stein-modform.pdf>
"This is a textbook about algorithms for computing with modular forms. It is nontraditional in that the primary focus is not on underlying theory; instead, it answers the question “how do you explicitly compute spaces of modular forms?”"
And see the reference to SageMath software below.



#### Suggested software
- SageMath  (<http://www.sagemath.org>).
Especially the following sections:
[Modular Forms](http://www.sagemath.org/doc/reference/modfrm/index.html),
[Arithmetic Subgroups of SL(2,Z)](http://www.sagemath.org/doc/reference/arithgroup/index.html),
[General Hecke Algebras and Hecke Modules](http://www.sagemath.org/doc/reference/hecke/index.html),
[L-functions](http://www.sagemath.org/doc/reference/lfunctions/index.html),
[Miscellaneous Modular-Form-Related Modules](http://www.sagemath.org/doc/reference/modmisc/index.html).

Note that main driving force behind SageMath (and CoCalc) 
is William Stein, see his book "Modular Forms, A Computational Approach." above.


#### Sources of citations

1. "THE PROOF", PBS Airdate: October 28, 1997,
BBC interview with mathematicians
<https://www.pbs.org/wgbh/nova/transcripts/2414proof.html>
2. Ken Ribet. "The five fundamental operations of mathematics: addition, subtraction, multiplication, division, and modular forms", a talk on March 31, 2008.
<https://math.berkeley.edu/~ribet/trinity.pdf>
3. Don Zagier: A Refinement of a Theorem of J. E. Littlewood. 
<http://people.mpim-bonn.mpg.de/zagier/files/doi/10.4169/amer.math.monthly.121.07.618/littlewood.pdf>
4. <http://empslocal.ex.ac.uk/people/staff/mrwatkin//zeta/bump-poisson.htm>


#### Related courses

- Introduction to Fourier analysis [MAT2640](https://www.puc-rio.br/ferramentas/ementas/ementa.aspx?cd=mat2640)
- [Introduction to complex variable](complex.md)
- [Introduction to topology](itop.md) (fundamental group and coverings)
- [Riemann surfaces I, II](rs-en.md)
- [Algebraic structures](http://mat.puc-rio.br/~sergey/as.html)
- (Number theory)


