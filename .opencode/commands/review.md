---
description: Review the implementation against the approved plan and repository discovery.
agent: reviewer
---

Review the current implementation for this task:

$ARGUMENTS

Use the available:

- repository discovery report;
- approved architecture plan;
- current Git diff;
- relevant source files;
- relevant tests.

Do not perform broad repository discovery unless required.

Check:

1. Functional correctness.
2. Regression risk.
3. Security and data handling.
4. Test coverage.
5. Architecture compliance.
6. Scope compliance.
7. Code reuse.
8. Agent, command, and skill duplication.
9. Instruction conflicts.
10. Maintainability.

Do not modify files.
Do not commit or push.

Return findings ordered by severity.

If there are no findings, state that explicitly.
