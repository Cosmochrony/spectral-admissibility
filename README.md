This repository contains the source of the **Spectral Admissibility 1.0** Cosmochrony paper  
*Spectral Admissibility and Non-Abelian Mode Resilience in the Q₈ Cayley Graph under Bounded Flux*.

This work develops the first analytically tractable instance of the **spectral admissibility
programme** within the Cosmochrony framework.

On relational graphs equipped with a bounded-flux constraint

|∂ₜχ_v| ≤ c_χ

the admissible amplitude of each spectral mode is limited by the Laplacian eigenvalue of the
graph. This induces a hierarchy of dynamically admissible modes across irreducible
representation sectors.

## Core Result

For a relational Laplacian with eigenvalues λₙ, the maximal admissible effective amplitude is

Aₙ^{max} = c_χ / √λₙ

This envelope:

- depends only on the Laplacian spectrum of the relational graph
- induces a hierarchy of admissible amplitudes across representation sectors
- favours the lowest non-abelian sector on the Q₈ Cayley graph by a factor √(4/3)

The envelope is shown to coincide with the **exact saturation boundary** of the
one-mode Dirac–Born–Infeld dynamics, demonstrating that the hierarchy is structurally
stable beyond the perturbative regime.

## Conceptual Structure

Spectral Admissibility integrates:

1. Relational Laplacians on Cayley graphs
2. Representation-theoretic spectral decomposition
3. Bounded-flux dynamical constraints
4. Effective amplitude definition for graph eigenmodes
5. Nonlinear Dirac–Born–Infeld modal reduction

The result provides a concrete demonstration that **bounded substrate capacity
acts as a spectral filter selecting dynamically resilient modes**.

## Extension to Finite SU(2) Subgroups

The analysis is extended from the quaternion group

Q₈

to the binary icosahedral group

2I ⊂ SU(2)

the largest finite subgroup of SU(2).

Using the order-10 generating classes of 2I, the same admissibility envelope
produces a four-level hierarchy across spin sectors with contrast

√(14/9).

Together these cases provide explicit realizations of the spectral admissibility
programme along the chain

Q₈ ⊂ 2I ⊂ SU(2).

## Status

This framework is:

- spectral and representation-theoretic
- analytically tractable
- dynamically validated through DBI reduction
- independent of additional dynamical selection principles

It does not assume:

- fundamental particle fields
- quantum statistics
- specific microscopic dynamics beyond bounded flux capacity

## Repository Structure
```
paper/
├── pdf/ # Compiled Spectral Admissibility PDF
├── tex/ # LaTeX sources
└── README.md
```

## Citation

If you reference this work, please cite:

> J. Beau, *Spectral Admissibility and Non-Abelian Mode Resilience in the Q₈ Cayley Graph under Bounded Flux*, Zenodo, 2026.

## Acknowledgements

Portions of the formal derivations, consistency checks, and editorial refinement
benefited from iterative interactions with large language models used as analytical
assistants.  
All theoretical results and interpretations remain the sole responsibility of the author.

## Contributions

This repository is intended as a research reference.

Critical feedback, mathematical scrutiny, and independent spectral analyses
are welcome.  
Please open an issue to discuss conceptual points, technical details,
or possible extensions.
