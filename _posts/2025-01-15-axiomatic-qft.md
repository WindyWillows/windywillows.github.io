---
layout: post
title: "Axiomatic Frameworks for Quantum Field Theory"
tags: math physics
---

Quantum field theory famously does not have full axiomisation in the way standard quantum mechanics does. Constructing a lagrangian for the standard model is a millenium prize problem. Nevertheless, by restricting what we mean by "quantum field theory", there exist various kinds of axiom systems that can be constructed in a fully rigorous manner.

Algebraic Quantum Mechanics:

1. A physical system $$\mathfrak{A}$$ (a unital C*-algebra)
2. States which are identified by positive normalised linear functionals on $$\mathfrak{A}$$, i.e. $$\omega(A^{*}A) \geq 0$$ for all $$A \in \mathfrak{A}$$ and $$\omega(\mathbb{1}) = 1$$


The Wightman Axioms:

The Haag-Kastler Axioms:

Setting - For a net of C*-algebras $$\mathcal{O} \mapsto \mathfrak{A(\mathcal{O})}$$ the following hold:

- 1 - Isotony: 

  For $$\mathcal{O} \subset \mathcal{O}'$$ we have $$\mathfrak{A(\mathcal{O})} \subset \mathfrak{A(\mathcal{O}’)}$$​

- 2 - Locality (also called Einstein causality). Here algebras associated to different spacelike separated regions commute:

  If $$\mathcal{O_1}$$ is spacelike separated from $$\mathcal{O_2}$$ , then then $$[A, B] = 0, \space \forall A \in \mathfrak{A(\mathcal{O_1})}, \space B \in \mathfrak{A(\mathcal{O_2})},$$​ 

  This expresses the independence of physical systems associated to regions $$\mathcal{O_1}$$ and $$\mathcal{O_2}$$ of spacetime.

- 3 - Covariance: Minkowski spacetime has a isometries of the connected component of the Poincaré group $$\mathcal{P}$$. We need that for each $$L \in \mathcal{P}$$ there exists an isomorphism $$\alpha^{\mathcal{O}}_{L} : \mathfrak{A(\mathcal{O})} \rightarrow \mathfrak{A(L\space \mathcal{O})}$$, and that for $$\mathcal{O_1} \subset \mathcal{O_2}$$ the restiction of $$\alpha^{\mathcal{O_2}}_L$$ to $$\mathfrak{A(\mathcal{O_1})}$$ coincidences with $$\alpha^{\mathcal{O_1}}_L$$ and $$\alpha^{L\mathcal{O}}_{L'} \circ \alpha^{\mathcal{O}}_{L} = \alpha^{\mathcal{O}}_{L'L}$$

- 4 - Time slice axiom: The algebra of a neighbourhood of a Cauchy surface of a given region coincidences with the algebra of the full region. This corresponds to the well-posedness of an initial value problem for a hyperbolic PDE. This shows that we only need to determine our observances in some small time interval $$(t_0 - \epsilon, t_0 + \epsilon)$$ to recreate the full algebra.

- 5 - Spectrum condition: This is the positivity of energy. Assuming a compatible family of faithful representations $$\pi_{\mathcal{O}}$$ of $$\mathfrak{A(\mathcal{O})}$$ on a fixed Hilbert space (i.e. the restriction of $$\pi_{\mathcal{O}_2}$$ to $$\mathfrak{A(\mathcal{O}_1)}$$ coincidences with $$\pi_{\mathcal{O}_1}$$ for $$\mathcal{O}_1 \subset \mathcal{O}_2$$) such that translations are unitarily implemented, i.e. there is a unitary representation $U$ of the translation group satisfying

  ​		$$U(a)\pi_{\mathcal{O}}(A)U(a)^{-1} = \pi_{\mathcal{O}+a}(\alpha_a(A)), \space A \in \mathfrak{A(\mathcal{O})}$$,

  And such that the joint spectrum of the generators $$P_\mu$$ of translations $$e^{a \cdot P} = U(a), a \cdot P = \sum_{\mu = 0}^{3} a^{\mu} P_{\mu}$$, is in the closed future lightcone $$\sigma(P) \subset \overline{V}_{+}$$.

Axioms for Locally Covariant Quantum Field Theory (or AQFT):

An embedding $$\chi$$


Axioms for AQFT on Curved Spacetimes:

Axioms for Perturbative AQFT:

We build perturbative AQFT on a classical field theory. That is, a model on spacetime $$\mathcal{M}$$ of a net of locally convex topological Poisson $$*$$-algebras $$\mathfrak{B}(\mathcal{O})$$, each possessing a sequentially continuous product and a Poisson bracket $$\lfloor .,. \rfloor$$;

$$\mathcal{O} \mapsto \mathfrak{B}(\mathcal{O})$$​,

where $$\mathcal{O} \subset \mathcal{M}$$ are bounded, simply connected regions.

- We keep the axiom for locality, i.e. if $$\mathcal{O}_1$$ is spacelike separated from $$\mathcal{O}_2$$ then $$\lfloor A, B \rfloor = 0, \space \forall A \in \mathfrak{B(\mathcal{O_1})}, \space B \in \mathfrak{B(\mathcal{O_2})},$$ where the Poisson bracket $$\lfloor , \rfloor$$ is taken in $$\mathfrak{B}(\mathcal{M})$$.

Now we give the axioms for perturbative AQFT which are a quantization of the aforementioned theory.

A perturbative algebraic quantum field theory (pAQFT) is a model on a spacetime $$\mathcal{M}$$ a net of topological $$*$$-algebras with a sequentially continuous product

$$\mathcal{O} \mapsto \mathfrak{A}(\mathcal{O})$$,

where $$\mathcal{O} \subset \mathcal{M}$$ are bounded, simply connected regions.

- Locality: Holds as usual.

- Time Slice Axiom:

  A classical/quantum field theory model on a globally hyperbolic spacetime $$\mathcal{M}$$ satisfies the time slice axiom if the algebra of a neighborhood of a Cauchy surface for a given region coincides with the algebra of the full region.

- Covariance:

  If the underlying spacetime $$\mathcal{M}$$ has a non-trivial group of symmetries $$\mathcal{G}$$, we say that the model on it is covariant if for $$\mathcal{B} \in \mathcal{G}$$ there there exists a family of isomorphisms $$\alpha^{\mathcal{O}}_{\mathcal{\beta}} : \mathfrak{A}(\mathcal{O}) \rightarrow \mathfrak{A}(\beta \mathcal{O})$$, such that for $$\mathcal{O}_{1} \subset \mathcal{O}_{2}$$ the restriction of $$\alpha^{\mathcal{O}_{2}}_{\beta}$$ to $$\mathfrak{A}(\mathcal{O}_{1})$$ coincides with $$\alpha^{\mathcal{O}_{1}}_{\beta}$$ and $$\alpha^{g \mathcal{O}}_{\beta'} \circ \alpha^{\mathcal{O}}_{\beta} = \alpha^{\mathcal{O}}_{\beta'\beta}$$.

Axioms for Perturbative AQFT on Curved Spacetimes:

Haag-Kastler Stacks:

Let us define the Haag-Kastler 2-functor 

$$\textsf{HK} : \textbf{Loc}^{\text{op}} \longrightarrow \textbf{CAT}$$​​

By assigning to each object $$M \in \textbf{Loc}$$ the category

$$\textsf{HK}(M) := \textbf{AQFT}(\overline{\textbf{COpen}(M)}) \in \textbf{CAT}$$​

of Haag-Kastler-style AQFTs on $M$ and to each $\textbf{Loc}$-morphism $f : M \rightarrow N$ the pullback functor

![Image](/assets/images/ld1.png)

Factorisation Algebras:

Topological Quantum Field Theories:

Functorial Field Theories:


Conformal Field Theories:





References:

[1] Haag, K., Local Quantum Physics, 1992

[2] Brunetti, R., Fredenhagen, K., Verch, R., The Generally Covariant Locality Principle - A New Paradigm for Local Quantum Field Theory, 2001

[3] Rejzner, K., Perturbative Algebraic Quantum Field Theory, 2016
