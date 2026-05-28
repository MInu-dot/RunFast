# RunFast

GitHub Actions workflow for restoring and validating the `agent-pulse` skill from:

```text
https://github.com/Jane-o-O-o-O/agent-pulse-skills.git
```

Run it from the repository's Actions tab with the `run` workflow.

The scheduled workflow runs 30 times per day, spread about 48 minutes apart.
Each run randomly starts between 150 and 256 matrix jobs, and each job restores
the `agent-pulse` skill and verifies the `agent-pulse` CLI.
