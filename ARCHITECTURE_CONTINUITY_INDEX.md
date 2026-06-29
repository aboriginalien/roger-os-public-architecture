# Roger OS Public Architecture Continuity Index

- **Status:** Public-safe continuity index source maintained in private `aboriginalien/roger-core`.
- **Published target:** `aboriginalien/roger-os-public-architecture/main/ARCHITECTURE_CONTINUITY_INDEX.md`
- **Stable Lead Build review URL:** https://raw.githubusercontent.com/aboriginalien/roger-os-public-architecture/main/ARCHITECTURE_CONTINUITY_INDEX.md
- **Source file:** `docs/ops/public/ARCHITECTURE_CONTINUITY_INDEX_SOURCE.md`
- **Last updated:** 2026-06-29 00:00 UTC

This public index is a sanitized review/navigation surface. It does not replace private repository reality, GitHub checks, deploy verification, Lead Build judgment, Architect acceptance, merge approval, or ADR-008 observed-code reconciliation.

## Current Build Status

- **Current active roger-core PR:** PR #207 — ADR-013 operational correction: public Architecture Continuity Index publishing.
- **Current readiness state:** `needs Operator input` until PR #207 checks, conflicts, Codex/GitHub review comments, and public publication state are known.
- **Publication state:** source file and controlled publishing mechanism are prepared in `roger-core`; public publication requires the `ROGER_PUBLIC_ARCHITECTURE_PUBLISH_TOKEN` repository secret.
- **Runtime behavior changed:** no. This is docs/workflow/script-only publishing support.

## Active PR Review Board

### PR #207 — ADR-013 operational correction: roger-core publishes public Architecture Continuity Index

- **PR number:** `#207`
- **PR title:** `ADR-013 operational correction — roger-core publishes public Architecture Continuity Index`
- **PR URL:** https://github.com/aboriginalien/roger-core/pull/207
- **Branch:** `work`
- **Readiness state:** `needs Operator input`
- **Changed files list:**
  - `.github/workflows/publish-architecture-continuity-index.yml` — manual controlled publish workflow.
  - `scripts/publish_architecture_continuity_index.sh` — fail-closed source-to-public-repo publish script.
  - `docs/ops/public/ARCHITECTURE_CONTINUITY_INDEX_SOURCE.md` — public-safe source for the Architecture Continuity Index.
  - `docs/setup/PUBLIC_ARCHITECTURE_PUBLISHING.md` — setup note for the required repository secret name.
  - `docs/adr/ADR-013_codex_pr_evidence_packet_and_active_build_evidence_handoff.md` — operational correction for public index publication.
  - `docs/templates/CODEX_PR_EVIDENCE_PACKET_TEMPLATE.md` — Lead Build Review Surface template additions for public index state.
  - `docs/templates/ACTIVE_BUILD_EVIDENCE_HANDOFF_TEMPLATE.md` — handoff template additions for public index state.
  - `docs/ops/codex/CODEX_CONTINUITY_WORKFLOW.md` — workflow rule requiring source/public-index updates.
  - `docs/ops/ACTIVE_PR_EVIDENCE_INDEX.md` — private active evidence entry updated for PR #207.
  - `docs/ops/ARCHITECTURE_CONTINUITY_INDEX.md` — stale public pointer corrected to the public raw URL and private source path.
- **Checks/status:** `unknown` — local static checks pending in this patch; GitHub checks unavailable in this environment.
- **Conflicts state:** `unknown` — PR #207 conflict state could not be verified because this environment has no configured `origin` remote and no GitHub CLI.
- **Preview/deploy/live verification status where applicable:** `not applicable` for docs/workflow-only patch; public raw publication is the required external verification.
- **Codex/GitHub review comments summary:** `unknown` — review comments unavailable in this environment.
- **Unresolved/resolved review-comment state:** `unknown` until GitHub review comments can be inspected.
- **Material findings:** PR #207 must not be marked ready for Lead Build review until checks, conflicts, review comments, and public publication state are known.
- **Patches applied after review comments:** none known in this environment.
- **ADR-008 obligation/status:** `not required` for this docs/workflow/script-only controlled-publication patch; no runtime, storage, provider, model, memory, Vault, routing, writeback, tool, or agent-identity behavior changed.
- **Runtime/storage/provider/model/memory/Vault/routing/writeback/tool/agent-identity impact statement:** no behavior change; the patch only adds documentation, a manual GitHub Actions workflow, and a controlled publish script for a sanitized Markdown index.
- **Forbidden-evidence confirmation:** no credentials, PATs, deploy keys, tokens, env values, provider payloads, hidden prompts, raw Operator prompts, raw Codex task prompts, prompt chains/logs, Vault data, requester-private records, raw audio, or secret-bearing screenshots are included.
- **Remaining gaps:** configure repository secret; run workflow or script with the secret; verify the public raw URL; update PR #207 body Lead Build Review Surface after publication; verify GitHub checks/conflicts/review comments.
- **Exact Lead Build request:** Lead Build: do not merge or mark PR #207 ready yet; first verify checks, conflicts, review comments, and public publication state, then review the PR body Lead Build Review Surface against changed files and this public index source.
- **Exact Operator request, if any:** Add the `ROGER_PUBLIC_ARCHITECTURE_PUBLISH_TOKEN` secret to `aboriginalien/roger-core` with least privilege to update `aboriginalien/roger-os-public-architecture`, then run the manual publish workflow if Codex cannot access the secret.
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

PR #207 is the latest public-safe evidence entry. Its current state is `needs Operator input` because publication and GitHub-side checks/conflicts/review comments are not yet verified.

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
- Current correction: ADR-013 operational correction adds a controlled public Architecture Continuity Index publication path without changing runtime/provider/model/Vault/memory/routing/writeback/tool/agent-identity behavior.
