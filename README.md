This repository contains the source of the **Topological Invariants** Cosmochrony paper  
*Topological Invariants of Admissible Configurations:
Charge Quantisation, Absence of Magnetic Monopoles,
and Projective Chirality in Cosmochrony*.

This work establishes the **topological layer** of the Cosmochrony framework,
complementary to the dynamical and spectral analyses developed in previous papers.

While earlier works derived:
- the emergence of charge from non-injective projection
- the bounded-flux constraint and its dynamical consequences
- the spectral admissibility hierarchy

they left open a fundamental question:

**what topological invariants remain admissible under the projection constraint,
and what physical consequences do they impose?**

The present work answers that question.

# Core Result

The paper establishes three unified structural results:

- **Charge quantisation** arises from  
  $\pi_1(S^1) \cong \mathbb{Z}$

- **Magnetic monopoles are excluded** on the canonical admissible model via  
  $\pi_2 = 0$

- **Parity violation** arises from a structural mechanism of  
  **projective chirality**

These are not independent phenomena, but consequences of a single principle:

> admissibility under non-injective projection determines both
> the available topological invariants and their orientation.

# Main Structural Results

The paper proves three central points.

## 1. Charge as a π₁ invariant

The U(1) fibre of the Hopf fibration supports a winding number:

$$
\pi_1(S^1) \cong \mathbb{Z}
$$

This winding number is identified with electric charge.

Unlike the Dirac mechanism, charge quantisation here:
- does **not require magnetic monopoles**
- follows directly from the topology of the fibre

## 2. Topological exclusion of monopoles

In the unconstrained case:

$$
\pi_2(S^2) \cong \mathbb{Z}
$$

supports Dirac monopoles and their non-abelian generalisations
('t Hooft–Polyakov, classified by $\pi_2(G/H)$).

Under the bounded-flux constraint, the admissible base becomes:

$$
S^2_{\mathrm{adm}} \simeq S^1 \times (0,1)
$$

which implies:

$$
\pi_2(S^2_{\mathrm{adm}}) = 0
$$

Thus:

- isolated magnetic monopoles are **topologically excluded**
- their empirical absence is explained structurally

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

The paper establishes a sharp contrast with the standard paradigm:

- **Standard gauge theory**:
    - monopoles are topologically admissible
    - their absence requires a dynamical explanation

- **Cosmochrony**:
    - monopoles are topologically excluded
    - their absence follows from admissibility constraints

This inversion is central to the result.

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

- $\pi_1(S^1) \cong \mathbb{Z}$ → charge quantisation (canonical model)
- $\pi_2 = 0$ → absence of monopoles (canonical model)
- projective chirality as a structural mechanism

What remains open:

- extension of $\pi_2(C_{\mathrm{eff}}) = 0$ to the full configuration space
- derivation of maximal chirality (strict V−A)
- identification of weak-interaction sectors within Weil blocks

This distinction is explicit throughout the paper.

# Why This Paper Matters

This work is a **structural clarification** of fundamental phenomena.

It shows that:

- charge
- absence of monopoles
- parity violation

are not independent inputs of the theory,
but consequences of a single topological structure.

It converts empirical facts into **topological constraints**.

# Structural Role in the Programme

This paper complements the existing Cosmochrony programme:

- White paper: emergence of projection and gauge structure
- Dynamical papers: bounded flux and relaxation
- Spectral programme (O-series): admissibility and hierarchy
- **Topological invariants (this work)**: classification of admissible sectors

Together they provide:

- classification (topology)
- mechanism (dynamics)
- quantification (spectral)

# Interpretation of the Result

The central conceptual outcome is:

- the absence of monopoles is **not contingent**
- parity violation is **not an external symmetry breaking**
- charge quantisation is **not derived from monopoles**

Instead:

👉 all three arise from admissible topology under projection

# Outcome

The paper does **not** resolve all open problems.

What it does establish is:

- a complete classification of admissible topological invariants (canonical model)
- a structural explanation for key empirical facts
- a clear separation between established results and open questions

# Residual Open Problems

1. **Global extension of π₂ = 0**  
   Prove that the triviality of π₂ holds on the full configuration space

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
Charge Quantisation, Absence of Magnetic Monopoles,
and Projective Chirality in Cosmochrony, Zenodo, 2026.

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
