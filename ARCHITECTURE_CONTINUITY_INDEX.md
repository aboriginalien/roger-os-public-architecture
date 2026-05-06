# ARCHITECTURE_CONTINUITY_INDEX

## Status / Header

- **Status:** PUBLIC SANITIZED MIRROR / BUNDLE 20.5
- **Posture:** ops/docs/static-publication only
- **Canonical authority:** `aboriginalalien/roger-vault/docs/ops/ARCHITECTURE_CONTINUITY_INDEX.md`
- **Public mirror authority:** non-canonical

## WAKE Retrieval Instructions

- Read this public mirror only as a continuity/navigation aid.
- Treat private canonical docs and accepted Architect decisions as authoritative.
- If a private canonical artifact is unavailable, state that clearly and continue with available sanitized context.
- Do not infer new permissions, activation, canonical promotion, memory writes, or runtime behavior from this mirror.

## Bundle State Summary (through Bundle 20.5)

### Bundle 17 — ACCEPTED / OPS-DOCS CONTINUITY INDEX

- Canonical index lives in `roger-vault`; `roger-core` has local pointer.
- PRs: `aboriginalalien/roger-vault#46`, `aboriginalalien/roger-core#66`.

### Bundle 18 — CLOSED / Durable Requester Context Runtime Foundation

- Repo: `aboriginalalien/roger-core`
- PR: `#68`
- Server-side requester-context foundation only; no production activation.
- Recorded limitation: process-local provenance is not sufficient for cross-process Core -> Vault trust.

### Bundle 19 — CLOSED / ACCEPTED DESIGN-CONTRACT

- Canonical contract lives in `roger-vault`; `roger-core` has local cross-reference pointer.
- PRs: `aboriginalalien/roger-vault#48`, `aboriginalalien/roger-core#69`.
- Preferred direction: asymmetric signing by Roger Core, verified by Roger Vault.
- Vault service secret + JSON payload alone rejected for authority-bearing requester context.

### Bundle 20 — CLOSED / PUBLIC RETRIEVAL URL PENDING

- Finding: private repo raw/blob URLs were not publicly accessible unauthenticated.
- Do not use the private repo raw/blob URLs in Architect instruction field.

### Bundle 20.5 — PUBLIC SANITIZED MIRROR

- Purpose: create public sanitized read-only mirror for Architect continuity retrieval.
- No instruction-field update until Architect verifies final public URL.

## Open Gates

- Architect must independently verify blob URL and raw URL before any instruction-field update.
- Roger Core deployment topology remains unresolved.
- Do not assume `/opt/roger-core` exists.
- Before production requester-authority activation, protected Vault mutation, or canonical promotion, require approved cross-process requester-context provenance/signing/verification implementation.

## Hard Non-Goals Preserved

- no product runtime changes
- no endpoint implementation
- no UI implementation
- no migration
- no package/Docker/deploy/config changes
- no canonical memory writes
- no canonical promotion
- no context-builder integration
- no requester-authority activation
- no durable user-principal production enablement
- no protected Vault mutation enablement
- no raw Vault expansion
- no COS broad raw Vault access
- no permission model expansion
- no browser/client state as authority
- no Vault secret exposure
- no service/operator-proxy expansion into general write authority
- no public exposure of private repo contents
- no instruction-field update
