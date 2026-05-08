# ARCHITECTURE_CONTINUITY_INDEX

## Status / Header

- **Status:** PUBLIC SANITIZED MIRROR / BUNDLE 34 CLOSEOUT
- **Posture:** ops/docs/static-publication only
- **Canonical authority:** `aboriginalalien/roger-vault/docs/ops/ARCHITECTURE_CONTINUITY_INDEX.md`
- **Public mirror authority:** non-canonical

## Top-of-File Verification

- **mirror_status:** current
- **latest_bundle:** Bundle 34
- **source_pr:** roger-core PR #88
- **merge_commit:** not available in this public sanitized mirror
- **last_updated_utc:** 2026-05-08T19:47:59Z

## WAKE Retrieval Instructions

- Read this public mirror only as a continuity/navigation aid.
- Treat private canonical docs and accepted Architect decisions as authoritative.
- If a private canonical artifact is unavailable, state that clearly and continue with available sanitized context.
- Do not infer new permissions, activation, canonical promotion, memory writes, or runtime behavior from this mirror.

## Bundle State Summary (through Bundle 34)

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

### Bundle 20.5 — CLOSED / PUBLIC SANITIZED MIRROR BOOTSTRAP

- Purpose: establish public sanitized read-only mirror for Architect continuity retrieval.
- This mirror remains non-canonical and retrieval-only.

### Bundle 33 — CLOSED / ARCHITECTURAL SUCCESS WITH IMPLEMENTATION LIMITATION

- Bundle 33 closed with implementation limitation.
- Browser-native `SpeechRecognition` / `webkitSpeechRecognition` is opportunistic only.
- It is not dependable V1 behavior.
- Safari/iPad live verification returned `service-not-allowed`.
- On tested Safari/iPad path, “Roger, send” and “Roger, stop” did not trigger stop/send.
- Manual Stop/Send remains dependable V1 baseline.
- Selected-agent response rendering remained live.
- Speak Reply / Stop Speak remained available.
- No backend/Vault/schema/package/env/config/requester-authority/memory/audio-pipeline expansion occurred.
- Observed-code reconciliation artifact pointer (public-safe): `docs/adr/ADR-008-observed-code-reconciliation.md` (if present in canonical/private context).

### Bundle 34 — CLOSED / V1 CAPTURE ERGONOMICS IMPROVEMENT

- Bundle 34 closed as capture ergonomics improvement.
- Bundle 33 remains closed with implementation limitation.
- V1 dependable baseline is manual Start Recording -> Stop & Send.
- Browser-native verbal send remains opportunistic only.
- Bundle 34 added a large mobile-friendly Stop & Send primary action during active recording.
- Stop & Send uses the existing capture/send path.
- Separate Stop and Send controls remain available as fallback/manual controls.
- Selected-agent response rendering remains live.
- Speak Reply / Stop Speak remain available.
- Safari/iPad unsupported verbal-command state does not block manual capture.
- No backend/Vault/schema/package/env/config/requester-authority/memory-authority/agent-identity/audio-pipeline expansion occurred.

## Recommended Next Direction

### Bundle 34 — V1 Capture Ergonomics: Reliable Push-to-Talk / Stop+Send Mobile Loop

- Prioritize dependable mobile capture ergonomics over opportunistic browser-native verbal send behavior.
- Preserve manual control as baseline while hardening capture loop reliability.

## Open Gates

- Architect should verify this public mirror raw URL for current continuity retrieval state.
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
