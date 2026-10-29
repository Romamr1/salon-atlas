# salon-atlas

## Layout

- `src/db/` — schema and database connection
- `scripts/` — ingestion, labeling, and eval scripts
- `evals/labels/` — dev labels; agents may read these
- `evals/holdout/` — holdout labels; hidden from agents
- `evals/results/` — eval run results
- `docs/decisions.md` — recorded decisions
- `.claude/skills/` — skills shared by Claude Code and Cursor

## Rules

- Do not read, cite, search, or modify `evals/holdout/`.
- Do not commit `.env` or `data/raw/`.
