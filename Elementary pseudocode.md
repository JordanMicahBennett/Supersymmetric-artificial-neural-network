Overview before pseudocode
===========================
![](https://i.imgur.com/BYseI46.png)

  _Image snippet, because markdown doesn't appear to support LATex Math Symbols. (Source [a quora answer of mine](https://www.quora.com/How-far-are-we-from-achieving-artificial-general-intelligence-AGI/answer/Jordan-Bennett-9?srid=Jj6I))_

As you can see in the concluding line above, there is good motivation to do something wrt to _SU(m|n)_ space. This is what the "Supersymmetric Artificial Neural Network" is all about.

Pseudocode
===========================

a. Initialize input [Supercharge](https://en.wikipedia.org/wiki/Supercharge) compatible [special unitary matrix](https://en.wikipedia.org/wiki/Special_unitary_group) _SU(m|n)_.

b. Compute ∇C w.r.t. to _SU(m|n)_, where _C_ is some cost manifold.

* Weight space is reasonably some K¨ahler potential like form: _K(φ, φ∗)_, obtained on some initial projective space _CP^(n−1)_. ([source](https://arxiv.org/pdf/hep-th/0006025.pdf))

c. Parameterize _SU(m|n)_ in -∇C terms, by [Darboux transformation](https://www.encyclopediaofmath.org/index.php/Darboux_transformation).

d. Repeat until convergence.
