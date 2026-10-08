# Testing & QA

Use layered tests:
1. static/type checks;
2. unit tests for critical logic;
3. component tests for interactive UI;
4. API/integration tests;
5. end-to-end tests for primary flows;
6. accessibility checks;
7. production build verification.

For each critical feature define happy path, validation failure, authorization failure, empty state, network failure, and retry behavior.
