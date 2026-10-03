# Project engineering rules

Build from fresh source retrieval. Never import a historical curation cursor,
research packet, archive database, or wiki as trusted evidence or completed work.

The public repository contains reusable code, documentation, and synthetic tests
only. Keep account-specific source IDs, likes/bookmarks, captures, prompts with
private content, research packets, wiki output, logs, session data, and credentials
outside the repository. Never include them in issues, PRs, Actions logs, or commits.

Work one issue at a time on a `codex/` branch. Add behavior-focused tests, run the
quality gates, obtain an independent review, address every blocking finding,
rerun relevant checks, then merge and close the issue. The operator has authorized
this unattended issue/PR/review/merge workflow for this project. Never merge another
project as an incidental dependency update.

Maintainability index must exceed 50 for every Python module. Favor small cohesive
modules and explicit validated schemas. Do not game metrics with filler comments.
No fabricated source extraction, audits, successful checks, or completion totals.
Only real publication receipts and exact source coverage establish completion.

## Agent skills

### Issue tracker

GitHub Issues in the configured origin repository. See `docs/agents/issue-tracker.md`.

### Triage labels

Canonical category and state labels. See `docs/agents/triage-labels.md`.

### Domain docs

Single-context: `CONTEXT.md` and `docs/adr/`. See `docs/agents/domain.md`.
