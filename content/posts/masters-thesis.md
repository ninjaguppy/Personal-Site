+++
title = "Masters Thesis: The Beginnings of Algebraic Topology in Free Analysis"
authors = ["Lucas Kerbs"]
date = 2023-12-02T15:31:00-06:00
categories = ["FreeAnalysis"]
draft = false
Katex = true
+++

I completed my Master's Thesis at Cal Poly SLO under the direction of Dr. Ryan
Tully-Doyle. You can download to the full document [here](/files/BeginningsAlgTopinFA_LK.pdf).

Free Analysis seeks to understand functions that accept matrices of arbitrary
sizes as inputs---so called "free" functions. For example, polynomials in a
single variable have a natural extension to matrices. Polynomials in several
variables are more complicate to extend to matrices, but such extensions are
possible and explored at length.

Many classical results (monodromy, Oka-Weil, the implicit function theorem,
etc.) have been extended to this new context. At the time of writing, there is
no canonical topology for these spaces of matrices (although there are several
candidate topologies). My thesis explored one of these topologies in depth,
working through and expanding upon the results of J. E. Pascoe in [this paper](https://arxiv.org/abs/2010.14483).

My thesis uses tools from a number of different disciples (algebraic topology,
algebraic geometry, complex analysis, and even a handful of combinatorial
arguments) in order to understand the "shape" of nice[^fn:1] open subsets of
\\(\mathcal{D} \subset \bigcup\_{\mathbb{N}} M\_n(\mathbb{C})\\) (called _free_ sets).
There are three types of functions defined on such a \\(\mathcal{D}\\): free
functions (which act like classical analytic function), determinental functions
(which act like \\(\det\\)) and tracial functions (which act like the trace).

Directly analogous to the construction in Complex Analysis, we use the analytic
continuation of frees function (and the related functions, which can also be
analytically continued) defined on \\(\mathcal{D}\\) create analogues of the
fundamental group and detect its topology. Since there is more than one class of
function which can be analytically continued, there turn out to be _three_ such
fundamental groups: \\(\pi\_1^{free},\pi\_1^{det}, \text{ and }\pi\_1^{tr}\\). It
turns out that \\(\pi\_1^{free}\\) is trivial and \\(\pi\_1^{tr}=\pi\_1^{det}\\) is
countable, torsion free, and abelian.

It turn out that free and tracial functions defined on some free sets are
related by a derivative-like object. As such, Pascoe uses this gradient to
construct a basic[^fn:2] cohomlogy theory analogous to De-Rham cohomology. This
cohomology theory allows us to actually compute \\(\pi\_{1}^{tr}\\) for simple spaces.

[^fn:1]: See the thesis for details, but in short "niceness" requires the sets are
    closed under direct sum (\\(X \in \mathcal{D} \implies X \oplus X \in
    \mathcal{D}\\)) and under similarity (\\(X \in \mathcal{D} \implies U X U^{\*} \in
    \mathcal{D}\\) for all like-size unitary \\(U\\)).
[^fn:2]: Basic meaning that only \\(H^1\\) is defined.