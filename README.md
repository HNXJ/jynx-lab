# gamma-tools

Agent tools, skills and coordination utilities.

Proposed future name: **jynx-lab** (proposal, not renamed yet)

## Place in the 7-repo layout

Plane: **LAB**. See [HNXJ/jynx-arena](https://github.com/HNXJ/jynx-arena) and its [architecture](https://github.com/HNXJ/jynx-arena/blob/main/docs/protocol/ARCHITECTURE.md) (ARENA, RULES, SCIENCE, LAB, ENGINE, JUDGE, WORLD). The current jynx-arena runtime is proposed to become **jynx-engine**; **jynx-world** (event ledger, projections) is a new proposed repo.

## Holds today

- Python utilities at root (`CLI_router.py`, `git_sync.py`, `memory_manager.py`, etc.).
- Skill/template/coordination folders: `active_skills/`, `agent_templates/`, `agent_requests/`, `ledgers/`, `docs/`, and others.
- Proposed to merge with `gamma-analysis` into **jynx-lab**.

## Shared root layout (target, not yet applied)

`artifacts/`, `docs/`, `src/`, `schemas/`, `tests/`, `tournaments/`, `README.md` — see [SHARED_ROOT_LAYOUT](https://github.com/HNXJ/jynx-arena/blob/main/docs/protocol/SHARED_ROOT_LAYOUT.md).

## Truth safety

A Judge PASS means a submission met a rubric under a protocol version; it is not scientific truth.

No secrets: no tokens, API keys, passwords or `.env` contents in this repo.
