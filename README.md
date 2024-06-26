# chaos-stuff

This is some stuff related to my undergrad thesis in physics at Washington State University. It's not my best work and I don't think it has any applications, outside of being a somewhat-interesting artifact of mathematics and physics.

In this thesis, we arbitrarily calculate the Lyapunov exponent of BECs modeled by the Gross-Pitaevskii equation. The exponent is found using the $L^2$-norm of the many-body wavefunction. It seems that the GPE exhibits chaotic motion for positive coupling constants $g$, but I have no idea if this is real (or just some ✨funky maths✨). It is interesting that it is linear between $\lambda$ and $g$ for $g \in \mathbb{R}^+$ (although I do not understand _why_!).

## Abstract
The Gross-Pitaevskii equation (GPE) is a nonlinear Schrödinger equation used in modeling Bose-Einstein condensates (BECs).
Using Lyapunov exponents, chaos was characterized in the GPE in the one-dimensional case.
The GPE was simulated using Python using finite-difference methods in space and an adaptive Runge-Kutta solver was used to evolve the equation in time.
When an initial state of the GPE with positive coupling constant is perturbed, positive Lyapunov exponents were found.
There was a proportionality found between positive Lyapunov exponents and the nonlinear coupling constant of the GPE, $g$.
Further research can be done to analyze this proportionality and to extend this research to higher dimensions.

## Contents

* [My undergraduate thesis (pdf)](ThesisEvans.pdf)
* [GPE IPython notebook](gpe.ipynb) (scratch-work)
* [Lorenz IPython notebook](lorenz.ipynb) (scratch-work)
* I'm not actually sure if these were the notebooks that I used for the paper, or just some scratch work for generating plots for the report. 


## Notes

* I dislike the LaTeX template we were using. I've looked at the templates of other schools and thought ours was very lackluster.
* This was conducted before I had my classes in QM. So, I feel like there was a lot of this thesis that I didn't truly understand. As a result, I didn't enjoy working on this report, thought it didn't engage me, and overall disliked the topic. 
