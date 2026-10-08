# Web Security

Threat model before exposing sensitive functionality.

Minimum controls:
- secure session/cookie configuration;
- authorization on every protected resource;
- CSRF protection where applicable;
- output encoding and XSS-safe rendering;
- parameterized queries/ORM;
- server-side validation;
- rate limiting;
- secure headers;
- dependency updates;
- safe file upload handling;
- secret management.

Never place secrets in client bundles, commits, logs, screenshots, or generated documentation.
