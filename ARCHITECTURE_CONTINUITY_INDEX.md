# Roger OS Public Architecture Continuity Index

- **Status:** Public-safe continuity index source maintained in private `aboriginalien/roger-core`.
- **Published target:** `aboriginalien/roger-os-public-architecture/main/ARCHITECTURE_CONTINUITY_INDEX.md`
- **Stable Lead Build review URL:** https://raw.githubusercontent.com/aboriginalien/roger-os-public-architecture/main/ARCHITECTURE_CONTINUITY_INDEX.md
- **Source file:** `docs/ops/public/ARCHITECTURE_CONTINUITY_INDEX_SOURCE.md`
- **Last updated:** 2026-06-29 00:00 UTC

This public index is a sanitized review/navigation surface. It does not replace private repository reality, GitHub checks, deploy verification, Lead Build judgment, Architect acceptance, merge approval, or ADR-008 observed-code reconciliation.

## Current Build Status

- **Current active roger-core PR:** PR #211 — Reconcile ADR-013 publish verification evidence.
- **Current readiness state:** `patched, waiting for checks/review` after Codex review finding; public source now records PR #211 as the active PR while keeping PR #210 as merged publication-trigger history.
- **PR #208 state:** `merged` — installed the controlled public Architecture Continuity Index publish mechanism: fail-closed publish script, GitHub Actions workflow, public-safe source, and setup documentation.
- **PR #210 state:** `merged` into `main` as merge commit `914c80f` (`Merge pull request #210 from aboriginalien/codex/update-architecture-continuity-index-workflow`).
- **Controlled publish mechanism:** `installed` by PR #208 and `automated for relevant main pushes` by PR #210.
- **Observed publication gap:** `partially closed` — the public raw Architecture Continuity Index is accessible and now names PR #210, but this source must not claim full ADR-013 operational closure until the GitHub Actions run for PR #210's merge-to-main push is audited as a push-triggered run rather than a manual `workflow_dispatch`.
- **Required correction state:** `PR #210 merged; verification pending for trigger provenance` — normal publication is configured to be automatic after relevant `main` updates; `workflow_dispatch` remains only as emergency/manual fallback, not the normal publication path.
- **Runtime behavior changed:** no. This is docs/workflow/public-index-source-only publishing automation and changes no runtime/provider/model/Vault/memory/routing/writeback/tool/agent-identity behavior.

## PR #210 Publication State

PR #210 has merged to `main` and is no longer the active PR. It added the automatic merge-to-main publication trigger for the public Architecture Continuity Index source and related publishing files.

- **Public raw index freshness:** `current for PR #210 evidence content` — the public raw URL now names PR #210 and includes the PR #210 publication board instead of leaving PR #208 as the latest/current correction.
- **Automatic trigger configuration:** `enabled` for pushes to `main` that change `docs/ops/public/ARCHITECTURE_CONTINUITY_INDEX_SOURCE.md`, `.github/workflows/publish-architecture-continuity-index.yml`, `scripts/publish_architecture_continuity_index.sh`, or `docs/setup/PUBLIC_ARCHITECTURE_PUBLISHING.md`.
- **Automatic publish verification:** `pending trigger-provenance audit` — this evidence packet confirms the public raw index changed and names PR #210, but does not by itself prove the run event was the PR #210 merge-to-main `push` rather than an Operator-triggered `workflow_dispatch`. The remaining gap is to inspect the `Publish Architecture Continuity Index` GitHub Actions run for merge commit `914c80f` and confirm `event=push`, successful conclusion, and public target commit freshness.
- **Manual fallback:** `workflow_dispatch` remains available only as emergency/manual fallback; it is not required for normal publication when the automatic `push` trigger runs successfully.
- **ADR-013 operational statement:** do not claim ADR-013 publication is operationally fixed until the push-triggered automatic run for a relevant `main` update is verified without Operator copy/paste, screenshot couriering, or manual dispatch.

## Active PR Review Board

### PR #211 — Reconcile ADR-013 publish verification evidence

- **PR number:** `#211`
- **PR title:** `Reconcile ADR-013 publish verification evidence`
- **PR URL:** https://github.com/aboriginalien/roger-core/pull/211
- **Branch:** `work`
- **Readiness state:** `patched, waiting for checks/review` — Codex review finding that the public source lacked a current PR #211 active entry has been patched.
- **Changed files list:**
  - `docs/ops/public/ARCHITECTURE_CONTINUITY_INDEX_SOURCE.md` — adds this current PR #211 active review-board entry and keeps PR #210 as merged/published verification history.
  - `docs/ops/ACTIVE_PR_EVIDENCE_INDEX.md` — keeps internal evidence aligned with the PR #211 public-safe source entry and review-comment patch state.
  - `docs/ops/codex/CODEX_CONTINUITY_WORKFLOW.md` — clarifies automatic main-push publication as the normal path and dispatch/script use as fallback only.
- **Checks/status:** `pending GitHub checks`; local docs/evidence checks passed for this patch.
- **Conflicts state:** `none known locally`.
- **Preview/deploy/live verification status where applicable:** public raw URL check confirmed the current published public index names PR #210; PR #211 publication is pending merge/relevant main-push publication. Automatic trigger provenance for PR #210 remains pending until the Actions run for merge commit `914c80f` is audited as `event=push`.
- **Codex/GitHub review comment state:** material Codex review finding patched — this public-safe source now records PR #211 as the current active PR entry before Lead Build review readiness.
- **Material findings:** valid finding that the previous patch updated internal evidence for PR #211 but left the public Active PR Review Board/current active PR focused on PR #210/none.
- **Patches applied after review comments:** added this PR #211 public Active PR Review Board entry; changed Current Build Status to name PR #211; kept PR #210 as merged verification history.
- **ADR-008 obligation/status:** `not required` — docs/evidence/workflow-language-only patch; no runtime, storage, provider, model, memory, Vault, routing, writeback, tool, or agent-identity behavior changed.
- **Runtime/storage/provider/model/memory/Vault/routing/writeback/tool/agent-identity impact statement:** no behavior change; this correction only changes public-safe and internal evidence wording.
- **Forbidden-evidence confirmation:** no credentials, PATs, deploy keys, tokens, env values, provider payloads, hidden prompts, raw Operator prompts, raw Codex task prompts, prompt chains/logs, Vault data, requester-private records, raw audio, or secret-bearing screenshots are included.
- **Remaining gaps:** confirm GitHub checks, conflicts, review-comment state, PR body freshness, and—separately from PR #211 readiness—the PR #210 automatic publish trigger-provenance audit.
- **Exact Lead Build request:** Lead Build: review PR #211 after checks/review settle; do not merge automatically; do not mark ADR-013 publication operationally fixed until PR #210's successful merge-to-main `push` workflow run is verified without manual dispatch.
- **Exact Operator request, if any:** do not merge PR #211 automatically; patch the same PR; keep this docs/workflow/evidence-only; do not expose forbidden evidence.
- **Last updated timestamp:** 2026-06-29 00:00 UTC

### PR #210 — Automate Architecture Continuity Index publishing

- **PR number:** `#210`
- **PR title:** `Automate Architecture Continuity Index publishing`
- **Branch:** `codex/update-architecture-continuity-index-workflow`
- **Status:** `merged` into `main` as merge commit `914c80f`.
- **Purpose:** reconcile ADR-013 with automatic publish-on-main and add automatic publication on relevant pushes to `main` while retaining `workflow_dispatch` only as emergency/manual fallback.
- **Changed files list:**
  - `.github/workflows/publish-architecture-continuity-index.yml` — adds automatic `push` trigger for relevant `main` updates while retaining manual fallback.
  - `docs/adr/ADR-013_codex_pr_evidence_packet_and_active_build_evidence_handoff.md` — explicitly permits controlled automatic publish-on-main and requires merge-safe public source content.
  - `docs/setup/PUBLIC_ARCHITECTURE_PUBLISHING.md` — updates setup language from manual-only to automatic-on-main with fallback dispatch.
  - `docs/ops/public/ARCHITECTURE_CONTINUITY_INDEX_SOURCE.md` — records current public-safe active review board state, merge-safe post-merge state, and the observed stale-public-index gap.
- **Checks/status:** `merged`; GitHub run audit is still needed to prove trigger provenance for the publication run.
- **Conflicts state:** `none known for merged PR #210`.
- **Preview/deploy/live verification status where applicable:** public raw URL now names PR #210; automatic merge-to-main trigger provenance remains pending until the Actions run is audited as `event=push` for merge commit `914c80f`.
- **Publication state:** `public raw refreshed with PR #210 content; automatic trigger provenance pending`.
- **Codex/GitHub review comments summary:** material findings were addressed by reconciling ADR-013 with automatic publication and making this public source merge-safe.
- **Unresolved/resolved review-comment state:** `resolved by merged patch; no unresolved public evidence blocker recorded here except trigger-provenance audit`.
- **Material findings:** public raw index remained stale after PR #209; manual-only publication is insufficient for ADR-013; ADR-013 needed explicit automatic-publish permission; source needed merge-safe post-merge wording.
- **Patches applied after review comments:** ADR-013 operating rule updated; public index source rewritten with merge-safe PR #210 post-merge state.
- **ADR-008 obligation/status:** `not required` for this docs/workflow/public-index-source-only publication automation patch; no runtime, storage, provider, model, memory, Vault, routing, writeback, tool, or agent-identity behavior changed.
- **Runtime/storage/provider/model/memory/Vault/routing/writeback/tool/agent-identity impact statement:** no behavior change; this correction only changes publication workflow triggering, ADR-013 docs, setup docs, and public-safe documentation state.
- **Forbidden-evidence confirmation:** no credentials, PATs, deploy keys, tokens, env values, provider payloads, hidden prompts, raw Operator prompts, raw Codex task prompts, prompt chains/logs, Vault data, requester-private records, raw audio, or secret-bearing screenshots are included.
- **Remaining gaps:** audit the GitHub Actions run for merge commit `914c80f` and confirm it was a successful `push`-triggered automatic publication run; public raw URL freshness is observed because it names PR #210.
- **Exact Lead Build request:** Lead Build: treat PR #210 as merged and public raw content as refreshed, but do not mark ADR-013 publication operationally fixed until the merge-to-main `push` workflow run is verified without manual dispatch.
- **Exact Operator request, if any:** reconcile ADR-013 publication evidence after PR #210 merged; create a new PR only if changes are needed; do not merge automatically; do not create ADR-014; keep this docs/workflow/evidence-only; do not expose forbidden evidence.
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
