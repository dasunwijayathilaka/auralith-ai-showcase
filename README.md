# Auralith AI

### A self-hostable AI workspace
**Full-stack Software Engineering Portfolio Project**

Auralith AI is an actively developed AI workspace built with
React, Fastify, TypeScript, and shared Zod contracts.

It explores secure authentication, AI-assisted conversations,
workspace isolation, document ingestion, and extensible
persistence architecture.

> **Portfolio showcase:** The complete application source code
> is maintained in a separate private repository.

## Highlights

- **Full-stack TypeScript:** React client, Fastify API, and shared contracts.
- **Authentication:** Registration, email OTP, login, password reset, and sessions.
- **AI conversations:** Chat workflows and saved conversation history.
- **Workspaces:** Membership checks and authorization boundaries.
- **Document retrieval:** Text ingestion and lexical retrieval fallback.
- **Local-first AI:** Ollama integration with configurable models.
- **Database engineering:** PostgreSQL configuration and migration safety tooling.
- **Quality assurance:** Automated tests, linting, type checking, and builds.

## Verified engineering results

| Check | Result |
|---|---|
| Automated tests | 433 passed |
| Test files | 36 passed |
| Skipped tests | 5 |
| ESLint | Passed |
| TypeScript | Passed |
| Backend build | Passed |
| Frontend build | Passed |
| Local Gitleaks scan | 0 findings |

Results reflect the verified local publication snapshot,
not an independent production security certification.

## Architecture

```text
React 19 + Vite + Tailwind CSS
             |
             v
      Fastify API
             |
    +--------+--------+
    |        |        |
 Authentication  AI   Workspaces
    |        |        |
 Sessions   Ollama   Documents
             |
     Shared Zod contracts
             |
   Memory / PostgreSQL design
```

The backend validates configuration and enforces authorization.
PostgreSQL runtime activation remains subject to migration and
deployment readiness checks.

## Technology

**Frontend:** React, TypeScript, Vite, Tailwind CSS

**Backend:** Node.js, Fastify, Zod

**AI:** Ollama, Groq integration, document retrieval

**Database:** PostgreSQL configuration and migration tooling

**Testing:** Vitest, ESLint, TypeScript

**Automation:** GitHub Actions workflow

## Screenshots

Real application screenshots will be added following privacy review.

## Project status

**Active development — not a production-ready SaaS release.**

Live AI model execution, deployment readiness, PostgreSQL runtime
activation, advanced analytics, usage accounting, and additional
security hardening require further verification or implementation.

## Repository access

This is a **public portfolio showcase**, not a distribution
of the Auralith AI application source code.

The full source repository is private.

## Copyright

All rights reserved. No license to reuse the showcase
materials is granted.