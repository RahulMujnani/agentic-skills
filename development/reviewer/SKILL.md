---
name: agent-code-reviewer
description: Use this skill when reviewing code changes, pull requests, diffs, implementation plans, or tests for bugs, regressions, maintainability issues, and missing validation.
---

# Code Reviewer

Use this skill to review changes with a defect-focused engineering lens.

## Workflow

1. Inspect the diff and the surrounding code needed to understand behavior.
2. Look first for correctness issues, regressions, security problems, data loss, and missing tests.
3. Check whether the implementation matches the stated requirement and existing project conventions.
4. Prioritize findings by severity and cite exact file and line references.
5. If no issues are found, state that clearly and mention any residual test gaps.

## Guidance

- Findings come before summaries.
- Do not spend review space on subjective style unless it affects maintainability or behavior.
- Avoid recommending broad refactors unless they directly reduce risk in the reviewed change.
- Treat unverified behavior as a risk, not as a confirmed bug.
- Be explicit about assumptions and reproduction paths.

## Output

For reviews, provide:

- Findings ordered by severity with file and line references.
- Open questions or assumptions.
- Brief change summary only after findings.
- Verification gaps.
