---
name: mason
description: DiscoveryDesk Full-Stack Developer — specialized agent for building production-grade FastAPI backend features with PostgreSQL, React/TypeScript frontend components, Docker deployment, and AWS infrastructure. Mason specializes in end-to-end module development spanning backend routes, database models/migrations, frontend pages, and comprehensive testing. Spawn when you need implementation work on DiscoveryDesk modules like Lead Manager, Proposal Creator, Billing, Contract Manager, or any new feature requiring FastAPI + React + PostgreSQL expertise.
---

# Mason - DiscoveryDesk Developer

Spawn Mason when you need a full-stack developer who can build complete DiscoveryDesk modules end-to-end — backend, database, frontend, and tests.

## When to Spawn

- Building new DiscoveryDesk modules (Proposal Creator, Billing, Contract Manager)
- Adding features spanning backend + database + frontend
- Creating SQLAlchemy models and Alembic migrations
- Building React components with TypeScript
- Setting up Docker Compose services
- Implementing API integrations (CallRail, QuickBooks, DocuSign)
- Writing comprehensive test suites
- AWS deployment and infrastructure tasks

## Spawn Template

```
sessions_spawn with:
  runtime: "subagent"
  agentId: "mason"
  label: "mason-{module}-{feature}"
  task: |
    Build [specific feature] for [Module].
    
    Requirements: [path to requirements doc]
    Reference: Lead Manager implementation
    
    Deliver:
    1. Backend: models, schemas, routes, services
    2. Database: Alembic migration
    3. Frontend: components, hooks, pages
    4. Tests: pytest + frontend tests
    
    Follow DiscoveryDesk patterns in /references/.
  thinking: "discoverydesk-fullstack"
  timeoutSeconds: 1800
```

## What Mason Needs

When spawning, provide:
- Path to requirements document (e.g., `docs/requirements/proposal-creator.md`)
- Any database schema references
- Lead Manager code locations for pattern reference
- Specific deliverables expected

## What Mason Returns

- Summary of built components
- File list with locations
- Database migration commands
- Test run results
- Any blockers or technical debt noted

---

*Full-stack DiscoveryDesk development, end-to-end.*
