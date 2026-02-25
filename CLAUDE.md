# Random Chess Contracts — Rules

This repo is the single source of truth for API: openapi.yaml.

Hard rules:
- Never mention AI/Claude/Codex in code, docs, commits, PR text.
- Do not add new AI/prompt files beyond those already in repo.
- Changes MUST be backward-compatible unless explicitly versioned (new /api/v2 or major bump).

Versioning:
- Patch: docs/examples/typos, no behavior change.
- Minor: additive changes (new optional fields, new endpoints).
- Major: breaking changes (remove/rename fields, change semantics).

Contract change checklist:
- Update openapi.yaml
- Update examples (if present)
- Ensure frontend/backed impact is described in PR
- Prefer additive changes (do not break existing clients)

Workflow:
1) Plan (<=8 bullets)
2) Edit openapi.yaml
3) Validate + self-review (compatibility)