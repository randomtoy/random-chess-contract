# Random Chess Contracts (Codex)

Source of truth: openapi.yaml only.

Rules:
- Never mention AI/Claude/Codex in code, docs, commits, PR text.
- Do not add new prompt/AI files beyond existing repo set.
- Prefer backward-compatible changes. Breaking -> /api/v2 or major bump.

Process:
PLAN (<=8 bullets) -> EDIT openapi.yaml -> REVIEW (compat + consistency)