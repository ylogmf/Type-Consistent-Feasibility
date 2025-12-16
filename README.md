# Type-Consistent Feasibility

This repository explores **type-consistent feasibility**:
a minimal requirement for making well-formed comparisons between computational
feasibility predicates such as **P** and **NP**.

The goal is not to resolve the classical P vs NP problem,
but to clarify when such comparisons are structurally meaningful.

---

## Motivation

The classical P vs NP question is formulated over languages defined as subsets
of Σ*.

In practice, however, languages arise from layered constructions involving
syntax, semantics, and rule-based admissibility constraints.
These layers are typically left implicit.

When feasibility predicates are evaluated over languages generated under
different implicit assumptions, the resulting comparisons may be ill-typed.

This repository makes those parameters explicit.

---

## Core Idea

Let Θ denote a parameter system governing how a language is formed and interpreted.

A feasibility comparison is **type-consistent** if all predicates involved
are evaluated under the same Θ.

Under this view:

- Comparisons between P and NP are meaningful only relative to a fixed parameter system.
- Once parameters are held fixed, both collapse and strict separation between P and NP
  arise as concrete cases.
- The classical P vs NP question corresponds to a narrow slice of a broader
  feasibility landscape.

The emphasis is on **well-formedness**, not on conclusions.

---

## Repository Structure



    Type-Consistent-Feasibility/
    ├── README.md
    ├── LICENSE
    └── paper/
        ├── pnp-ultra-sharp.tex
        └── pnp-ultra-sharp.pdf
      └── notes/
        ├── on_the_irreversibility_of_decision_to_verification.tex
        ├── on_the_irreversibility_of_decision_to_verification.pdf
        ├── rule_externalization_and_verification_shift.tex
        └── rule_externalization_and_verification_shift.pdf


---

## Paper

The `paper/` directory contains the main research note.

It provides formal definitions and concrete parameterized instances
illustrating feasibility collapse and separation,
without appeal to unproven complexity conjectures.

The paper is the only canonical argumentative artifact in this repository.

---

## Notes

The `notes/` directory contains auxiliary working material that sits alongside,
but outside, the main paper.

These files record local observations, structural intuitions,
and intermediate formulations that informed the development of the core ideas.

Topics explored in the notes include:

- asymmetries between decision and verification
- the role of explicit rule structures in feasibility
- shifts induced by rule externalization

The notes are intentionally kept separate from the main paper.
Nothing in `notes/` should be treated as a formal claim, theorem,
or part of the core argument.

They preserve context, not conclusions.

---

## Status

This is an early-stage foundational exploration.

It does not claim:
- a proof or disproof of P vs NP under the standard formulation
- a new complexity class
- a modification of classical complexity theory

---

## Relation to OGMF

The ideas here are intended to inform future work related to the
**Open Governance Modeling Framework (OGMF)**.

No formal organization or research collective under this name has been
established at the time of writing.

---

## License

This work is licensed under the  
**Creative Commons Attribution–NonCommercial–NoDerivatives 4.0 International License  
(CC BY-NC-ND 4.0)**.