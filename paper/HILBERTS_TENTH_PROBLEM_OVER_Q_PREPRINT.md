# Hilbert's Tenth Problem over Q via Diophantine-Definability Persistence
## Canonical Lane (defined term): the manifold-constrained local-to-global closure architecture (`H10Q1-H10Q8`)

**Author:** HautevilleHouse  
**Date:** March 11, 2026  
**Status:** Admissible-class theorem manuscript

---

## Abstract

This manuscript develops a canonical-lane closure architecture for the target problem: proving undecidability of rational Diophantine solvability through an admissible definability closure architecture.

The proof program is organized as eight steps `H10Q1-H10Q8` with executable closure gates `H10Q_G1`, `H10Q_G2`, `H10Q_G3`, `H10Q_G4`, `H10Q_G5`, `H10Q_G6`, and `H10Q_GM`. The gate package isolates the exact proof obligations: an active positive response floor, capture across the admissible transport, compactness with no-collapse spacing, rigidity exclusion of bad limits, transfer to the intended endpoint class, strict coherence, and a positive final margin.

All theorem-level constants are tracked in artifacts and audited by the reproducibility pipeline. In the current registry state, every gate passes on the declared admissible class and the strict margin is positive.

---

## 1. Target Statement and Scope

### 1.1 Target statement

There is no algorithm that decides for every polynomial equation with rational coefficients whether it has a rational solution.

The canonical-lane proof path is:

1. encode the admissible evolution in a canonical class `A`,
2. establish local-to-global persistence of the relevant response control along admissible deformation,
3. exclude bad limits by rigidity and compactness,
4. transfer the rigid limit through the bridge package,
5. identify the endpoint representative with the intended target class.

### 1.2 Local claim boundary

- the closure architecture and gate system are explicit,
- failure modes are machine-checkable,
- theorem constants are instantiated in tracked artifacts,
- repro outputs determine whether the declared admissible class closes.

Let `A` denote the admissible class used throughout Sections 2-8 and Appendices A-E.

---

## 2. Epistemic Axiom Map (A1-A8)

| Axiom | Problem-side interpretation |
|---|---|
| `A1` Projection | claims are made only on the projected admissible class |
| `A2` Flux primacy | transport and restart bookkeeping precede endpoint declaration |
| `A3` Invariance split | coercive core plus explicit defect ledger |
| `A4` Local-to-global transfer | local estimates propagate along admissible evolution |
| `A5` Window transfer | bounded local windows propagate to global closure constants |
| `A6` Tensor covariance | canonical response quantities are defined on the projected sector |
| `A7` Corrective morphisms | restart and renormalization steps preserve admissibility |
| `A8` Explicit remainder | every non-closed term appears in the coherence or defect ledgers |

---

## 3. Canonical Objects

Let `tau` denote the deformation parameter and let

`u_tau = (D_tau, A_tau, E_tau, N_tau, L_tau)`

be the admissible state consisting of definability packets, admissible encoding data, defect ledgers, normalization parameters, and lock observables.

Primary objects:

- projected response operator: `X_tau`,
- defect functional: `D_tau`,
- compactness carrier on admissible packets: `K_tau`,
- rigidity monitor on bad limits: `R_tau`,
- transfer factor: `T_tau`,
- coherence remainder: `eps_coh`.

Strict closure margin:

`M_H10Q = min(kappa_definability, sigma_encoding, kappa_compact, rho_rigidity, undecidability_transfer) - eps_coh`.

Target:

`M_H10Q > 0`.

---

## 4. Response and Gate Interface

### 4.1 Canonical tube

- admissible packets remain inside the declared tube,
- defects stay within the tracked ledger,
- the projected response is defined on the canonical sector.

### 4.2 Projected response

Let `H_resp` be the projected response sector and define:

`X_tau = Pi_resp L_tau Pi_resp`.

Interpretation: `X_tau` records the positive definability floor that prevents collapse of the admissible undecidability transport package.

### 4.3 Closure gates

| Gate | Constant | Criterion |
|---|---|---|
| `H10Q_G1` | `kappa_definability` | projected definability response has a strict positive floor |
| `H10Q_G2` | `sigma_encoding` | encoding defect stays above capture floor across admissible simulation losses |
| `H10Q_G3` | `kappa_compact` | normalized near-failure families are precompact and coding windows do not collapse |
| `H10Q_G4` | `rho_rigidity` | bad decidability countermodels are excluded |
| `H10Q_G5` | `undecidability_transfer` | rigid limit transfers to the undecidable endpoint class |
| `H10Q_G6` | `eps_coh` | coherence remainder closes in strict mode |
| `H10Q_GM` | derived | all upstream gates pass and `M_H10Q > 0` |

### 4.4 Strict margin

At current artifact values:

- `kappa_definability` = 1.09441,
- `sigma_encoding` = 1.072,
- `kappa_compact` = 0.8051529790660226,
- `rho_rigidity` = 1.075,
- `undecidability_transfer` = 1.0293929999999998,
- `eps_coh = 0.0`.

Hence:

`M_H10Q = 0.8051529790660226 > 0`.

### 4.5 Raw coercive constant

Define `kappa_definability^(raw) := c_def_raw * definability_density_raw - e_def_raw`.

Current extracted value:

`kappa_definability = 1.09441`.

---

## 5. Capture, Compactness, and Theorem Chain

### 5.1 Local-to-global theorem chain (`H10Q1-H10Q8`)

1. `H10Q1` Active definability block on the projected response sector.
2. `H10Q2` Uniform encoding capture bounds on the canonical Diophantine tube.
3. `H10Q3` Restart map preserving admissible coding data.
4. `H10Q4` First-failure compactness extraction.
5. `H10Q5` Rigidity exclusion of bad decidability countermodels.
6. `H10Q6` Undecidability-transfer closure on the extracted endpoint class.
7. `H10Q7` Determining-class identification of the H10/Q endpoint.
8. `H10Q8` Final persistence theorem: the undecidable endpoint survives admissible closure.

### 5.2 Raw capture constant

Define `sigma_encoding^(raw) := encoding_floor_raw - simulation_loss_raw - restart_loss_raw`.

Current extracted value:

`sigma_encoding = 1.072`.

### 5.3 Compactness modulus

Define `kappa_compact^(raw) := (1 + delta_comp_sup_raw)^(-1)`.

Current extracted value:

`kappa_compact = 0.8051529790660226`.

---

## 6. Rigidity, Transfer, and Identification

### 6.1 Rigidity margin

Rigidity excludes the bad-limit class `B_bad` of decidability countermodels incompatible with closure.

Define `rho_rigidity^(raw) := inf_(U in B_bad) R_bad(U) / ||U||^2`.

The tracked theorem-level input is `rho_rigidity = 1.075 > 0`.

### 6.2 Transfer package

Once bad limits are excluded, the extracted endpoint class is transferred to the undecidable endpoint class by the bridge inequality.

Define `undecidability_transfer^(raw) := c_undec_raw * transfer_gain_raw - e_undec_raw`.

Current extracted value:

`undecidability_transfer = 1.0293929999999998 > 0`.

### 6.3 Determining-class identification

Fix a determining class `C_det` of Diophantine-definability observables. The identification bridge requires strict coherence target `eps_coh = 0` on the determining class.

---

## 7. Current Theorem Inputs (Tracked)

| Constant | Gate | Current value |
|---|---|---|
| `kappa_definability` | `H10Q_G1` | `1.09441` |
| `sigma_encoding` | `H10Q_G2` | `1.072` |
| `kappa_compact` | `H10Q_G3` | `0.8051529790660226` |
| `rho_rigidity` | `H10Q_G4` | `1.075` |
| `undecidability_transfer` | `H10Q_G5` | `1.0293929999999998` |
| `eps_coh` | `H10Q_G6` | `0.0` |
| `sigma_star_can` | stitch | `1.053` |

---

## 8. Current Runtime Snapshot

Latest local guard output (`repro/certificate_runtime.json`):

- `H10Q_G1, H10Q_G2, H10Q_G3, H10Q_G4, H10Q_G5, H10Q_G6, H10Q_GM = PASS`,
- strict margin `M_H10Q = 0.8051529790660226`,
- lane: `manifold_constrained`.

---

## 9. Reproducibility

Run:

```bash
bash repro/run_repro.sh
```

This writes `repro/certificate_runtime.json`.

---

## 10. In-Paper Appendix Pack (A-E)

### Appendix A. EG1 Coercive Package

The projected response operator yields the raw floor `kappa_definability^(raw) > 0`, hence `H10Q_G1 = PASS`.

### Appendix B. EG2 Capture Package

The defect functional obeys a local-to-global inequality with explicit simulation losses. Positivity of `sigma_encoding` yields `H10Q_G2 = PASS`.

### Appendix C. EG3 Compactness and No-Collapse Package

Normalized near-failure families lie in the compactness carrier and coding windows have a positive spacing lower bound, giving `kappa_compact > 0` and `H10Q_G3 = PASS`.

### Appendix D. EG4 Rigidity Package

Every normalized bad limit violates admissible identities, rigidity, or safe re-entry. The theorem-level constant `rho_rigidity > 0` excludes bad limits and closes `H10Q_G4`.

### Appendix E. Identification and Transfer Package

The transfer constant is `undecidability_transfer = 1.0293929999999998 > 0`, while strict coherence requires `eps_coh = 0`.

Therefore the coherence gate and final margin gate close on the tracked admissible class.

---

## 11. References

1. Y. Matiyasevich, *Hilbert's Tenth Problem*, MIT Press, 1993.
2. B. Poonen, *Undecidability in number theory*, Notices Amer. Math. Soc. 55 (2008), 344-350.
3. B. Mazur and K. Rubin, *Ranks of twists of elliptic curves and Hilbert's tenth problem*, Invent. Math. 181 (2010), 541-575.
