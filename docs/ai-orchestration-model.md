# AI Orchestration Model

## Purpose

The AI assistant coordinates workflows and routes requests while remaining outside the authentication trust boundary.

AI responsibilities:

- intent recognition
- workflow routing
- request classification
- escalation triggering

AI responsibilities explicitly exclude:

- authentication
- authorization
- security trust evaluation

---

## Workflow

```text
User Request
      ↓
Copilot Studio
      ↓
Intent Classification
      ↓
Power Automate
      ↓
Collect Signals
      ↓
Decision Sources
      ↓
Action Execution
```

---

## Trust Boundary Rule

AI orchestration cannot override:

- Conditional Access
- Identity Protection
- Device compliance controls
