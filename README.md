# Project Soccer — Contracts

Planned blockchain contracts and financial verification for [Project Soccer](https://github.com/project-soccer).

## Responsibility

Develop NFT ownership and escrow settlement under an agreed economic specification. Include financial invariant tests and, later, deployment tooling and versioned contract interface artifacts.

## Boundaries

Gameplay remains off-chain. The game service reports results; an escrow does not independently establish their fairness. Wallet integration and settlement operation belong to the application components, with separate signing controls.

The relationship between NFT price and competitive strength remains explicitly open. A proprietary token is not an approved requirement. Chain, wallet model, deposits, fees, disputes, and jurisdictional requirements need resolution before real-money release.

## Status

Planning only. The public [project-soccer/contracts](https://github.com/project-soccer/contracts) repository was created with the founder’s authorization on 2026-09-20. Git operations use SSH. No contract implementation, compilation, audit, or deployment has been performed. The supplied LLM contract examples are reviewed in the canonical document and must not be treated as production-ready.

Licensing is undecided. See `docs/adr/README.md` and `docs/open-questions.md` in `project-soccer/game`. All documentation must be written in English.
