# Wave Board (first program)

A curated, single-cycle subset of the backlog for the first Drips Wave, chosen
to be **independent**, **completable in one cycle**, and **representative** of
the project. It is deliberately a small subset of the full backlog, with a
bounded points budget.

Point values are assigned in the Drips Wave maintainer dashboard (Trivial 100 /
Medium 150 / High 200). The labels here are the honest pre-estimate.

## Budget

| Complexity | Issues | Points each | Subtotal |
| ---------- | -----: | ----------: | -------: |
| Trivial | 8 | 100 | 800 |
| Medium | 10 | 150 | 1,500 |
| High | 2 | 200 | 400 |
| **Total** | **20** | | **2,700** |

## Trivial (100 points)

| # | Title |
| - | ----- |
| [#20](https://github.com/StellarFoundry/stellar-contract-platform/issues/20) | docs(repro): document the Stellar contract build metadata vocabulary |
| [#23](https://github.com/StellarFoundry/stellar-contract-platform/issues/23) | docs(security): document every heuristic with rationale |
| [#33](https://github.com/StellarFoundry/stellar-contract-platform/issues/33) | fix(spec): reject trailing bytes after the final spec entry |
| [#35](https://github.com/StellarFoundry/stellar-contract-platform/issues/35) | test(interface): expand known-value fingerprint vectors |
| [#40](https://github.com/StellarFoundry/stellar-contract-platform/issues/40) | docs(troubleshooting): expand error-code guidance |
| [#102](https://github.com/StellarFoundry/stellar-contract-platform/issues/102) | docs(config): document configuration precedence |
| [#112](https://github.com/StellarFoundry/stellar-contract-platform/issues/112) | docs(events): document the event JSON schema |
| [#130](https://github.com/StellarFoundry/stellar-contract-platform/issues/130) | docs: add a Stellar/Soroban glossary |

## Medium (150 points)

| # | Title |
| - | ----- |
| [#2](https://github.com/StellarFoundry/stellar-contract-platform/issues/2) | test(output): add golden-file tests for every report kind |
| [#3](https://github.com/StellarFoundry/stellar-contract-platform/issues/3) | test(interface): add property tests for canonicalization idempotence |
| [#6](https://github.com/StellarFoundry/stellar-contract-platform/issues/6) | feat(spec): make unsupported spec entries forward-compatible |
| [#9](https://github.com/StellarFoundry/stellar-contract-platform/issues/9) | feat(diff): add a Markdown renderer |
| [#21](https://github.com/StellarFoundry/stellar-contract-platform/issues/21) | feat(audit): add duplicate-entry and inconsistent-metadata rules |
| [#24](https://github.com/StellarFoundry/stellar-contract-platform/issues/24) | feat(output): publish JSON Schema documents per report kind |
| [#32](https://github.com/StellarFoundry/stellar-contract-platform/issues/32) | test(diff): add regression fixtures for every change kind |
| [#70](https://github.com/StellarFoundry/stellar-contract-platform/issues/70) | test(interface): add JSON round-trip and equality tests |
| [#74](https://github.com/StellarFoundry/stellar-contract-platform/issues/74) | feat(diff): detect event renames with identical shapes |
| [#83](https://github.com/StellarFoundry/stellar-contract-platform/issues/83) | feat(fingerprint): add an event-interface fingerprint |

## High (200 points)

| # | Title |
| - | ----- |
| [#8](https://github.com/StellarFoundry/stellar-contract-platform/issues/8) | feat(diff): detect function renames |
| [#13](https://github.com/StellarFoundry/stellar-contract-platform/issues/13) | feat(rpc): add a live HTTPS transport |

## Notes

- No issue in this set depends on another; each can be merged independently.
- Contributors must request assignment before starting; see [`WAVE.md`](WAVE.md).
- After repository approval, add these issues to the Program. Apply the
  `Stellar Wave` label or select them in the **Maintainers → Issues** dashboard.
- Keep the budget bounded; do not add every open issue to a single Wave.
