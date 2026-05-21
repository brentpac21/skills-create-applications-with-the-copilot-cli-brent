Agent Team for Mona's Project Pulse Dashboard

Overview

This repository includes a suggested custom agent team to build Mona's Project Pulse dashboard. Each agent focuses on a specific domain so work can be parallelized and reviewed efficiently.

Agent summaries

- Project Manager Agent — Coordinates the project, defines milestones, writes acceptance criteria, and assigns work to specialist agents.
- Frontend Agent — Implements UI components, responsive behavior, example props, and component tests (React/Vue).
- Backend Agent — Designs APIs, data models, and OpenAPI contract snippets; writes integration tests.
- Data/Analytics Agent — Produces ETL/aggregation logic, SQL/queries, and sample datasets for dashboard metrics.
- Designer (UX) Agent — Creates wireframes, color tokens, and accessibility guidance for the dashboard.
- QA Agent — Writes unit, integration, and e2e test plans; validates outputs against acceptance criteria.
- DevOps Agent — Provides CI/CD workflows, deployment steps, and monitoring/runbook guidance.
- Docs Agent — Produces user-facing docs, onboarding guides, and example queries.

How to use

- Invoke the Project Manager Agent first to create a prioritized backlog and acceptance criteria.
- Assign tickets to specialist agents (frontend/backend/data/designer) and request deliverables (components, endpoints, queries, wireframes).
- Use QA and Docs agents to validate outputs and produce onboarding material before merging and releasing.

If you'd like, these agents can be represented as configuration files under .github/agents/ (a suggested team YAML has been added at .github/agents/team.yml).