# my-agent-kit

A personal agent kit: reusable agent skills and repo-wide configuration, plus one folder per case under `cases/`.

## Layout

### Shared part

Used by every case; change it here, not in a case folder.

- `.agents/skills/` — editable copies of the Matt Pocock agent skills. Read the matching `SKILL.md` when a task fits its description.
- `docs/agents/` — repo-wide agent configuration: issue tracker, triage labels, domain docs. Details under Agent skills below.

### Cases

Each `cases/<name>/` is one self-contained piece of work and holds only that case's material. Read the case's own docs for its context.

- `cases/process-panel/` — the current case.

## Agent skills

### Issue tracker

Issues and specs for this repo live as GitHub issues (via the `gh` CLI). See `docs/agents/issue-tracker.md`.

### Triage labels

Five canonical roles mapped 1:1: `needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`. See `docs/agents/triage-labels.md`.

### Domain docs

Single-context: `GLOSSARY.md` + `docs/adr/` at the repo root. See `docs/agents/domain.md`.
