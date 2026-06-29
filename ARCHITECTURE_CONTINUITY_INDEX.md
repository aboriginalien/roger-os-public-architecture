# Roger OS Public Architecture Continuity Index

- **Status:** Public-safe continuity index source maintained in private `aboriginalien/roger-core`.
- **Published target:** `aboriginalien/roger-os-public-architecture/main/ARCHITECTURE_CONTINUITY_INDEX.md`
- **Stable Lead Build review URL:** https://raw.githubusercontent.com/aboriginalien/roger-os-public-architecture/main/ARCHITECTURE_CONTINUITY_INDEX.md
- **Source file:** `docs/ops/public/ARCHITECTURE_CONTINUITY_INDEX_SOURCE.md`
- **Last updated:** 2026-06-29 00:00 UTC

This public index is a sanitized review/navigation surface. It does not replace private repository reality, GitHub checks, deploy verification, Lead Build judgment, Architect acceptance, merge approval, or ADR-008 observed-code reconciliation.

## Current Build Status

- **Current active roger-core PR:** PR #208 — ADR-013: Add controlled public Architecture Continuity Index publishing.
- **Current readiness state:** `merged` based on Operator-provided post-merge/publication evidence for PR #208.
- **Controlled publish mechanism:** `installed` — the manual GitHub Actions workflow `Publish Architecture Continuity Index` and fail-closed publish script exist in `roger-core`.
- **Publication state:** `verified/successful` — Operator reported the workflow ran successfully and updated the public raw Architecture Continuity Index after PR #208.
- **Runtime behavior changed:** no. This is docs/workflow/script-only publishing support and changes no runtime/provider/model/Vault/memory/routing/writeback/tool/agent-identity behavior.

## Active PR Review Board

### PR #208 — ADR-013: Add controlled public Architecture Continuity Index publishing

- **PR number:** `#208`
- **PR title:** `ADR-013: Add controlled public Architecture Continuity Index publishing`
- **PR URL:** https://github.com/aboriginalien/roger-core/pull/208
- **Branch:** `work`
- **Status:** `merged` — Operator reported PR #208 is the implementation path after successful workflow publication.
- **Changed files list:**
  - `.github/workflows/publish-architecture-continuity-index.yml` — manual controlled public-index publish workflow.
  - `scripts/publish_architecture_continuity_index.sh` — fail-closed source-to-public-repo publish script.
  - `docs/ops/public/ARCHITECTURE_CONTINUITY_INDEX_SOURCE.md` — public-safe source for the Architecture Continuity Index.
  - `docs/setup/PUBLIC_ARCHITECTURE_PUBLISHING.md` — setup note for the repository secret name and workflow.
  - `docs/adr/ADR-013_codex_pr_evidence_packet_and_active_build_evidence_handoff.md` — ADR-013 operational rule for public index publication.
  - `docs/templates/CODEX_PR_EVIDENCE_PACKET_TEMPLATE.md` — Lead Build Review Surface template additions for public index state.
  - `docs/templates/ACTIVE_BUILD_EVIDENCE_HANDOFF_TEMPLATE.md` — handoff template additions for public index state.
  - `docs/ops/codex/CODEX_CONTINUITY_WORKFLOW.md` — workflow rule requiring source/public-index updates.
  - `docs/ops/ACTIVE_PR_EVIDENCE_INDEX.md` — private active evidence entry updated for PR #208 state.
  - `docs/ops/ARCHITECTURE_CONTINUITY_INDEX.md` — public pointer corrected to the public raw URL and private source path.
- **Checks/status:** `passing` — Operator reported the publish workflow completed successfully; local static checks for this evidence refresh passed.
- **Conflicts state:** `none` — no conflicts reported for merged PR #208.
- **Preview/deploy/live verification status where applicable:** `not applicable` for docs/workflow-only patch; public raw publication is the external verification.
- **Publication state:** `verified/successful` — the controlled publish workflow updated the public raw Architecture Continuity Index after PR #208.
- **Codex/GitHub review comments summary:** `none material reported` for this publication-state evidence refresh.
- **Unresolved/resolved review-comment state:** `none material reported`; PR #208 is no longer blocked on publication.
- **Material findings:** none for the docs/workflow/script-only publication path.
- **Patches applied after review comments:** this evidence refresh records post-PR #208 publication reality; it does not change runtime behavior.
- **ADR-008 obligation/status:** `not required` for this docs/workflow/script-only controlled-publication patch; no runtime, storage, provider, model, memory, Vault, routing, writeback, tool, or agent-identity behavior changed.
- **Runtime/storage/provider/model/memory/Vault/routing/writeback/tool/agent-identity impact statement:** no behavior change; the controlled public index mechanism and this evidence update are documentation/workflow/script-only.
- **Forbidden-evidence confirmation:** no credentials, PATs, deploy keys, tokens, env values, provider payloads, hidden prompts, raw Operator prompts, raw Codex task prompts, prompt chains/logs, Vault data, requester-private records, raw audio, or secret-bearing screenshots are included.
- **Remaining gaps:** none for the ADR-013 public index publication path; continue using repo/check/deploy/publication reality as stronger evidence than this index text.
- **Exact Lead Build request:** Lead Build: treat PR #208 as the merged implementation path for ADR-013 controlled public Architecture Continuity Index publishing, with publication verified successful and no runtime/provider/model/Vault/memory/routing/writeback/tool/agent-identity impact.
- **Exact Operator request, if any:** none.
- **Last updated timestamp:** 2026-06-29 00:00 UTC

### PR #207 — ADR-013 operational correction: roger-core publishes public Architecture Continuity Index

- **PR number:** `#207`
- **PR title:** `ADR-013 operational correction — roger-core publishes public Architecture Continuity Index`
- **PR URL:** https://github.com/aboriginalien/roger-core/pull/207
- **Status:** `superseded/closed/not active` — PR #208 is the active merged implementation path for controlled public Architecture Continuity Index publishing.
- **Publication state:** superseded by PR #208 verified/successful publication.
- **Runtime/storage/provider/model/memory/Vault/routing/writeback/tool/agent-identity impact statement:** none; PR #207 is not the active implementation path.
- **Forbidden-evidence confirmation:** no credentials, PATs, deploy keys, tokens, env values, provider payloads, hidden prompts, raw Operator prompts, raw Codex task prompts, prompt chains/logs, Vault data, requester-private records, raw audio, or secret-bearing screenshots are included.
- **Last updated timestamp:** 2026-06-29 00:00 UTC

## PR Timing / Readiness States

- `PR created, waiting for checks`
- `waiting for preview/deploy`
- `waiting for Codex/GitHub review`
- `needs Codex patch`
- `patched, waiting for recheck`
- `ready for Lead Build review`
- `needs Operator input`
- `needs Architect review`
- `ready to merge after Lead Build`
- `merged`
- `closed`

**Timing rule:** PR creation is not Lead Build review readiness. Lead Build review readiness is not merge readiness.

## Latest PR Evidence Entry

PR #208 is the latest public-safe evidence entry. Its current state is `merged`; checks are recorded as passing, conflicts as none, and public Architecture Continuity Index publication as verified/successful based on Operator-reported workflow success. PR #207 is superseded/closed/not the active implementation path.

## Sprint / ADR Status

- **ADR-013:** accepted; this patch is an operational correction to the accepted ADR-013 and does not create ADR-014.
- **Sprint 15 voice:** not restarted or changed by this docs/workflow patch.
- **ADR-008:** remains required for meaningful architecture/runtime/storage/authority/provider/memory changes and is not replaced by this public index.

## Durable Architecture Continuity

- `aboriginalien/roger-core` remains the private core/runtime/build repository and primary Codex task repo.
- `aboriginalien/roger-os-public-architecture` is the public architecture/continuity surface for the sanitized Architecture Continuity Index.
- `aboriginalien/roger-vault` remains private Vault-specific work only; access does not imply broader authority, memory access, requester-private access, or permission expansion.

## Accepted ADR Index

- **ADR-008:** observed-code reconciliation remains the stronger code-reality mechanism where required.
- **ADR-009:** internal AI workers remain non-authority harness helpers unless separately approved.
- **ADR-010:** largest-safe-bundle doctrine remains bounded by stop gates and review requirements.
- **ADR-011:** anti-ghost-build posture remains in force; evidence must describe real repo/deploy state.
- **ADR-012:** model/provider identity separation remains unchanged.
- **ADR-013:** PR Evidence Packet, Active Build Evidence Handoff, Lead Build Review Surface, private active evidence index, and public-safe Architecture Continuity Index source/publish workflow are evidence/navigation artifacts only.

## Historical Bundle / Sprint Log

- Sprint 13: Gemini Provider Parity Catch-Up and Safe Activation Readiness closed.
- Sprint 14: ADR-013 Codex PR Evidence Packet and Active Build Evidence Handoff closed; ADR-013 accepted.
- Sprint 15A: Gemini Runtime Eligibility Parity closed.
- Current correction: ADR-013 operational correction has an installed and verified/successful controlled public Architecture Continuity Index publication path after PR #208, without changing runtime/provider/model/Vault/memory/routing/writeback/tool/agent-identity behavior.
