{% include navigation.html %}

## Research Interests

Geometry is the common thread through my research, my interests, and even the way I approach problems in data science. In particular I think about geometry as envisioned by the Klein Erlangen Program: the study of objects/properties invariant under a particular group of transformations. Euclidean geometry, for instance, can be interpreted as the study of objects/properties invariant under rigid motions. My mathematics work is heavily focused on invariants (of curves in particular), but I tend to interpret data science in a geometric way as well. After all a dataset can be often be thought of as a collection of points in high-dimensional space with the challenge of identifying interesting properties of this dataset.

* Note: All works listed below have equal authorship (authors listed in alphabetical order) and have preprints that can be found on the [arxiv](https://arxiv.org/search/math?searchtype=author&query=Ruddy%2C+M).

## Thesis and Related Work: Differential Invariants in Algebraic Geometry

My PhD thesis is titled [The Group Equivalence Problem and Signatures of Algebraic Curves](https://repository.lib.ncsu.edu/handle/1840.20/36673). The goal of this work was to use tools from differential and algebraic geometry to categorize algebraic curves (curves defined by polynomials) up to various groups of transformations. In particular we show that one can use various symoblic computation algorithms to determine whether algebraic curves are related by a transformation (such as rotation and translation) which is of interest in certain computer vision applications. Much of this work was later published:

* [Differential Signatures of Algebraic Curves](https://epubs.siam.org/doi/10.1137/19M1242859), *SIAM J. of Applied Algebraic Geometry 4, 1 (2020), 185-226* (with [Irina A. Kogan](https://iakogan.math.ncsu.edu/) and [Cynthia Vinzant](http://sites.math.washington.edu/~vinzant/)).

Because symbolic computation algorithms can become incredibly slow as the complexity of the algebraic curve increases, [Tim Duff](https://timduff35.github.io/timduff35/) and I showed that the method outlined in the above works can be used in conjunction with *numerical algebraic geoemtry* which uses algebraic geometric tools to develop numerical algorithms. We submitted an initial report of this work in the conference proceeding here:

* [Numerical equality tests for rational maps and signatures of curves](https://dl.acm.org/doi/10.1145/3373207.3404050), *Proc. of the 45th ISSAC (2020), pp. 154-161*, code available [here](https://github.com/timduff35/NumericalSignatures) (with [Tim Duff](https://timduff35.github.io/timduff35/)).

which we later expanded to a journal work here:

* [Signatures of algebraic curves via numerical algebraic geometry](https://arxiv.org/pdf/2005.04783.pdf), *to appear in J. of Symbolic Computation* (with [Tim Duff](https://timduff35.github.io/timduff35/)).

Moving away from algebraic curves, in a later work my co-authors and I applied some of the same tools from above to describe a space of *integral* invariants (which are must more robust to noise) for curves defined by time series. The work makes the computation of such invariants very explicit, and I hope that work will be done in the future investigating the use of this method in applications such as human activity recognition.

* [The moving frame method for iterated-integrals: orthogonal invariants](https://trebuchet.public.springernature.app/get_content/c2fd43bd-8748-41c1-9089-26d376e13111), *Foundations of Computational Mathematics, June 2022* (with [Joscha Diehl](https://diehlj.github.io), [Rosa Preiß](https://www.rosapreiss.net), and [Nikolas Tapia](https://www.wias-berlin.de/people/tapia/?lang=0))

## Algebraic Statistics

During my time at the MPI MiS in Leipzig, I was fortunate to come into contact with many spectacular researchers in the field of algebriac statistics, or the use of tools from algebraic geometry to solve problems in statistics or to describe statistical models. I entered this field by using some of previous knowledge of algebraic curves to solve a completely different problem: counting the number of solutions to a maximum likelihood problem:

* [Maximum likelihood degree of the two-dimensional linear Gaussian covariance model](https://doi.org/10.2140/astat.2020.11.107), *Algebraic Statistics 11(2), 107-123*, (with [Jane Ivy Coons](https://sites.google.com/view/jane-ivy-coons) and [Orlando Marigliano](https://orlandomarigliano.com))

However, the most work I've done in this area is a large project that has spanned almost three years of time. Here we use tools from combinatorics (scary!) and algebraic geometry to describe the relationship between a representation of a statistical model and the result of a numerical algorithm to compute the maximum likelihood estimate:

* [Rational partition models under iterative proportional scaling](https://arxiv.org/pdf/2206.00173.pdf), *submitted*, (with [Jane Ivy Coons](https://sites.google.com/view/jane-ivy-coons) and [Carlotta Langer](https://dblp.org/pid/207/4233.html))

## Deep Learning in Radiology

While at USF, I also had the opportunity to be a part of a few projects involving deep learning and radiology. For most of these projects, I advised teams of students in conjunction with clinical researchers at UCSF. We used deep learning and traditional tabular data algorithms to try and predict clinical outcomes including local control of tumors and amount of radiation to sensitive organs. The datasets often involved both demographics and clinical tabular data about patients and their 3D imaging scans and radiation outcomes.
