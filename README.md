This repository contains the source of the **Topological Invariants** Cosmochrony paper  
*Topological Invariants of Admissible Configurations:
Charge Quantisation, the Open Monopole Question,
and Projective Chirality in Cosmochrony*.

This work establishes the **topological layer** of the Cosmochrony framework,
complementary to the dynamical and spectral analyses developed in previous papers.

While earlier works introduced:
- the emergence of charge from non-injective projection
- the capacity axiom [A-cap], a bound on the discrete per-node relaxation rate
- the spectral admissibility hierarchy

they left open a fundamental question:

**what topological invariants remain admissible under the projection constraint,
and what physical consequences do they impose?**

The present work answers that question.

# Core Result

The paper establishes two structural results and records one open question:

- **Charge quantisation** arises from  
  $\pi_1(S^1) \cong \mathbb{Z}$

- **$\pi_2 = 0$ on a chosen domain** of the Hopf base, with two disjoint discs removed;
  this does **not** exclude magnetic monopoles, whose absence remains open

- **Parity violation** arises from a structural mechanism of  
  **projective chirality**

Charge and parity violation are read as consequences of a single principle:

> admissibility under non-injective projection determines both
> the available topological invariants and their orientation.

# Main Structural Results

The paper examines three points; their status is stated in each.

## 1. Charge as a π₁ invariant

The U(1) fibre of the Hopf fibration supports a winding number:

$$
\pi_1(S^1) \cong \mathbb{Z}
$$

This winding number is identified with electric charge.

Unlike the Dirac mechanism, charge quantisation here:
- does **not require magnetic monopoles**
- follows directly from the topology of the fibre

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

- $\pi_1(S^1) \cong \mathbb{Z}$ → charge quantisation (on the supplied fibre identification)
- $\pi_2 = 0$ on the chosen domain of the base, without a derived physical consequence
- projective chirality as a structural mechanism

What remains open:

- absence of magnetic monopoles
- derivation of the admissible base from the projection structure, and extension of
  $\pi_2(C_{\mathrm{eff}}) = 0$ to the full configuration space
- derivation of maximal chirality (strict V−A)
- identification of weak-interaction sectors within Weil blocks

This distinction is explicit throughout the paper.

# Why This Paper Matters

This work is a **structural clarification** of fundamental phenomena.

It shows that:

- charge
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
- charge quantisation is **not derived from monopoles**

Instead:

👉 both arise from admissible topology under projection; the monopole question stays open

# Outcome

The paper does **not** resolve all open problems.

What it does establish is:

- a classification of admissible topological invariants on the canonical model
- a structural reading of charge quantisation and parity violation
- a clear separation between established results and open questions

# Residual Open Problems

1. **Admissible base and monopoles**  
   Derive the admissible base from the projection structure, and determine whether $\pi_2$ of the
   Hopf base bears on magnetic defects at all

2. **Derivation of maximal chirality**  
   Show that admissibility enforces strict V−A selection

3. **Spectral identification of weak sectors**  
   Connect SU(2) structure to Weil-block representations

4. **Topological–spectral interface**  
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
Charge Quantisation, the Open Monopole Question,
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
