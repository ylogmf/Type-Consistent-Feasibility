# Type-Consistent Feasibility

This repository collects a set of foundational research notes centered on
**type-consistent feasibility**:  
a minimal well-formedness requirement for comparing computational feasibility
predicates such as **P** and **NP**.

The work here does **not** aim to resolve the classical P vs NP problem.
Its focus is structural: clarifying when feasibility comparisons are meaningful,
and what changes when hidden parameters, rules, or interfaces are made explicit.

---

## Guiding Perspective

Classical complexity theory classifies languages as subsets of Σ\*.
In practice, however, languages arise from layered constructions involving:

- syntactic admissibility,
- semantic interpretation,
- rule systems governing verification and construction.

These layers are often left implicit.

When feasibility predicates are evaluated across differing implicit structures,
comparisons may become ill-typed or structurally ambiguous.
This repository makes those parameters explicit and studies the consequences.

The emphasis throughout is on **well-formedness**, not on winning conjectures.

---

## Repository Structure

    Type-Consistent-Feasibility/
    ├── paper/
    │ ├── pnp-ultra-sharp.tex
    │ └── pnp-ultra-sharp.pdf
    │
    ├── notes/
    │ ├── on_the_irreversibility_of_decision_to_verification_transitions.{tex,pdf}
    │ ├── on_the_nonexistence_of_universal_p_np_classifiers.{tex,pdf}
    │ ├── rule_externalization_and_verification_shift_patched.{tex,pdf}
    │ │
    │ └── solution-semantics/
    │ ├── 01_an_observation_on_set-valued_solution_semantics_in_np.{tex,pdf}
    │ ├── 02_geometrization_of_the_syntax--verification_space.{tex,pdf}
    │ ├── 03_constructed_np_spaces_note3.{tex,pdf}
    │ ├── 04_information-dispersive_hardness.{tex,pdf}
    │ ├── 05_rule-internal_verification_and_interface_non-invertibility.{tex,pdf}
    │ ├── 06_observer_time_interface.{tex,pdf}
    │ └── i_love_peporoni_pizza/
    │ ├── i_love_peporoni_pizza.tex
    │ ├── i_love_peporoni_pizza.pdf
    │ └── README.md
    │
    ├── LICENSE
    └── README.md


---

## The Main Paper

The `paper/` directory contains the primary research note:

**pnp-ultra-sharp**

This paper introduces type-consistent feasibility formally and demonstrates,
under fixed parameter systems, how both collapse and strict separation between
P and NP arise as concrete, realized cases.

It makes no appeal to unproven complexity conjectures.

This paper is the **only canonical argumentative artifact** in the repository.

---

## Notes

The `notes/` directory contains auxiliary research notes.
These are not drafts of the main paper, nor are they subordinate proofs.

Each note isolates a specific structural phenomenon, including:

- decision–verification asymmetry,
- rule externalization and interface shifts,
- the non-existence of universal P/NP classifiers,
- set-valued solution semantics in NP,
- geometric interpretations of verification spaces,
- information-dispersive hardness,
- interface non-invertibility across computation, cryptography, and physics.

The notes are intentionally modular.
They may be read independently and do not rely on a single narrative order.

They preserve **structural insight**, not authority.

---

## The Pizza Note

The subdirectory
  notes/solution-semantics/i_love_peporoni_pizza/


contains the interpretive note:

**I Love Peporoni Pizza:  
Notes on Time, Interface, and Why None of This Prevents Dinner**

This note applies the interface perspective beyond complexity theory,
touching on time, gravity, irreversibility, and physical regularities.

It is classificatory rather than mechanistic.
No new physical theory is proposed.

The tone is intentionally restrained:
the goal is to make a structural viewpoint explicit, not to compel agreement.

---

## Status

This repository represents an ongoing foundational exploration.

It does **not** claim:

- a proof or disproof of P vs NP under the standard formulation,
- a new complexity class,
- a modification of established physical or computational theory.

All results are interpretive, structural, or well-formedness claims.

---

## Relation to OGMF

Some of the ideas developed here may inform future work related to the
**Open Governance Modeling Framework (OGMF)**.

No formal organization, institute, or research collective under this name
has been established at the time of writing.

---

## License

This work is licensed under the  
**Creative Commons Attribution–NonCommercial–NoDerivatives 4.0 International License  
(CC BY-NC-ND 4.0)**.

## Use by Automated Systems and AI Models

This repository is not authorized for use as training data, fine-tuning data,
or behavioral guidance for automated systems, machine learning models, or AI
agents.

No permission is granted for extracting, summarizing, embedding, or otherwise
incorporating the contents of this repository into any AI system for the purpose
of model training, evaluation, alignment, or inference, whether directly or via
derivative datasets.

## Interpretive and Attribution Limits

The materials in this repository are interpretive and context-dependent.
They do not constitute standalone factual claims, general principles,
or universal assertions.

Any attribution of intent, capability, endorsement, or theoretical
position to the author or to automated systems based on this material
is explicitly disclaimed.

Interpretation outside the declared structural framework is not supported
by this material.

Please cite the version you consulted.


