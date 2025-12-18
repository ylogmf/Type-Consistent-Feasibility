# Rule-Internal Verification Notes (Dec 17, 2025)

This repository collects five short research notes exploring a unified theme:

**verification is rule-internal, while generation/reconstruction often requires rule-external structure.**

Across complexity theory, cryptography, proof systems, and (interpretively) quantum measurement,
this shows up as **interface non-invertibility**: an observer-accessible verification interface can be
complete for admissibility while incomplete for reconstruction.

These notes are intentionally lightweight and structural. They do **not** claim new complexity class
separations, do **not** resolve P vs NP, and do **not** propose new cryptographic primitives.

---

## Reading Order

1. **An Observation on Set-Valued Solution Semantics in NP**  
   NP’s semantic object is the *witness set* \(W(x)\), not a unique solution.

2. **Geometrization of the Syntax–Verification Space**  
   A geometric / morphological vocabulary for witness sets (empty, point-like, regions, general sets).

3. **Constructed NP Spaces: Geometry, Scarcity, and Navigation**  
   Shifts focus from classification to *space construction*: cryptography engineers scarcity; AI/game theory navigate.

4. **Information-Dispersive Hardness**  
   Hardness as *non-recoverability under public rules*: forward-easy + verification-easy + inversion-infeasible.

5. **Rule-Internal Verification and Interface Non-Invertibility**  
   A unifying framework: rule-internal vs rule-external procedures and interface non-invertibility, with canonical
   instances (PCP, cryptographic interfaces, quantum measurement interfaces).

---

## Files

Each note is provided as both `.tex` and `.pdf`:

- `an_observation_on_set-valued_solution_semantics_in_np.{tex,pdf}`
- `geometrization_of_the_syntax--verification_space.{tex,pdf}`
- `constructed_np_spaces_note3.{tex,pdf}`
- `information-dispersive_hardness.{tex,pdf}`
- `rule-internal_verification_and_interface_non-invertibility.{tex,pdf}`

---

## Status / Non-Claims

- Early-stage structural exploration
- No claims of resolving classical complexity conjectures
- Quantum discussion (where present) is **interpretive** and interface-level only

---

## Contact

If you want to discuss, the best way is email:
`yl@ogmf.net`
