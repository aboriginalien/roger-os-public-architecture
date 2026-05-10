# ARCHITECTURE_CONTINUITY_INDEX

## Status / Header

- **Status:** PUBLIC SANITIZED MIRROR / BUNDLE 44 CLOSEOUT
- **Posture:** ops/docs/static-publication only
- **Canonical authority:** `aboriginalalien/roger-vault/docs/ops/ARCHITECTURE_CONTINUITY_INDEX.md`
- **Public mirror authority:** non-canonical

## Top-of-File Verification

- **mirror_status:** current
- **latest_bundle:** Bundle 44
- **implementation_prs:** roger-core PR #103
- **mirror_pr:** TBD until this PR exists
- **mirror_merge_commit:** TBD until merged
- **last_updated_utc:** 2026-05-10T14:32:29Z
- **recommended_next_direction:** Next decision should be Architect/Operator review of post-Bundle-44 direction; do not infer approval for Agent Creator activation, runtime dossier editing, custom-agent creation UI, workspace/mission-room buildout, Laboratory activation, voice-provider runtime implementation, or memory/Vault/requester/tool authority expansion.

## WAKE Retrieval Instructions

- Read this public mirror only as a continuity/navigation aid.
- Treat private canonical docs and accepted Architect decisions as authoritative.
- If a private canonical artifact is unavailable, state that clearly and continue with available sanitized context.
- Do not infer new permissions, activation, canonical promotion, memory writes, or runtime behavior from this mirror.

## Bundle State Summary (through Bundle 44)

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



### Bundle 38 — CLOSED / V1 AGENT DOSSIER MVP

- Static/config-backed Agent Dossier MVP created in `roger-core`.
- Chief of Staff mapped into seven-layer dossier structure.
- Chief of Staff remains slug `chief_of_staff` and default selected user-facing agent.
- Roger Intercom remains shell/capture/navigation, not an agent and not dossiered as an agent.
- Candidate dossier/example remains inactive and not selectable.
- Dossiers describe intended profile/scope only; they do not grant permissions.
- No Vault access expansion.
- No canonical memory promotion behavior.
- No hidden memory writes.
- No requester-authority activation.
- No tool/action expansion.
- No runtime dossier editor.
- No full custom-agent UI.
- No Laboratory activation.
- No workspace/mission-room buildout.
- No voice-provider runtime implementation.
- `/capture` smoke after deploy remained good: selected agent visible, Start Recording -> Stop & Send works, response renders, Speak Reply / Stop Speak work, no visible Intercom-as-agent regression.

### Bundle 39 — CLOSED / AGENT DOSSIER READ SURFACE + CANDIDATE AGENT REVIEW FOUNDATION

- Read-only `/agents` dossier review surface added in `roger-core`.
- Chief of Staff remains the only active/default selected user-facing agent.
- `chief_of_staff` slug preserved.
- Candidate/example dossier remains inactive and not selectable.
- Public-safe/redacted dossier fields only.
- Dossiers describe intended profile/scope and do not grant permissions.
- Roger Intercom remains shell/capture/navigation, not an agent.
- Selected-agent routing and `/capture` behavior preserved.
- Start Recording -> Stop & Send smoke-verified after deploy.
- Selected-agent response rendering preserved.
- Speak Reply / Stop Speak preserved.
- No runtime dossier editing.
- No candidate activation.
- No new active agents.
- No Vault/memory/requester/tool/write authority expansion.
- No backend/API/schema/package/env/config/deploy changes.
- No workspace/mission-room, Laboratory, or voice-provider runtime implementation.


### Bundle 40 — CLOSED / CANDIDATE DOSSIER REVIEW MECHANICS, NO ACTIVATION

- Candidate review states added as static/config-backed governance metadata.
- `/agents` displays candidate review posture in read-only/public-safe form.
- Candidate remains inactive and not selectable.
- Review status does not grant runtime authority.
- Chief of Staff remains active/default selected user-facing agent.
- Roger Intercom remains shell/interface/capture/navigation, not an agent.
- Selected-agent routing and `/capture` behavior preserved.
- No edit/create/approve/reject/activate controls.
- No runtime dossier editing.
- No candidate activation.
- No custom-agent creation UI.
- No memory/Vault/requester/tool/write authority expansion.
- No backend/API/schema/package/env/config/deploy changes.
- No workspace/mission-room, Laboratory, or voice-provider runtime implementation.

### Bundle 41 — CLOSED / AGENT DOSSIER CANDIDATE READINESS WORKSTREAM, NO ACTIVATION

- Bundle 41 implemented candidate readiness metadata/workstream posture in `roger-core`.
- Implementation PRs: `roger-core` PR #97, #98, #99.
- Candidate readiness metadata remains static/config-backed.
- `/agents` shows public-safe candidate readiness metadata.
- Candidate remains inactive and not selectable.
- Chief of Staff remains the only active/default selected user-facing agent.
- `chief_of_staff` slug remains preserved.
- Roger Intercom remains shell/interface/capture/navigation, not an agent.
- Selected-agent routing and `/capture` behavior remain preserved.
- `accepted_for_future_activation` exists only as a type/documented future governed outcome and was not assigned to any candidate.
- ADR-008 observed-code reconciliation was produced.
- Boundary confirmations:
  - No runtime dossier editing.
  - No candidate activation.
  - No custom-agent creation UI.
  - No new active agents.
  - No selected-agent routing change.
  - No requester-authority change.
  - No memory-authority change.
  - No Vault access change.
  - No canonical memory promotion behavior.
  - No hidden memory writes.
  - No tool/action expansion.
  - No workspace/mission-room buildout.
  - No Laboratory activation.
  - No voice-provider runtime implementation.
  - No Deepgram runtime calls.
  - No backend/API/schema/package/env/config/deploy changes.

## Recommended Next Direction

- Post-Bundle-41 direction requires explicit Architect/Operator review before selecting any next implementation bundle.
- Do not imply approval for runtime dossier editing, candidate activation, custom-agent creation UI, workspace/mission-room buildout, Laboratory activation, or voice-provider runtime implementation without a newly accepted bundle decision.
- Preserve current boundary behavior and public sanitized docs-only/non-canonical posture until that decision is made.

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


### Bundle 42 — CLOSED / CANDIDATE ACTIVATION CONTRACT, PLANNING/DISCOVERY ONLY

- Bundle 42 closeout is docs-only planning/discovery in `roger-core`.
- Implementation PR: `roger-core` PR #100 (docs-only).
- Delivered docs in `roger-core`:
  - `docs/CANDIDATE_ACTIVATION_CONTRACT_BUNDLE_42.md`
  - `docs/OBSERVED_CODE_MAP_BUNDLE_42_CANDIDATE_ACTIVATION_CONTRACT.md`
- Candidate Activation Contract is defined as planning/discovery only.
- Activation is documented as a governed future architecture event, not a UI toggle, dossier status change alone, config-only change, readiness label, prompt copy change, automatic selection, or automatic permission/memory/Vault/tool grant.
- Eligibility gates and approval requirements are documented.
- Distinctions are preserved between readiness label, review status, `accepted_for_future_activation`, active production profile, selected/active runtime agent, and permissioned authority.
- Dossiers may describe intended scope/role/tools/memory posture, but enforcement remains outside the dossier.
- ADR-008-style observed-code/planning reconciliation was produced.
- No runtime/source behavior changed.
- Boundary confirmations:
  - No candidate activation.
  - No runtime dossier editing.
  - No custom-agent creation UI.
  - No new active agents.
  - No selected-agent routing changes.
  - No requester-authority changes.
  - No memory-authority changes.
  - No Vault access changes.
  - No canonical memory promotion.
  - No hidden memory writes.
  - No tool/action expansion.
  - No workspace/mission-room buildout.
  - No Laboratory activation.
  - No voice-provider runtime implementation.
  - No Deepgram runtime calls.
  - No backend/API/schema/package/env/config/deploy changes.
  - No assignment of `accepted_for_future_activation` to any candidate.


### Bundle 43 — CLOSED / AGENT CREATOR SOURCE INTAKE + ADAPTATION MAP, NO ACTIVATION

- Agent Creator source intake/adaptation map completed.
- Corrective docs-only boundary/provenance patch applied.
- Agent Creator remains source material only.
- No Agent Creator activation.
- No formal Agent Creator candidate dossier.
- No runtime dossier editing.
- No custom-agent creation UI.
- No workspace/mission-room buildout.
- No Laboratory activation.
- No voice-provider runtime implementation.
- No memory/Vault/requester/tool authority expansion.
- Codex used Operator-provided Agent Creator source export/context, not direct raw Agent Creator attachment ingestion.

### Bundle 44 — CLOSED / AGENT CREATOR STATIC CANDIDATE DOSSIER, NO ACTIVATION

- Agent Creator static candidate dossier added in `roger-core`.
- implementation_prs: roger-core PR #103.
- candidate slug: `agent_creator`.
- candidate status: inactive / not selectable.
- review state: proposed.
- readiness label: needs_source_refs.
- `accepted_for_future_activation` was not assigned.
- Agent Creator remains candidate/source-derived review material only.
- Chief of Staff remains the only active/default selected user-facing agent.
- No Agent Creator activation.
- No selected-agent routing changes.
- No runtime dossier editing.
- No custom-agent creation UI.
- No workspace/mission-room buildout.
- No Laboratory activation.
- No voice-provider runtime implementation.
- No memory/Vault/requester/tool authority expansion.
- Provenance posture: Bundle 44 used accepted Bundle 43 public-safe source intake/adaptation material; Bundle 43 used Operator-provided Agent Creator source export/context, not direct raw Agent Creator attachment ingestion by Codex.
- Direct raw-source review remains a provenance gap before any readiness upgrade.

