# Node.js & Express Production Reference Guide

This is an interactive, production-oriented reference guide for building web applications with Node.js and Express. It was developed through a series of deep dives covering the full application stack — from project setup and module design through to deployment, security hardening, and observability. Each section includes working code examples, architectural diagrams, and the rationale behind each decision, reflecting current best practices as of 2025.

Topics covered include project initialization, TypeScript and ESM configuration, feature-based architecture, the router/controller/service pattern, database integration with the repository pattern, JWT authentication with refresh token rotation, OAuth/OIDC flows, API key authentication, HTTP security headers, CSP, CSRF, injection and XSS prevention, supply chain security, CORS configuration, Nginx as a reverse proxy, and OpenTelemetry-based observability across traces, metrics, and logs. The guide is intended to grow over time as additional topics are added.

## Usage

Each section of the guide is self-contained and navigable via a sidebar. Code examples are production-oriented — they reflect current best practices as of 2025, including decisions like `jose` over `jsonwebtoken`, `csrf-csrf` over the deprecated `csurf`, `argon2id` over `bcrypt`, and `--import` over `--require` for OTel instrumentation in ESM projects.

The guide was built as an interactive reference companion — intended to be consulted during development rather than read front to back.
