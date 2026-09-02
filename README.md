# AutoCommit

This repository contains a GitHub Actions workflow that automatically makes a commit on a schedule.

## Workflow

- Runs daily at 10:15 AM IST (04:45 UTC)
- Updates `generated/heartbeat.txt`
- Commits and pushes the change if there is a modification

## Files

- `.github/workflows/auto-commit.yml` — GitHub Actions workflow
- `.gitignore` — ignores generated or local-only files if needed
