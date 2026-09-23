# VantaBlade product-system case studies

These case studies document implemented VantaBlade product systems as engineering evidence. They focus on architecture, system boundaries, engineering decisions, and transferable patterns rather than product marketing.

VantaBlade builds security products. The portfolio uses those products to demonstrate broader full-stack and applied-AI engineering capability across interfaces, APIs, persistence, external providers, workflow reliability, automation, reporting, analytics, and operational tooling.

The underlying product repositories are not linked here as public proof. Each study identifies what the implementation supports, keeps sensitive details abstract, and avoids unsupported claims about customers, performance, scale, certifications, or business outcomes.

## Case studies

### [VantaBlade Identity Risk Ops](vantablade-identity-risk-ops.md)

An authenticated multi-tenant SaaS system spanning a Next.js customer workspace, typed API contracts, FastAPI services, Supabase Auth, PostgreSQL/RLS, employee entitlements, background exposure scans, incident and identity-case workflows, reporting, analytics, and supporting operator tools.

This is the strongest integrated product-system example in the portfolio.

### [VantaBlade DeepScan](deepscan.md)

A multi-provider identity-intelligence workflow that normalizes heterogeneous exposure data, applies deterministic and AI-assisted analysis within explicit authority boundaries, and coordinates paid intake, background execution, persisted results, PDF reporting, storage, and delivery.

### [VantaBlade FreeScan](freescan.md)

A compact public data product connecting anonymous intake, HIBP retrieval, normalized result presentation, report generation, persistence, delivery, analytics, and the downstream DeepScan funnel.

## How these studies relate to the public proofs

Product systems show capabilities operating together. The public proof repositories isolate recurring patterns so a reviewer can inspect and run them independently:

- [Reliable Data Intake Pipeline](https://github.com/vantablade-ai/reliable-data-intake-pipeline)
- [Controlled AI Decision Pipeline](https://github.com/vantablade-ai/controlled-ai-decision-pipeline)
- [Reliable Webhook Workflow](https://github.com/vantablade-ai/reliable-webhook-workflow)
- [Signal-to-Content Automation Pipeline](https://github.com/vantablade-ai/signal-to-content-automation-pipeline)

[Return to the engineering portfolio](../README.md)
