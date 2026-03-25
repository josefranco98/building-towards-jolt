## Building Towards Jolt: Algebraic Foundations of Modern Proof Systems

### Overview
This repository contains my Master’s thesis in Applied Mathematics at Instituto Superior Técnico (grade: 18/20).

The work presents a constructive development of the algebraic foundations underlying modern zero-knowledge proof systems, with a focus on how efficient and scalable verification emerges from a small set of composable algebraic techniques.

---

### Abstract
This work studies the transition from classical interactive proofs to their algebraic counterparts, where computation is encoded through low-degree polynomials and verified probabilistically.

Core tools include polynomial commitments, the Schwartz–Zippel lemma, and multilinear extensions, which together enable succinct verification via random evaluation. The Fiat–Shamir transform is used to remove interaction, yielding non-interactive arguments.

Building on these foundations, the thesis develops the sum-check protocol and the GKR protocol as central mechanisms for algebraic verification. These are then extended to modern lookup arguments, including Plookup and Logup.

The work culminates in the study of Lasso and Jolt, which unify linear verification and modular proof composition into a coherent framework for scalable SNARK construction.

---

### Structure
The thesis follows a bottom-up development:

- Classical and interactive proof systems  
- Zero-knowledge and non-interactive arguments (Fiat–Shamir)  
- Algebraic encodings of computation (multilinear extensions, R1CS)  
- Sum-check protocol  
- GKR protocol  
- Lookup arguments (Plookup, Logup, Lasso)  
- Jolt: lookup-based verification of computation  

---

### Key Ideas
A central theme is the reduction of complex verification tasks to polynomial identities evaluated at random points.

- Multilinear extensions encode discrete computation as algebraic objects  
- Sum-check reduces high-dimensional verification to sequential checks  
- GKR enables efficient verification of layered computations  
- Polynomial commitments enforce identities succinctly  
- Lookup arguments replace circuit constraints with table-based verification  

Together, these techniques show how scalable proof systems emerge from a unified algebraic perspective.

---

### Jolt and Modern Directions
The later part of the thesis focuses on lookup-based proof systems.

Lasso introduces efficient lookup arguments based on structured inner products and sparse representations. Jolt extends this paradigm by expressing full computation (e.g., a RISC-V execution trace) purely through algebraic lookups, avoiding traditional circuit-based encodings.

This reflects a broader shift toward lookup-centric proof system design, where verification is reduced to consistency of table relations rather than arithmetic constraints.

---

### Contents
- [Full thesis (PDF)](building-towards-jolt.pdf)

---

### Author
José Franco
