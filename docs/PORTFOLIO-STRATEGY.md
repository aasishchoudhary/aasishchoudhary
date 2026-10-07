# Aasish FX — Production AI Ecosystem Strategy

## Mission

Build a coherent open-source AI systems laboratory that demonstrates the ability to design, implement, test, secure, observe and operate agentic software.

The portfolio is not a collection of AI demos. Each repository owns a distinct platform capability and uses shared engineering contracts.

## Portfolio architecture

### Core execution
1. [AI Automation Engine](https://github.com/aasishchoudhary/ai-automation-engine) — policy-controlled task and tool execution.

### Intelligence
2. [Research Intelligence System](https://github.com/aasishchoudhary/research-intelligence-system) — evidence, claims, provenance, contradictions and reproducible research reports.

### Agent infrastructure
3. Auditable Agent Memory — provenance-aware persistent state.
4. Context Runtime — context budgeting, compression, retrieval and session state.
5. Background Agent Runtime — durable jobs, checkpoints, recovery and verification.

### Reliability and security
6. AI Evaluation Lab — datasets, traces, regression tests and quality metrics.
7. Agent Security Lab — tool permissions, sandboxing and agent/MCP security.

### Platform
8. Agent Integration Hub — APIs, webhooks, queues, databases and external services.
9. Agent Control Plane — agents, jobs, identities, policies, approvals and fleet state.
10. Aasish FX Console — optional operator interface for the ecosystem.

## Common platform concepts

The repositories should converge on a small shared vocabulary:

```
Task
Agent
Run
Tool
Artifact
Event
Policy
Approval
Evidence
Memory
Trace
Evaluation
```

The purpose is interoperability, not framework lock-in.

## Production gate

A component is not called production-grade merely because it runs.

```
WORKS
  ↓
TESTED
  ↓
OBSERVED
  ↓
SECURED
  ↓
EVALUATED
  ↓
RECOVERABLE
  ↓
DEPLOYABLE
  ↓
PRODUCTION
```

Each claim must be backed by evidence.

## Technology strategy

- Python: AI, data, research, evaluation and orchestration.
- TypeScript: APIs, services, interfaces and production-facing systems.
- Containers: reproducible and isolated execution.
- Cloud: deploy only where the operational requirement justifies it.
- CI: every flagship repository must have automated validation.

GitHub's 2025 Octoverse data supports this division: TypeScript became the most-used language on GitHub while Python remained dominant in AI/data; Dockerfile adoption also grew strongly as AI workloads moved toward reproducibility and production. 

## Development phases

### Phase 1 — Public foundation
- strengthen AI Automation Engine
- build Research Intelligence System
- establish common quality/security standards

### Phase 2 — Agent infrastructure
- memory
- context
- background execution

### Phase 3 — Reliability
- evaluation
- observability
- regression datasets

### Phase 4 — Security
- permissions
- sandboxing
- threat modeling
- agent/MCP inspection

### Phase 5 — Platform
- integration hub
- control plane
- operator console
- staging/production deployment

## Trust rules

Never fabricate:
- clients
- revenue
- testimonials
- benchmarks
- production status
- deployment status
- certifications
- research evidence

Always label:
- implemented
- tested
- experimental
- planned
- unknown

## Portfolio objective

The visitor should be able to conclude:

> Aasish FX understands how to build AI systems around models — execution, evidence, memory, context, reliability, security and operations — rather than merely calling an AI API.
