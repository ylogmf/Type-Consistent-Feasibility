# pizza — Computer Science Wrapper

## Positioning

This document outlines a computer science–oriented extension of **pizza**,  
which serves as the foundational reference.

This wrapper does **not** modify the core claims of *pizza*.  
It adopts the framework introduced in *pizza* and applies it to questions in
theoretical computer science, particularly decision, verification, and
complexity semantics.

Non-claims:
- This work does not resolve P vs NP.
- This work does not introduce new complexity separations.
- This work does not propose new computational models.

---

## 0. Abstract

- This note builds on *pizza* as a foundational boundary-setting framework.
- It clarifies the semantic roles of decision and verification under external
  interface constraints.
- The goal is conceptual clarification, not technical breakthrough.

---

## 1. Introduction

- Long-standing confusion in complexity theory regarding P and NP.
- Decision and verification are often treated as comparable capabilities.
- This wrapper re-examines these notions under the *pizza* framework.

---

## 2. Framework Assumptions (Reference to pizza)

- Internal derivation vs external verification.
- Facts arise only from internal derivation.
- Observation and verification do not constitute proof.
- External interfaces are assumed to be generally non-invertible.

---

## 3. Decision as an Internal Capability (P)

- P as derivability under fixed rules and encodings.
- Closure and termination properties of internal decision.
- What P does **not** represent.

---

## 4. Verification as an External Interface (NP)

- NP as existential verification.
- Witness-set semantics.
- Verification without construction.
- NP as the natural interface under external observation.

---

## 5. Limits of Reconstruction

- Why verification does not guarantee recoverability.
- Exhaustive search and auxiliary structure as exceptions.
- This section states a boundary, not a lower bound.

---

## 6. Reframing the P vs NP Question

- Conditions under which P vs NP is well-typed.
- Conditions under which the comparison is ill-typed.
- Explicit non-claims regarding separation or collapse.

---

## 7. Implications for Complexity Theory

- Limits of classification.
- Structural reasons for the absence of universal classifiers.
- Consequences for how complexity questions should be framed.

---

## 8. Conclusion

- Summary of clarification achieved.
- Reinforcement of *pizza* as the foundational reference.
- Emphasis on boundary-setting rather than result competition.
