# Fourier Series Through Probability and Statistics

**By B. Grey Vandeberg**

📄 **[Read the chapter (PDF)](https://github.com/greystat/fourier-through-statistics/blob/b122c537425fb396246ec4351fac03a5c2ed644b/MathematicalMethods-Fourier.pdf)**

---

A 140-page treatment of Fourier series that develops the theory through a probabilistic and statistical lens. The Fejér kernel is a probability density converging to a point mass; Fejér's theorem follows from convergence in probability. Parseval's identity is a variance decomposition — the Fourier-analytic equivalent of ANOVA. Coefficient decay rates are purchased by smoothness, one derivative at a time. The chapter develops calculus, probability, and analysis organically as the Fourier story demands them, rather than as prerequisites.

This is an early chapter of a larger book in progress --- loosely on "mathematical methods" --- which uses Fourier theory as a throughline connecting calculus, probability, linear algebra, and regression. The chapter is self-contained and is intended to be readable with minimal background beyond introductory calculus.

### What's in it

The chapter opens with trigonometric identities and the unit circle, builds the Fourier coefficient formulas from orthogonality, and then asks: when and in what sense does the Fourier series actually converge to the original function? The answer turns out to depend on the function's regularity, and the different notions of regularity — absolute integrability, square-integrability, bounded variation, differentiability — each buy something different. The development introduces the mathematical tools as they're needed:

- **Integration:** Riemann-Stieltjes integration and total variation, developed to state and prove the Dirichlet-Jordan theorem on pointwise convergence.
- **Probability:** Expectation, variance, CDF/PDF, convergence in probability, and Jensen's inequality — all arising from the observation that Fourier coefficients are expectations under uniform sampling.
- **Convergence:** The Fejér kernel as a probability density concentrating at the origin, giving a probabilistic proof of Fejér's theorem (uniform convergence of Cesàro means for continuous functions).
- **Parseval's identity** as a variance decomposition: the total variance of f(U) under uniform sampling equals the sum of per-harmonic contributions, with no cross terms — because orthogonality kills them.
- **A Master Theorem** unifying the convergence results across function classes: L¹ (existence and decay), bounded variation (pointwise convergence via Dirichlet-Jordan), continuity (uniform Cesàro convergence via Fejér), L² (mean-square convergence and Parseval), and Cᵏ (decay rates).

### Context

This chapter is part of a book whose next chapters develop regression (framed as "Fourier without orthogonality" — what breaks when the Gram matrix isn't diagonal), computational mathematics (culminating in the FFT as a theorem about algebraic structure), and the Fourier transform. The unifying idea across the book is that Parseval's identity, the Pythagorean theorem, and Cochran's theorem in statistics are the same theorem in three costumes — and orthogonality is the single property that makes all of them work.

---

Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). © B. Grey Vandeberg.
