# Patrick Reynolds

**People matter. Applications must be AI friendly.**

Those are the two principles I lead by, and everything on this profile is evidence of what happens when you take them seriously.

I run [Cross Link Consulting](https://crosslinkconsulting.net), a security-first IT firm that has served county and municipal governments, healthcare and legal practices, accounting firms, and industrial clients across the Augusta area since 2004. I founded [Resolute AIM](https://resoluteaim.com) to help organizations stop asking AI questions and start putting AI to work, safely, for their people. Most of what goes wrong with AI is not an AI problem. It is an access problem, an identity problem, a data-handling problem. Those are problems I have been solving for twenty-two years.

## What I build

Most of my production work is private and belongs to the organizations it serves, so the repositories here describe the systems rather than expose them. Each README covers the problem, the architecture, the security posture, and the honest outcome, including what did not work.

| Repository | What it is | Status |
|---|---|---|
| governed-agent-platform | Multi-tenant platform where technicians build and run AI agents against real business systems under tiered least-privilege skills, human-approved permission manifests, and a supervising Director agent | Production, one MSP, 33 client tenants |
| shepherd | Self-hosted endpoint control plane and Windows agent with tenant isolation, signed tasking, and a hash-chained audit log, built so an AI agent can operate a fleet safely | Working prototype, ten ADRs |
| gpu-queue-ledger | PowerShell reservation ledger that lets many concurrent AI-agent sessions share one workstation's GPU and RAM without collisions | In daily use, full source |
| agentic-engineering-process | The written operating model for teams of people and AI agents: audit-first work packets, isolated worktrees, worker, verifier, and adversarial-reviewer roles, a test gate on every pull request | In daily use |

Research repositories cover local inference of very large mixture-of-experts models on a single workstation, lossless LLM-driven compression, deterministic context management for long agent sessions, and on-device model selection for phones. Every one keeps a numbered journal, pre-registers decisions, and records negative results.

## How I work

- Least privilege first. An agent gets the narrowest scope that does the job, and a human approves the scope before the agent runs unattended.
- U.S. inference, no training on our data, zero retention. Providers that cannot promise all three in writing do not get sensitive workloads.
- Written standards over tribal knowledge. Decision records, journals, and a README that is the source of truth for people and agents alike.
- Adversarial verification. Convenient claims get audited by a fresh reviewer before they are believed.
- Plain language. If a technician cannot follow it, it is not finished.

Portfolio and case studies: [guyprompting.com](https://guyprompting.com) - [LinkedIn](https://www.linkedin.com/in/patrickreynolds)
