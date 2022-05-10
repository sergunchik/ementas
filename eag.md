### Elementary Algebraic Geometry, a geometric introduction

Already Rene Descartes criticized the separation of algebra and geometry and

> believed that I could borrow all that was best both in geometrical analysis and in algebra, and correct all the defects of the one by help of the other

greatly contributing to both by their synthesis in his analytic geometry.

In 19th century after the works of Poncelet and subsequent developments of Abel, Cayley, Salmon and others
the new discipline emerged and flourished in the Italian school of late 19 - early 20th century.

The aim of the course is to give a taste of projective and affine algebraic geometry
with minimal pre-requisites (linear algebra and basic algebra of polynomial rings)
and to show some classical results accessible with pre-WWII machinery.

I copy an abstract of the textbook of Gorodentsev

> This is a geometric introduction to the algebraic geometry. I hope to acquaint the readers with some basic figures underlying the modern algebraic technique and show how to translate things from the infinitely rich (but quite intuitive) world of figures to the scanty and finite (but very explicit) language of formulas. These lecture notes contain a lot of exercises crucial for understanding the subject.

#### Syllabus


Projective (and affine) varieties. Key examples.
Smooth vs. Singular points and dimension.
Plane Cubic Curves.
Projection and blowup.
Cubic Surfaces.


#### Some highlights
- Blaise Pascal and the mystic hexagon
- varieties of linear/tensor algebra and varieties of matrices:
Veronese, С. Serge, Grassmann, flags, determinantal
- secants and tangents, tangent space, Gauss map, projective duality, singularity and dimension
- group law on the cubic curve
- Poncelet's porism (+ explanation + (maybe) demonstration)
- how many lines in a space intersect four given lines? (intro to Schubert calculus)
- the 27 lines on the cubic surface (+ Cremona's proof)

#### Basic bibliography and pre-requisites.

All of the following books introduce the subject without the new techniques of schemes/sheaves/cohomology,
showing instead how far one can go with geometric methods.
Harris provides a lot of interesting examples
and does not even discuss a genus of a curve!

1. Alexey L. Gorodentsev: Algebraic Geometry: A Start Up Course.
125 pages. MCCME (2008).
<http://gorod.bogomolov-lab.ru/ps/stud/projgeom/1718/list.html> (2017.11.24) 

2. Miles Reid: Undergraduate Algebraic Geometry.
132 pages.
London Mathematical Society Student Texts 12.
(at DMAT library).
<https://homepages.warwick.ac.uk/staff/Miles.Reid/MA4A5/UAG.pdf> (2013.10.20)

3. William Fulton: Algebraic Curves. An Introduction to Algebraic Geometry.
114 pages.
<https://dept.math.lsa.umich.edu/~wfulton/CurveBook.pdf> (2008.01.28)

4. Klaus Hulek: Elementary Algebraic Geometry.
213 pages.
Student Mathematical Library 20.
(at DMAT library).
<https://bookstore.ams.org/stml-20>

5. Joe Harris: Algebraic Geometry. A First Course.
313 pages.
Graduate Texts in Mathematics 133.
(at DMAT library)
<https://link.springer.com/book/10.1007/978-1-4757-2189-8>

6. Igor Shafarevich: Basic Algebraic Geometry 1.  Varieties in Projective Space.
310 pages.
Third Edition. (2013) Springer.
Cf. <https://userpage.fu-berlin.de/aconstant/Alg2/Bib/Shafarevich.pdf>
"The book does not aim to cover a huge volume of material in the maximal generality and rigour, but gives instead a well-considered choice of topics, with a human-oriented discussion of the motivation and the ideas, and some sample results (including a good number of hard theorems with complete proofs)."


#### Pre-requisites

The course is suitable to either undergraduate or early post-graduate students.

Required: Proficiency with polynomials of many (e.g 3) variables.

Desirable: Knowledge how to compute a rank of a rectangular matrix with real or complex entries.

I copy pre-requisites from the authors of the reference textbooks.

> Harris: just some linear and multilinear algebra and a basic background in abstract algebra (definitions and basic properties of groups, rings, fields, etc.)

> Shafarevich (Part 1): in addition to an undergraduate algebra course, we assume known basic material from field theory: finite and transcendental extensions (but not Galois theory), and from ring theory: ideals and quotient rings. 

> Fulton: some basic properties of rings, ideals, and polynomials, such as is often covered in a one-semester course in modern algebra

> Beltrametti et al: basic elements of projective geometry and abstract algebra, e.g. some knowledge of the geometry of subspaces and properties of fields

> Reid is more explicit:
>
> - Algebra: Quadratic forms, easy properties of commutative rings and their ideals, principal ideal domains and unique factorisation.
> - Galois Theory: Fields, polynomial rings, finite extensions, algebraic versus transcendental extensions, separability.
> - Topology and geometry: Definition of topological space, projective space $\mathbf{P}^n$ (but I’ll go through it again in detail).
> - Calculus in $\mathbf{R}^n$: Partial derivatives, implicit function theorem (but I’ll remind you of what I need when we get there).
> - Commutative algebra: Other experience with commutative rings is desirable, but not essential.

> Garrity et al:
>
> - C1 (conics) -  appropriate for first-year college students (and many high school students). 
> - C2-3 (cubic and higher degree curves) - appropriate for people who have taken multivariable calculus and linear algebra.
> - C4-5 (higher dimensional varieties) - abstract algebra now plays a critical role, making a first course in abstract algebra necessary from this point on.

> Hulek: standard courses on algebra and complex analysis (in principle, some analytic parts could be replaced by other material)


#### Complementary Bibliography

- Thomas Garrity, et al: Algebraic Geometry: Problem Solving Approach.
362 pages.
<https://bookstore.ams.org/stml-66>
"This text consists of a series of exercises, plus some background information and explanations, starting with conics and ending with sheaves and cohomology." 
- Andreas Gathmann: 2014 lecture notes on undergraduate algebraic geometry.
<https://www.mathematik.uni-kl.de/~gathmann/de/alggeom.php>
- Igor Dolgachev: Introduction to Algebraic Geometry.
<http://www.math.lsa.umich.edu/~idolga/631.pdf> (2013.08.19)
- Igor Dolgachev: Classical Algebraic Geometry: a modern view.
Cambridge Univ. Press (2012). 656 pages + 612 references.
<http://www.math.lsa.umich.edu/~idolga/CAG.21.pdf> (2021)
- Giacomo Monti Bragadin Mauro C. Beltrametti, Ettore Carletti, Dionisio Gallarati:
Lectures on Curves, Surfaces and Projective Varieties.
EMS Textbooks in Mathematics.
506 pages. 2009
- Enrique Arrondo: Introduction to projective varieties.
<http://www.mat.ucm.es/~arrondo/projvar.pdf> (2017.11.26)
"The scope of these notes is to present a soft and practical introduction to algebraic geometry, i.e. with very few algebraic requirements but arriving soon to deep results and concrete examples that can be obtained “by hand”...
My approach consists of avoiding all the algebraic preliminaries that a standard algebraic geometry course uses for affine varieties and thus start directly with projective varieties (which are the varieties that have good properties)...."
- David Cox, John Little, Donal O'Shea: Ideals, Varieties, and Algorithms: An Introduction to Computational Algebraic Geometry and Commutative Algebra.
Undergraduate Texts in Mathematics.
- David Cox, John Little, Donal O'Shea: Using Algebraic Geometry.
Graduate Texts in Mathematics, 185.
