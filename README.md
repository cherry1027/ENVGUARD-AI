# EnvGuard AI — Agentic Test Environment Readiness Copilot

An independent research prototype exploring agent-assisted readiness analysis for synthetic integration-test environments.

**Live demo:**  
https://envguard-ai-readiness.charanvaranasi44.workers.dev

## Features

### Readiness Analyzer

- Editable YAML-style environment configuration
- Schema, completeness, consistency, and dependency checks
- Synthetic readiness score
- Four conceptual analysis agents:
  - Schema Agent
  - Dependency Agent
  - Resource Agent
  - Readiness Agent
- Suggested configuration diff
- Re-analysis flow ending in a `READY` state

### Orchestration Reliability

Visualizes the path from requirements to integration testing:

`Requirements → Environment Generation → Schema Validation → Data Quality → Dependency Check → Readiness → Provision / Block → Integration Tests`

Compares three synthetic approaches:

- Manual
- Schema Validation
- AI + Quality Orchestration

Metrics include provision success, configuration errors, manual effort, and data quality.

## Technology

- React
- TypeScript
- Vinext
- Tailwind CSS
- Cloudflare Workers
- Wrangler
