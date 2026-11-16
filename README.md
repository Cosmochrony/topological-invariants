This repository contains the source of the **Topological Invariants** Cosmochrony paper  
*Topological Invariants of Admissible Configurations:
Fibre Winding, the Open Charge and Monopole Questions,
and Projective Chirality in Cosmochrony*.

This work establishes the **topological layer** of the Cosmochrony framework,
complementary to the dynamical and spectral analyses developed in previous papers.

While earlier works introduced:
- a proposed reading of charge as an invariant of non-injective projection
- the capacity axiom [A-cap], a bound on the discrete per-node relaxation rate
- the spectral admissibility hierarchy

they left open a fundamental question:

**what topological invariants remain admissible under the projection constraint,
and what physical consequences do they impose?**

The present work answers that question.

# Core Result

The paper establishes two topological results and records two open questions:

- the circle fibre carries an **integer winding**, $\pi_1(S^1) \cong \mathbb{Z}$, invariant for configurations in a
  fixed fibre or over a trivialising domain of the base, not for configurations in the whole fibre $\Pi \cong S^3$;
  its identification with **electric charge is not derived**, so charge quantisation in the emergent description
  is open

- **$\pi_2 = 0$ on a chosen domain** of the Hopf base, with two disjoint discs removed;
  this does **not** exclude magnetic monopoles, whose absence remains open

- **Parity violation** arises from a structural mechanism of  
  **projective chirality**

The fibre winding and parity violation are read, as an interpretation, under a single principle:

> admissibility under non-injective projection determines both
> the available topological invariants and their orientation.

# Main Structural Results

The paper examines three points; their status is stated in each.

## 1. Fibre winding, and the missing link to charge

The U(1) fibre of the Hopf fibration supports a winding number:

$$
\pi_1(S^1) \cong \mathbb{Z}
$$

Whether it is invariant depends on the configurations and deformations allowed: it is invariant for maps into a
fixed fibre, or over a trivialising domain of the base (where the fibre coordinate is global); it is not for maps
into the whole fibre $\Pi \cong S^3$, since $\pi_1(S^3) = 0$.

The Hopf fibration is the $U(1)$ bundle over $S^2$ with first Chern number of absolute value one: the bundle of
the unit Dirac monopole over the internal base (Trautman 1977; Wu and Yang 1975). In it the fibre winding and the
class of the base are the same integer, since $\pi_2(S^2) \to \pi_1(S^1)$ is an isomorphism. The winding is
therefore not independent of the monopole structure; it is the integer of a monopole over the internal base, not
over a sphere in the emergent space.

The reading of the winding as electric charge, $q_{\mathrm{eff}} = w \cdot e$, is not derived: it needs a
specified relation between the internal fibre and an electromagnetic potential of the emergent description, which
is not supplied (the gauge connection of the gauge-structure analysis is itself supplied). Charge quantisation in
the emergent description is open.

## 2. The open monopole question

On the full Hopf base:

$$
\pi_2(S^2) \cong \mathbb{Z}
$$

but this $S^2$ is the base of the internal Hopf fibration of the projection fibre, and whether its
$\pi_2$ classifies magnetic defects is not derived; Dirac monopoles are classified by $U(1)$ bundles
over a sphere surrounding the source in the emergent space.

The capacity axiom bounds a per-node relaxation rate; it bounds no continuum field strength, and no
bound on the fibre-phase gradient is derived from it, so such a bound is used only as a hypothesis.
Neither selects a region of the base: the Hopf fibration is a principal $U(1)$ bundle with a
homogeneous base, so no point of $S^2$ is distinguished and no fibre degenerates.
On a **chosen** domain with two disjoint discs removed,

$$
S^2_{\mathrm{adm}} \simeq S^1 \times (0,1),
\qquad
\pi_2(S^2_{\mathrm{adm}}) = 0 .
$$

This computation does not exclude magnetic monopoles. An exclusion would need two steps that are not
derived: that the admissible base is such a domain, obtained from the projection structure rather
than chosen, and that $\pi_2$ of this internal base classifies the magnetic defects of the projected
description. Assuming both would build the exclusion into the assumptions. The absence of magnetic
monopoles is therefore open.

## 3. Projective chirality and parity violation

The non-injective projection introduces an orientation dependence:

$$
\Gamma(Q) \neq \Gamma(-Q)
$$

This defines **projective chirality**, which:

- breaks parity structurally
- selects one orientation of winding invariants
- provides a mechanism for the observed V−A asymmetry

# Topological vs Standard Framework

In standard gauge theory, monopoles are topologically admissible and their absence requires a
dynamical explanation. The present paper does not supply a topological alternative.

# Observable Hierarchy

To avoid conflating distinct layers, the paper separates:

- **topological layer**:
  classification of admissible homotopy invariants

- **dynamical layer**:
  relaxation processes and flux constraints

- **spectral layer**:
  admissibility selection and mass hierarchy (O-series)

These layers are complementary:

- topology defines what exists
- dynamics defines how it evolves
- spectral structure defines how it is organised

# Status of the Results

What is rigorously established:

- $\pi_1(S^1) \cong \mathbb{Z}$ → an integer fibre winding, in a fixed fibre or over a trivialising domain (on the
  supplied fibre identification)
- $\pi_2 = 0$ on the chosen domain of the base, without a derived physical consequence
- projective chirality as a structural mechanism

What remains open:

- the identification of the winding with electric charge, and charge quantisation in the emergent description
- absence of magnetic monopoles
- derivation of the admissible base from the projection structure, and extension of
  $\pi_2(C_{\mathrm{eff}}) = 0$ to the full configuration space
- derivation of maximal chirality (strict V−A)
- identification of weak-interaction sectors within Weil blocks

This distinction is explicit throughout the paper.

# Why This Paper Matters

This work is a **structural clarification** of fundamental phenomena.

It shows that:

- the fibre winding
- parity violation

are read as consequences of a single topological structure,
and it delimits what topology alone does not give for magnetic monopoles.

# Structural Role in the Programme

This paper complements the existing Cosmochrony programme:

- White paper: emergence of projection and gauge structure
- Dynamical papers: bounded relational capacity and relaxation
- Spectral programme (O-series): admissibility and hierarchy
- **Topological invariants (this work)**: classification of admissible sectors

Together they provide:

- classification (topology)
- mechanism (dynamics)
- quantification (spectral)

# Interpretation of the Result

The central conceptual outcome is:

- parity violation is **not an external symmetry breaking**
- the integer fibre winding is the integer of the unit monopole over the internal base

Instead:

👉 both are read from admissible topology under projection; the charge and monopole questions stay open

# Outcome

The paper does **not** resolve all open problems.

What it does establish is:

- a classification of admissible topological invariants on the canonical model
- a structural reading of the fibre winding and parity violation, with the link to charge stated as missing
- a clear separation between established results and open questions

# Residual Open Problems

1. **Fibre winding and emergent charge**  
   Derive a relation between the internal fibre and an electromagnetic potential of the emergent
   description, which the reading of the winding as electric charge requires

2. **Admissible base and monopoles**  
   Derive the admissible base from the projection structure, and determine whether $\pi_2$ of the
   Hopf base bears on magnetic defects at all

3. **Derivation of maximal chirality**  
   Show that admissibility enforces strict V−A selection

4. **Spectral identification of weak sectors**  
   Connect SU(2) structure to Weil-block representations

5. **Topological–spectral interface**  
   Understand how admissible invariants map onto spectral hierarchy

# Repository Structure

```text
paper/
├── out/      # Compiled PDF
├── tex/      # LaTeX sources
└── README.md
```
# Citation

If you reference this work, please cite:

J. Beau, Topological Invariants of Admissible Configurations:
Fibre Winding, the Open Charge and Monopole Questions,
and Projective Chirality in Cosmochrony, Zenodo, 2026.
[doi:10.5281/zenodo.19282962](https://doi.org/10.5281/zenodo.19282962)

# Acknowledgements

Portions of the conceptual organisation, structural clarification,
and editorial refinement benefited from iterative interactions with
large language models used as analytical assistants.
All theoretical results and interpretations remain the sole responsibility
of the author.

# Contributions

This repository is intended as a research reference.

Critical feedback, independent verification, and extensions of the
topological results to the full configuration space are welcome.

Please open an issue to discuss conceptual points,
technical details, or possible developments.
