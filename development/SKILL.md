---
name: agent-development
description: Use this skill for general software development work that spans implementation, refactoring, debugging, testing, or coordinating multiple development sub-tasks.
---

# Development

Use this skill to keep development work scoped, verifiable, and aligned with the existing codebase.

## Workflow

1. Read the relevant code before proposing or editing.
2. Define the smallest useful change and the expected behavior.
3. Implement using existing project patterns and helpers.
4. Add or update focused tests when behavior changes.
5. Run the most relevant verification available in the local environment.

## Guidance

- Prefer local conventions over generic best practices.
- Keep unrelated refactors out of the change.
- Preserve user work in the working tree.
- Make failure modes visible in errors, logs, or tests when appropriate.
- Stop and ask only when a missing decision would make the change risky or incorrect.

## Output

For development tasks, provide:

- Files changed.
- Behavior changed.
- Verification run.
- Any remaining risks or blocked checks.
