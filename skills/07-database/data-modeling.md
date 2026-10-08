# Database & Data Modeling

Start from entities and relationships, then design indexes around real query patterns.

Checklist:
- primary/foreign keys;
- uniqueness constraints;
- nullability;
- timestamps;
- soft delete only when justified;
- indexes for frequent filters/joins;
- migrations;
- seed data separated from production data;
- backup/recovery expectations.

Do not expose database credentials to the browser.
