**Arithmetic as Projection Residue: A Foundation of Number via Informational Constructivism (IC)**

**Abstract**  
This paper reformulates arithmetic from first principles within the framework of Informational Constructivism (IC). It proposes that integers are not ontic entities composed from atomic parts, but stabilized residues of constrained distinction processes. The traditional view of numbers as countable objects is replaced with a process-first ontology, where arithmetic structure emerges from recursive distinction operations acting on a substrate of indistinction under finite constraint. Within this framework, primes, composites, arithmetic operations, and analytic objects like the Riemann zeta function are interpreted as projection residues stabilized through recursive interaction between observer, constraint, and indistinct structure.

---

### 1. Introduction: Informational Constructivism Primer

Informational Constructivism (IC) is a foundational theory based on the principle that all structure arises from distinction. Pure non-distinction is logically and structurally impossible. Distinctions are enacted through operations (denoted \( \Delta \)) performed under finite constraints by observers embedded within a system.

**Core Components:**

- **Spaces and Objects:**
  - \( \mathcal{S} \): state space of distinguishability structures  
  - \( R^- \subseteq \mathcal{S} \): maximally symmetric indistinct substrate (e.g., fully connected graph)  
  - \( M_O \subseteq \mathcal{S} \): memory of observer-stabilized structures  

- **Distinction Operations (\( \Delta \))**:
  - \( \Delta_{\text{gen}}: \mathcal{S}_0 \rightarrow \mathcal{S}_1 \times \mathcal{S}_1 \): symmetry-breaking bifurcation  
  - \( \Delta_{\text{proj}}: \mathcal{S} \rightarrow M_O \): projection into memory via constraint-induced equivalence: \( \Delta_{\text{proj}}(s) = [s]_C \)  
  - \( \Delta_{\text{self}}: M_O \rightarrow M_O \): recursive operation on memory structure, enabling identity and learning  

- **Observer (O):**  
  \[ O = (M_O, C, \Delta) \]  
  where \( M_O \) is memory, \( C \) is a constraint functional, and \( \Delta \) is the observer’s distinction toolkit.  

- **Constraint (C):**  
  A projection-defining relation: \( \pi_C: \mathcal{S} \rightarrow M_O \) by \( [s]_C \in M_O \). It bounds distinguishability through an induced equivalence relation \( \sim_C \).  

---

### 2. Integer Regularization Principle (IC-L1)

All integers are stabilized residues of constrained distinction paths. They are not composed from atomic parts, but emerge from collapsed recursive operations constrained by the observer’s resolution.

We define an integer as:  
\[
n := \Delta_{\text{proj}}(\delta), \text{ where } \delta \in \mathcal{M}_\Delta \text{ and } [\delta]_C = m_n \in M_O
\]

- \( \mathcal{M}_\Delta \): the free monoid of composable Δ-paths  
- \( P = \{p_i\} \): irreducible Δ-operators (“prime voids”)  
- \( \delta = \Delta_{p_1} \circ \Delta_{p_2} \circ \ldots \): path composition  
- \( C \): defines \( \sim_C \) on \( \mathcal{M}_\Delta \)  

A **prime** projection residue \( m_p \in M_O \) satisfies:  
\[
\nexists \delta_1, \delta_2 \in \mathcal{M}_\Delta \setminus \{\delta_p\} \text{ such that } \Delta_{\text{proj}}(\delta_1 \circ \delta_2) = m_p
\]

This reframes primes as projection-irreducible residues under constraint—not syntactic artifacts.

---

### 3. Foundations of IC Arithmetic

- **Prime Voids**: Δ-paths that generate irreducible residues in memory  
- **Composite Residues**: Stabilized Δ-paths composed from multiple irreducible Δ-generators  
- **Regularization**: Observer constraint \( C \) induces projection collapse onto stable memory classes

---

### 4. Worked Example: 6 as \( \Delta \)-Collapse Residue

Let:  
- \( P = \{p_1 = 2, p_2 = 3\} \)  
- \( \delta = \Delta_2 \circ \Delta_3 \in \mathcal{M}_\Delta \)  
- \( C \) defines \( \delta \sim_C \delta' \Rightarrow \Delta_{\text{proj}}(\delta) = \Delta_{\text{proj}}(\delta') \)  

Then:  
\[
\Delta_{\text{proj}}(\delta) = m_6 \in M_O
\]

This is not due to multiplication but to the constraint-induced stabilization of the Δ-path structure.

---

### 5. Integer Structure Grid (ISG)

The ISG encodes stabilized Δ-paths as geometric memory embeddings. Each point \( m_n \) has metadata:  
\[
v_n = (\text{max exponent}, \text{sum of exponents}, \text{Δ-depth}, \text{Δ}_\text{self} \text{ cycles}, C_\text{cost})
\]  
It reflects both path structure and constraint effort. Primes map to (1,1), composites elsewhere.

---

### 6. Zeta Function as Structural Sum

Let \( N(\delta) = \prod p_i \) be the norm of a Δ-path. Then:  
\[
\zeta(s) = \sum_{\delta \in \mathcal{M}_\Delta^{\text{sqf}}} \frac{1}{N(\delta)^s} = \prod_{p \in P} \left(1 - \frac{1}{p^s} \right)^{-1}
\]  

- Zeta sums square-free Δ-paths.  
- \( N(\delta) \) reflects distinguishability cost.  
- This arises from IC structure—not retrofitted.


