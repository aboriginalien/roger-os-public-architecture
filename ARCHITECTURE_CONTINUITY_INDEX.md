# ARCHITECTURE_CONTINUITY_INDEX

## Status / Header

- **Status:** PUBLIC SANITIZED MIRROR / BUNDLE 37 CLOSEOUT
- **Posture:** ops/docs/static-publication only
- **Canonical authority:** `aboriginalalien/roger-vault/docs/ops/ARCHITECTURE_CONTINUITY_INDEX.md`
- **Public mirror authority:** non-canonical

## Top-of-File Verification

- **mirror_status:** current
- **latest_bundle:** Bundle 37
- **implementation_prs:** roger-core PR #93 / docs-only
- **mirror_pr:** TBD until this PR exists
- **mirror_merge_commit:** TBD until merged
- **last_updated_utc:** 2026-05-10T01:47:48Z
- **recommended_next_direction:** Next decision: choose whether Bundle 38 should implement Aura-1 TTS first, Flux STT/post-record replacement first, a smaller provider-config foundation, or pivot to Agent Dossier MVP before voice runtime implementation.

## WAKE Retrieval Instructions

- Read this public mirror only as a continuity/navigation aid.
- Treat private canonical docs and accepted Architect decisions as authoritative.
- If a private canonical artifact is unavailable, state that clearly and continue with available sanitized context.
- Do not infer new permissions, activation, canonical promotion, memory writes, or runtime behavior from this mirror.

## Bundle State Summary (through Bundle 37)

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


### Bundle 35 — CLOSED / V1 CAPTURE RELIABILITY POLISH

- Bundle 35 closed with V1 capture reliability polish status/failure-path hardening.
- V1 dependable baseline remains manual Start Recording -> Stop & Send.
- Stop & Send preserves the existing capture/send path.
- Separate Stop and Send controls remain available.
- Completed-capture duplicate re-submit behavior from separate Send was corrected.
- New Start Recording resets send availability for a new capture.
- Status and failure states were clarified for capture/send outcomes.
- Diagnostics are de-emphasized/collapsed but remain expandable and accessibly available.
- Selected-agent response rendering remains live.
- Speak Reply / Stop Speak remain available.
- Browser-native verbal send remains opportunistic only and is not dependable V1 baseline.
- Unsupported verbal-command state does not block manual capture.
- Observed watch item: selected-agent replies may blur “Roger” and “Chief of Staff” identity language; treat as future Architect-reviewed identity/prompt alignment concern, not Bundle 35 UI fix.
- Observed watch item: recent flow may answer using prior captures/messages in current context; record only as recent-context behavior, not canonical memory.
- No backend/Vault/schema/package/env/config/requester-authority/memory-authority/agent-identity/audio-pipeline expansion occurred.


### Bundle 36 — CLOSED / V1 IDENTITY BOUNDARY ALIGNMENT

- Roger Intercom remains shell/interface/capture/router, not an agent.
- Chief of Staff remains selected/default user-facing agent.
- `/capture` response copy and model-facing instruction wording were corrected to preserve identity boundary.
- `roger-core` PR #91 and PR #92 were merged, deployed, and production-verified.
- Identity prompt tests passed with boundary-respecting behavior for “Are you Roger or Chief of Staff?” and “Is Roger different from Chief of Staff?”.
- Existing capture/send path and selected-agent routing were preserved.
- Start Recording -> Stop & Send, separate Stop then Send, and completed-capture no-resubmit guard were preserved.
- Speak Reply / Stop Speak and diagnostics accessibility were preserved without implying Roger Intercom is an agent.
- Unsupported browser-native verbal command state does not block manual capture.
- No backend/API/schema/Vault/package/env/config/deploy/requester-authority/memory-authority/agent-identity/audio-pipeline expansion observed.
- Observed watch item: after a fresh deploy/browser refresh, the first response may not auto-speak until Speak Reply is tapped; subsequent responses auto-speak normally. This is non-blocking and tracked as a watch item only.



### Bundle 37 — CLOSED / V1 VOICE PROVIDER LAYER PLANNING

- Bundle 37 was docs-only planning/discovery.
- Delivered docs in `roger-core`:
  - `docs/VOICE_PROVIDER_LAYER_BUNDLE_37_PLAN.md`
  - `docs/OBSERVED_CODE_MAP_BUNDLE_37_VOICE_PROVIDER_PLANNING.md`
- Current `/capture` remains browser `MediaRecorder` capture.
- Current loop remains Start Recording -> Stop & Send.
- Current STT remains post-recording through existing server-side OpenAI transcription path.
- Selected-agent routing begins after transcription.
- Current TTS remains browser/client `speechSynthesis` with Speak Reply / Stop Speak and auto-speak behavior.
- Browser-native verbal command support remains opportunistic only.
- Roger Intercom remains shell/capture/navigation surface.
- Chief of Staff or selected agent remains responder.
- Proposed future adapter posture includes `VoiceProviderConfig`, STT adapter boundary, TTS adapter boundary, server-side secret handling, provider/model/voice swapping later.
- Default candidates documented:
  - STT: Deepgram Flux
  - TTS: Deepgram Aura-1
- Boundary confirmations:
  - No runtime Deepgram calls added.
  - No provider keys added.
  - No package/env/config changes added.
  - No backend/API/schema/Vault/requester-authority/memory-authority/agent-identity changes added.
  - No new audio pipeline added.
  - No always-listening or hidden recording behavior added.
  - No Intercom-as-agent behavior added.
  - No selected-agent routing redesign added.
- Architect caveat: Architect could not independently fetch the raw GitHub doc paths during review; preserve exact doc paths for later verification. This is not a closeout blocker.

## Recommended Next Direction

### Bundle 38 Decision Gate — Voice Provider Sequencing vs Agent Dossier MVP

- Choose the next scoped direction explicitly; do not treat voice runtime implementation as pre-approved.
- Candidate paths: Aura-1 TTS-first implementation, Flux STT/post-record replacement-first implementation, a smaller `VoiceProviderConfig` foundation slice, or a pivot to Agent Dossier MVP before voice runtime changes.
- Preserve current boundary behavior and docs-only/non-canonical posture until an Architect-approved implementation bundle is selected.

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
