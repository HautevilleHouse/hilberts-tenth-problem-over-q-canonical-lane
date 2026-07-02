# Reviewer Map

    ## Claim Scope

    - Canonical-lane claim: inside the `manifold_constrained` lane, if the theorem chain in this repository holds and the guard certificate passes, the repository-level closure claim is satisfied.
    - Standard target claim: carried by the in-repo bridge theorems tying the lane to the target statement.

    ## Theorem Dependency Chain

    1. `EG1`: coercive response and active control floor.
    2. `EG2`: capture and admissible continuation.
    3. `EG3`: compactness and no-collapse spacing.
    4. `EG4`: rigidity and transfer.
    5. Identification bridge: strict coherence on the determining class.
    6. Scalar closure: `H10Q_G1, H10Q_G2, H10Q_G3, H10Q_G4, H10Q_G5, H10Q_G6, H10Q_GM` all `PASS`.

    Primary files:

    - `paper/HILBERTS_TENTH_PROBLEM_OVER_Q_PREPRINT.md`
    - `notes/EG1_public.md`
    - `notes/EG2_public.md`
    - `notes/EG3_public.md`
    - `notes/EG4_public.md`
    - `notes/IDENTIFICATION_BRIDGE.md`

    ## Closure Gates

    | Gate | Constant | Description |
    |------|----------|-------------|
    | `H10Q_G1` | `kappa_definability` | projected definability response has a strict positive floor |
| `H10Q_G2` | `sigma_encoding` | encoding defect stays above capture floor across admissible simulation losses |
| `H10Q_G3` | `kappa_compact` | normalized near-failure families are precompact and coding windows do not collapse |
| `H10Q_G4` | `rho_rigidity` | bad decidability countermodels are excluded |
| `H10Q_G5` | `undecidability_transfer` | rigid limit transfers to the undecidable endpoint class |
| `H10Q_G6` | `eps_coh` | strict coherence / identification closure |
| `H10Q_GM` | derived | final strict margin |

    ## Falsification Conditions

    - `repro/certificate_runtime.json` has any non-`PASS` gate.
    - `lane.active_lane != "manifold_constrained"`.
    - `all_pass != true`.
    - Any manifest hash mismatch under `repro/repro_manifest.json`.
    - A certified counterexample to any EG theorem statement used in the paper.
