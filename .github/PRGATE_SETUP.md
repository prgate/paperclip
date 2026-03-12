# PRGate Setup (PRG-116)

## Required secrets (Settings → Secrets → Actions)

| Secret | Purpose |
|--------|---------|
| `PRGATE_REPO_TOKEN` | PAT with `repo` scope — для pip install из приватного prgate/prgate |
| `ANTHROPIC_API_KEY` | API key для Claude (или другой LLM по .prgate.yaml) |

## After adding secrets

Re-run the failed workflow on PR #1, or push a new commit to trigger it.
