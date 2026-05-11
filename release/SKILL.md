---
name: agent-release
description: Use this skill when preparing releases, changelogs, version notes, deployment checks, rollback plans, release readiness reviews, or post-release validation.
---

# Release

Use this skill to prepare and validate software releases.

## Workflow

1. Identify the release scope, target environment, and audience.
2. Confirm required checks: tests, migrations, configuration, feature flags, observability, and documentation.
3. Prepare release notes or changelog entries from actual changes.
4. Define deployment, smoke test, monitoring, and rollback steps.
5. Record known limitations and follow-up work.

## Guidance

- Keep release notes factual and user-impact focused.
- Do not include changes that are not actually in the release.
- Treat migrations, irreversible actions, and external integrations as high-risk items.
- Include exact commands only when they are known and appropriate for the repo.
- Separate pre-release, release, and post-release checks.

## Output

For release tasks, provide:

- Release scope.
- Readiness checklist.
- Release notes.
- Deployment and rollback steps.
- Post-release validation.
