# RunFast

GitHub Actions workflow for restoring and validating the `agent-pulse` skill from:

```text
https://github.com/Jane-o-O-o-O/agent-pulse-skills.git
```

Run it from the repository's Actions tab with the `run` workflow.

The scheduled workflow wakes up every 5 minutes and only runs the full matrix on
selected ticks, about every 50 minutes. Each active run randomly starts between
150 and 256 matrix jobs, and each job restores the `agent-pulse` skill and
verifies the `agent-pulse` CLI.
