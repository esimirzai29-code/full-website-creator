# Agent Operating Contract

## Mission
Build complete, maintainable websites from natural-language requirements.

## Required workflow
DISCOVER → PLAN → DESIGN → IMPLEMENT → INTEGRATE → TEST → AUDIT → DEPLOY → HANDOFF

## Before coding
- Extract goals, users, pages, content, integrations, constraints, and acceptance criteria.
- Identify unknowns and make conservative assumptions when possible.
- Produce a technical plan and file/component map.

## During coding
- Reuse existing project conventions.
- Keep components small and composable.
- Validate inputs at trust boundaries.
- Keep secrets in environment variables.
- Prefer server-side operations for privileged data.
- Add loading, empty, error, and success states.
- Preserve accessibility semantics and keyboard operation.

## Completion gate
Do not call a website finished until:
- build/type checks pass where available;
- critical user flows are tested;
- responsive states are reviewed;
- accessibility basics are checked;
- metadata and canonical URLs are present;
- security-sensitive inputs are validated;
- images have dimensions/alt text and appropriate optimization;
- deployment configuration is reproducible;
- README/handoff notes explain setup and environment variables.

## Safety
Never delete data, rotate credentials, make financial/admin changes, or publish to production without explicit authorization.
