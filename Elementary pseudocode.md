Overview before pseudocode
===========================
![](https://i.imgur.com/BYseI46.png)

  _Image snippet, because markdown doesn't appear to support LATex Math Symbols. (Source [a quora answer of mine](https://www.quora.com/How-far-are-we-from-achieving-artificial-general-intelligence-AGI/answer/Jordan-Bennett-9?srid=Jj6I))_

As you can see in the concluding line above, there is good motivation to do something wrt to _SU(m|n)_ space. This is what the "Supersymmetric Artificial Neural Network" is all about.

Pseudocode
===========================

a. Initialize input [Supercharge](https://en.wikipedia.org/wiki/Supercharge) compatible [special unitary matrix](https://en.wikipedia.org/wiki/Special_unitary_group) _SU(m|n)_. This is the atlas seen in b. **(See reference i and ii for "supercharge" and "special unitary matrix")**

b. Compute ∇C w.r.t. to _SU(m|n)_, where _C_ is some cost manifold.

* Weight space is reasonably some K¨ahler potential like form: _K(φ, φ∗)_, obtained on some initial projective space _CP<SUP>n−1</SUP>_.  **(See reference iii)**
* It is feasible that _CP<SUP>n−1</SUP>_ (a _C<SUP>∞</SUP>_ bound atlas) may be obtained from charts of [grassmann manifold networks](https://arxiv.org/pdf/1611.05742.pdf) **(See reference iv)** where there exists some invertible submatrix entailing matrix A ∈ φ<SUB>i</SUB> (U<SUB>i</SUB> ∩ U<SUB>j</SUB>), for U<SUB>i</SUB> = π(_V<SUB>i</SUB>_), where π is a submersion mapping enabling some differentiable grassmann manifold GF<SUB>k,n</SUB>, and _V<SUB>i</SUB>_ = u ∈ R<SUP>n×k</SUP>: det(u<SUB>i</SUB>) ≠ 0}. **(See reference v)**

c. Parameterize _SU(m|n)_ in -∇C terms, by [Darboux transformation](https://www.encyclopediaofmath.org/index.php/Darboux_transformation).  **(See reference vi for"Darboux transformation")**

d. Repeat until convergence.
