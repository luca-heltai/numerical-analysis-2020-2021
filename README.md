 [![Creative Commons License](http://mirrors.creativecommons.org/presskit/logos/cc.logo.png)](http://creativecommons.org/
    licenses/by-nc-nd/4.0/)

# Applied Mathematics: an Introduction to Scientific Computing

- Luca Heltai (<luca.heltai@sissa.it>)
- Gianluigi Rozza (<gianluigi.rozza@sissa.it>)

- Stefano Piani (<stefano.piani@sissa.it>)
- Francesco Ballarin (<francesco.ballarin@sissa.it>)

## Course information

This is a Joint course, between SISSA PhD in Mathematical Analysis, Modeling, and Applications, Laurea Magistrale in Matematica, Laurea Magistrale in Data Science and Scientific Computing, and Master in High Performance Computing.

Due to the large number of diverse groups that will follow the course, and for security protocols, only students with a Scholarship from SISSA will be allowed to follow some of the lectures in presence (SISSA PhD students, LM scholarship holders, DSSC scholarship holders) and few other students from Mathematics. DSSC and MHPC students will be connected online this year.

All lectures will be streamed online using the Zoom platform, and recorded live on YouTube. A link with the lecture will be provided to the students at the end of every lecture.

According to the availability of the teachers, some lectures will be delivered live in one of SISSA classrooms.

The following Zoom link will be used for the lectures:

https://sissa-it.zoom.us/j/85796873697?pwd=cm5HNGRidndvU05UTVAvRkdOdnNrdz09

Meeting ID: 857 9687 3697
Passcode: NumAna

You will find a recording of all lectures in this (YouTube playlist)[https://www.youtube.com/playlist?list=PLArvQL9bsv1y6BhTNOthBj1hGijN3vuCh].

If you want to get up-to-date information about the course, please subscribe to the group:

https://groups.google.com/g/numerical-analysis-2020-2021

(sending an email to numerical-analysis-2020-2021+subscribe@googlegroups.com is sufficient)


If you are following the course, please (FILL THIS FORM)[https://forms.gle/8DyESWnfCmXMei3h8].


## Syllabus 2020-2021

Frontal Lectures (about 24h), Interleaved with Laboratories (about 24h): total 48h, 6 CFU

### Frontal Lectures

##### Review Lectures
- Basic concepts of Vector spaces and norms
- Well posedness, condition numbers
- Polynomial based approximations (Lagrange interpolation, Bernstein polynomials, Bsplines approximations)
- Quadrature rules and orthogonal polynomials
- Solution methods for Linear Systems: direct, iterative and least square methods
- Eigenvalues/Eigenvectors
- Solution methods for non-Linear systems
- Review of ODEs
- Review of FEM/Lax Milgram Lemma/Cea's Lemma/Error estimates
- High order methods/high continuity methods

##### Mathematical Modeling
- Data assimilation in biomechanics, statistics, medicine, electric signals
- Model order reduction of matrices
- Linear models for hydraulics, networks, logistics
- State equations (real gases), applied mechanics systems, grow population models, financial problems
- Applications of ODEs
- example in electric phenomena, signals and dynamics of populations (Lotke-Volterra)
- Models for prey-predator, population dynamics, automatic controls
- Applications of PDEs, the poisson problem
 - Elastic rope
 - Bar under traction
 - Heat conductivity
 - Maxwell equation

### Laboratories

##### Introductory lectures
- Introduction to Python, Numpy, Scipy
- Exercise on Condition numbers, interpolation, quadratures
- Using numpy for polynomial approximation
- Using numpy for numerical integration
- Using numpy/scipy for ODEs
- Working with numpy arrays, matrices and nd-arrays
- Solving non-linear systems of equations

##### Students projects
- Application of the Finite Element Method to the solution of models taken from the course

### References and Text Books:

-   A. Quarteroni, R. Sacco, and F. Saleri. *Numerical mathematics*,
    volume 37 of Texts in Applied Mathe- matics. Springer-Verlag, New
    York, 2000.
    [\[E-Book-ITA\]](http://dx.doi.org/10.1007/978-88-470-0818-2) [\[E-Book-ENG\]](http://dx.doi.org/10.1007/b98885)
-   A. Quarteroni. *Modellistica Numerica per problemi differenziali*.
    Springer, 2008.
    [\[E-Book-ITA\]](http://dx.doi.org/10.1007/978-88-470-0494-8)
-   A. Quarteroni. *Numerical Models for Differential Problems*.
    Springer, 2009.
    [\[E-Book-ENG\]](http://dx.doi.org/10.1007/978-88-470-1071-0)
-   A. Quarteroni and A. Valli. *Numerical approximation of partial
    differential equations*. Springer Verlag, 2008.
    [\[E-Book-ENG\]](http://dx.doi.org/10.1007/978-3-540-85268-1)
-   S. Brenner and L. Scott. *The mathematical theory of finite element
    methods*. Springer Verlag, 2008.
    [\[E-Book-ENG\]](http://dx.doi.org/10.1007/978-0-387-75934-0)
-   D. Boffi, F. Brezzi, L. Demkowicz, R. Durán, R. Falk, and M.
    Fortin. *Mixed finite elements, compatibility conditions, and
    applications*. Lectures given at the C.I.M.E. Summer School held in
    Cetraro, Italy June 26–July 1, 2006. Springer Verlag, 2008.
    [\[E-Book-ENG\]](http://dx.doi.org/10.1007/978-3-540-78319-0)
-   D. Arnold. *A concise introduction to numerical analysis*. Institute
    for Mathematics and its Applications, Minneapolis, 2001.
    [\[E-Book-ENG\]](http://www.ima.umn.edu/~arnold/597.00-01/nabook.pdf)
-   A. Quarteroni, F. Saleri, P. Gervasio.* Scientific Computing with
    Matlab and Octave*. Springer Verlag, 2006.
    [\[E-Book-ENG\]](http://www.springer.com/mathematics/computational+science+%26+engineering/book/978-3-642-45366-3)
-   B. Gustaffson* Fundamentals of Scientific Computing, *Springer,
    2011
    [\[E-Book-ENG\]](http://www.springer.com/mathematics/computational+science+%26+engineering/book/978-3-642-19494-8)
-   Tveito, A., Langtangen, H.P., Nielsen, B.F., Cai, X. *Elements of
    Scientific Computing, *Springer, 2010
    [\[E-Book-ENG\]](http://www.springer.com/mathematics/computational+science+%26+engineering/book/978-3-642-11298-0)

Note that, when connecting from SISSA, all of the text books above are
available in full text as pdf files.

# Instructions for git aware students (and [MHPC](http://www.mhpc.it) students)

This repository contains, assignements, workspaces, and other material for the course P1.4

New material will be uploaded frequently,

Remember to set a second remote, either to our private seed


	git remote add P1.4_seed https://github.com/luca-heltai/numerical-analysis-2020-2021.git

or (if using ssh keys in your github account)

	git remote add P1.4_seed git@github.com:luca-heltai/numerical-analysis-2020-2021.git

and to update before the lectures:

	git pull P1.4_seed master

**Please consider contributing pull requests to correct typos, or better document the material in this repository!**

# Licencing

The content of this repository is distributed with a Creative Common licence. See
the file LICENCE.md in this directory for more information.

# Attribution

Some of the material in this repository was adapted from the python-lectures by [Robert Johansson](https://github.com/jrjohansson/scientific-python-lectures). Take a look at his repository for additional material and lectures.

