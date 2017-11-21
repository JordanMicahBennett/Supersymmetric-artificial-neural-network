Overview before pseudocode
===========================
1. There has been a clear progression of “**solution geometries**”, ranging from those of the ancient [Perceptron](https://en.wikipedia.org/wiki/Perceptron) to [unitaryRNN's](https://arxiv.org/abs/1611.00035) or [complex valued neural nets](https://arxiv.org/abs/1705.09792). These models may be denoted by ϕ(x,θ)<SUP>T</SUP>w parameterized by θ, expressible as geometrical groups ranging from _SO(n)_ to _U(n)_, and they got **better at representing input data i.e. representing richer weights**, thus the learning models generated better hypotheses or guesses.


2. By “**solution geometry**” I mean simply the class of regions where an algorithm's weights may lie, when generating those weights to do some task.


3. As such, if one follows **cognitive science**, one would know that biological brains may be measured in terms of **supersymmetric** operations. (Perez et al, “[Supersymmetry at brain scale”](https://arxiv.org/abs/0705.1134))


4. These supersymmetric biological brain representations can be represented by special unitary notation _SU(m|n)_, or ϕ(x,θ,θ<sup>–</sup>)<SUP>T</SUP>w  parameterized by θ,θ<sup>–</sup>, which are supersymmetric directions, unlike θ seen in item (1). Notably, Supersymmetric values can **encode or represent more information** than the prior classes seen in (1), in terms of “partner potential” signals for example.


5. So, state of the art machine learning work forming _U(n)_ based solution geometries, in for e.g, the [unitaryRNN](https://arxiv.org/abs/1611.00035) are **already** in the **family** of **solution geometries** that may be observed as occurring in the biological brain _SU(n)_, but not _SU(m|n)_, which is observed in biological brains. This is where the [“**Supersymmetric artificial neural network**”](https://jordanmicahbennett.github.io/Supermathematics-and-Artificial-General-Intelligence/) fits in.

Pseudocode
===========================

a. Initialize input [Supercharge](https://en.wikipedia.org/wiki/Supercharge) compatible [special unitary matrix](https://en.wikipedia.org/wiki/Special_unitary_group) _SU(m|n)_.

b. Compute ∇C w.r.t. to _SU(m|n)_, where _C_ is some cost manifold.

c. Parameterize _SU(m|n)_ in -∇C terms, by [Darboux transformation](https://www.encyclopediaofmath.org/index.php/Darboux_transformation).

d. Repeat until convergence.
