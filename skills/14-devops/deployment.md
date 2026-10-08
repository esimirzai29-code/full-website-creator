# DevOps & Deployment

Deployment must be reproducible.

Define:
- build command;
- runtime version;
- environment variables;
- database migration process;
- health check;
- logging;
- rollback strategy;
- domain/HTTPS configuration;
- preview/staging environment;
- production verification.

Never print secret values in CI logs. Production deployment is an explicit-action boundary.
