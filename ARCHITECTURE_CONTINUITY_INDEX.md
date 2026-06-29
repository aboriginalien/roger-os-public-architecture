# Roger OS Public Architecture Continuity Index

- **Status:** Public-safe continuity index source maintained in private `aboriginalien/roger-core`.
- **Published target:** `aboriginalien/roger-os-public-architecture/main/ARCHITECTURE_CONTINUITY_INDEX.md`
- **Stable Lead Build review URL:** https://raw.githubusercontent.com/aboriginalien/roger-os-public-architecture/main/ARCHITECTURE_CONTINUITY_INDEX.md
- **Source file:** `docs/ops/public/ARCHITECTURE_CONTINUITY_INDEX_SOURCE.md`
- **Last updated:** 2026-06-29 00:00 UTC

This public index is a sanitized review/navigation surface. It does not replace private repository reality, GitHub checks, deploy verification, Lead Build judgment, Architect acceptance, merge approval, or ADR-008 observed-code reconciliation.

## Current Build Status

- **Current active roger-core PR:** PR #210 — Automate Architecture Continuity Index publishing.
- **Current readiness state:** `patched, waiting for checks/review` before merge; merge-safe publication text below records the intended post-merge public state.
- **PR #209 state:** `merged` into `main` as merge commit `bc98f52` (`Merge pull request #209 from aboriginalien/codex/patch-public-architecture-continuity-index`).
- **Controlled publish mechanism:** `installed/patched` — the GitHub Actions workflow `Publish Architecture Continuity Index` and fail-closed publish script exist in `roger-core`; PR #210 reconciles ADR-013 to permit automatic publish-on-main for the public-safe continuity source and ADR-013 publication support files.
- **Observed publication gap:** `not operationally fixed until PR #210 merges and automatic publication is verified` — Lead Build can open the public raw Architecture Continuity Index, but the public raw URL was observed stale rather than the active ADR-013 PR review board state.
- **Required correction state:** `patched in PR #210` — normal publication is automatic after relevant `main` updates; `workflow_dispatch` remains only as emergency/manual fallback.
- **Runtime behavior changed:** no. This is docs/workflow/public-index-source-only publishing automation and changes no runtime/provider/model/Vault/memory/routing/writeback/tool/agent-identity behavior.

## Merge-Safe Post-Merge Publication State

When PR #210 is merged to `main`, this source file is intended to publish automatically to the public raw Architecture Continuity Index and should be read as the post-merge state below:

- **PR #210 post-merge state:** `merged` once this content is published from `main` by the automatic workflow.
- **Automatic trigger:** `enabled` for pushes to `main` that change `docs/ops/public/ARCHITECTURE_CONTINUITY_INDEX_SOURCE.md`, `.github/workflows/publish-architecture-continuity-index.yml`, `scripts/publish_architecture_continuity_index.sh`, or `docs/setup/PUBLIC_ARCHITECTURE_PUBLISHING.md`.
- **Manual fallback:** `workflow_dispatch` remains available only as emergency/manual fallback.
- **Publication verification:** `pending until automatic workflow run after merge is observed`; do not claim ADR-013 operationally fixed until that run and public raw freshness are verified.

## Active PR Review Board

### PR #210 — Automate Architecture Continuity Index publishing

- **PR number:** `#210`
- **PR title:** `Automate Architecture Continuity Index publishing`
- **Branch:** `work`
- **Status before merge:** `patched, waiting for checks/review`.
- **Status after merge/publication:** `merged` once published from `main` by the automatic workflow; this source is merge-safe and must not be interpreted as leaving PR #210 open after merge.
- **Purpose:** reconcile ADR-013 with automatic publish-on-main and add automatic publication on relevant pushes to `main` while retaining `workflow_dispatch` only as emergency/manual fallback.
- **Changed files list:**
  - `.github/workflows/publish-architecture-continuity-index.yml` — adds automatic `push` trigger for relevant `main` updates while retaining manual fallback.
  - `docs/adr/ADR-013_codex_pr_evidence_packet_and_active_build_evidence_handoff.md` — explicitly permits controlled automatic publish-on-main and requires merge-safe public source content.
  - `docs/setup/PUBLIC_ARCHITECTURE_PUBLISHING.md` — updates setup language from manual-only to automatic-on-main with fallback dispatch.
  - `docs/ops/public/ARCHITECTURE_CONTINUITY_INDEX_SOURCE.md` — records current public-safe active review board state, merge-safe post-merge state, and the observed stale-public-index gap.
- **Checks/status:** `pending GitHub checks`; local docs/workflow checks passed for this patch.
- **Conflicts state:** `none known locally`.
- **Preview/deploy/live verification status where applicable:** public raw update must be verified after this branch lands on `main` and the automatic publish workflow runs.
- **Publication state:** `pending automatic workflow after merge to main`; not reported as operationally fixed yet.
- **Codex/GitHub review comments summary:** material findings addressed by reconciling ADR-013 with automatic publication and making this public source merge-safe.
- **Unresolved/resolved review-comment state:** `resolved by patch pending reviewer confirmation`.
- **Material findings:** public raw index remained stale after PR #209; manual-only publication is insufficient for ADR-013; ADR-013 needed explicit automatic-publish permission; source needed merge-safe post-merge wording.
- **Patches applied after review comments:** ADR-013 operating rule updated; public index source rewritten with merge-safe PR #210 post-merge state.
- **ADR-008 obligation/status:** `not required` for this docs/workflow/public-index-source-only publication automation patch; no runtime, storage, provider, model, memory, Vault, routing, writeback, tool, or agent-identity behavior changed.
- **Runtime/storage/provider/model/memory/Vault/routing/writeback/tool/agent-identity impact statement:** no behavior change; this correction only changes publication workflow triggering, ADR-013 docs, setup docs, and public-safe documentation state.
- **Forbidden-evidence confirmation:** no credentials, PATs, deploy keys, tokens, env values, provider payloads, hidden prompts, raw Operator prompts, raw Codex task prompts, prompt chains/logs, Vault data, requester-private records, raw audio, or secret-bearing screenshots are included.
- **Remaining gaps:** confirm GitHub checks, conflicts, automatic publish workflow success, and public raw URL freshness after merge to `main`.
- **Exact Lead Build request:** Lead Build: review patched PR #210; do not merge until checks/review are acceptable, then verify the automatic publish workflow and public raw URL after merge before treating ADR-013 publication operationally fixed.
- **Exact Operator request, if any:** do not merge PR #210 yet; patch the same PR; reconcile ADR-013 before automatic push publishing; make the public index merge-safe; do not create a new ADR; keep this docs/workflow/public-index-source only; do not expose forbidden evidence.
- **Last updated timestamp:** 2026-06-29 00:00 UTC

### PR #209 — Update ADR-013 public index publication evidence

- **PR number:** `#209`
- **PR title:** `Update ADR-013 public index publication evidence`
- **Branch:** `codex/patch-public-architecture-continuity-index`
- **Status:** `merged` into `main` as merge commit `bc98f52`.
- **Publication state:** not sufficient; public raw index was observed stale after PR #209.
- **Runtime/storage/provider/model/memory/Vault/routing/writeback/tool/agent-identity impact statement:** none.
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
