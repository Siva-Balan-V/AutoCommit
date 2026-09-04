# AutoCommit

This repository contains a GitHub Actions workflow that automatically makes a commit on a schedule.

## Workflow

- Runs automatically 3 times daily at **10:35, 17:45, 23:51 Indian Time (IST)**
- Commits and pushes any pending changes (manual or generated) automatically
- No human involvement required

## Files

- `.github/workflows/auto-commit.yml` — GitHub Actions workflow
- `.gitignore` — ignores generated or local-only files if needed
