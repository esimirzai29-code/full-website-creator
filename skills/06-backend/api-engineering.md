# Backend & API Engineering

Rules:
- validate all external input;
- authenticate and authorize separately;
- enforce object-level authorization;
- return stable error shapes;
- rate-limit sensitive endpoints;
- paginate list endpoints;
- log security-relevant failures without secrets;
- use idempotency for retry-prone mutations;
- keep privileged logic server-side.

Never trust IDs, email addresses, roles, or client-supplied ownership fields.
