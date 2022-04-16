{% include navigation.html %}

In Progress. You can find the old version of this page [here](https://mgruddy.wixsite.com/home/research)

## Research Interests

Geometry is the common thread through my research, my interests, and even the way I approach problems in data science. In particular I think about geometry as envisioned by the Klein Erlangen Program: the study of objects/properties invariant under a particular group of transformations. Euclidean geometry, for instance, can be interpreted as the study of objects/properties invariant under rigid motions. My mathematics work is heavily focused on invariants (of curves in particular), but I tend to interpret data science in a geometric way as well. After all a dataset can be often be thought of as a collection of points in high-dimensional space with the challenge of identifying interesting properties of this dataset.

## Thesis and Related Work

My PhD thesis is titled [The Group Equivalence Problem and Signatures of Algebraic Curves](https://repository.lib.ncsu.edu/handle/1840.20/36673). The goal of this work was to use tools from differential and algebraic geometry to categorize algebraic curves (curves defined by polynomials) up to various groups of transformations. In particular we show that one can use various symoblic computation algorithms to determine whether algebraic curves are related by a transformation (such as rotation and translation) which is of interest in certain computer vision applications. Much of this work was later published:

* [Differential Signatures of Algebraic Curves](https://epubs.siam.org/doi/10.1137/19M1242859), *SIAM J. Appl. Algebra Geom. 4, 1 (2020), 185-226* (with [Irina A. Kogan](https://iakogan.math.ncsu.edu/) and [Cynthia Vinzant](http://sites.math.washington.edu/~vinzant/)).

Because symbolic computation algorithms can become incredibly slow as the complexity of the algebraic curve increases, [Tim Duff](https://timduff35.github.io/timduff35/) and I showed that the method outlined in the above works can be used in conjunction with *numerical algebraic geoemtry* which uses algebraic geometric tools to develop numerical algorithms. We submitted an initial report of this work in the conference proceeding here:

* [Numerical equality tests for rational maps and signatures of curves](https://dl.acm.org/doi/10.1145/3373207.3404050), *Proc. of the 45th ISSAC (2020), pp. 154-161*, code available [here](https://github.com/timduff35/NumericalSignatures) (with [Tim Duff](https://timduff35.github.io/timduff35/)).

which we later expanded to a journal work here:

* [Signatures of algebraic curves via numerical algebraic geometry](https://arxiv.org/pdf/2005.04783.pdf), *to appear in J. of Symbolic Computation* (with [Tim Duff](https://timduff35.github.io/timduff35/)).