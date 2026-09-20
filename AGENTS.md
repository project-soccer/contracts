# Contracts Repository Instructions

- Write all project documentation in English. Conversation with the founder may remain in Italian.
- This repository owns NFT/escrow contracts, financial verification, versioned interfaces, and future deployment tooling. Gameplay remains off-chain.
- Cross-project decisions are in `docs/adr/README.md` in `project-soccer/game` (locally `../game/docs/adr/README.md`). Current specifications are under `game/docs/specifications/`; the old design review is archived.
- Preserve the distinction between confirmed requirements and proposals. NFT price versus competitive strength, chain, wallet model, fees, and dispute rules remain open.
- Treat the supplied LLM contract examples as review material, not production-ready contracts or authorization to deploy.
- When implementation is authorized, verify fund conservation, authorization, duplicate submissions, timeouts, disputes, and recovery with relevant tests. Do not imply that tests constitute an audit.
- Planning does not authorize deployment, handling real funds, publishing, or license selection. Never commit signing keys, credentials, personal information, or private source attachments.
