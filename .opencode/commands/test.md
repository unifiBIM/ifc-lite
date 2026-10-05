---
description: Validate the approved implementation and diagnose test failures.
agent: tester
---

Validate this task:

$ARGUMENTS

Use the available:

- approved task;
- repository discovery report;
- architecture plan;
- current diff;
- reviewer findings.

Do not perform broad repository discovery unless required to diagnose a failure.

Run:

1. Focused tests for changed behavior.
2. Relevant typecheck or build checks.
3. Repository-required validation commands from `AGENTS.md`.

If the task changes OpenCode, Claude, agents, commands, skills, MCP, or external tool configuration, validate those changes as far as the available tools allow.

Do not commit.
Do not push.
Do not reset.
Do not revert.

Return:

- checks executed;
- pass/fail result;
- failure diagnosis;
- coverage;
- remaining risks;
- final validation status.
