# ESCALATION.md

> *Defines when and how AI agents escalate to human oversight*

[![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Part of agent-md-specs](https://img.shields.io/badge/part%20of-agent--md--specs-blue)](https://github.com/totalmarkdown/agent-md-specs)
[![Maintained by TotalMarkdown](https://img.shields.io/badge/maintained%20by-TotalMarkdown.ai-8B5CF6)](https://totalmarkdown.ai)

**Maintained by TotalMarkdown.ai**
· License: CC0 1.0 Universal — Public Domain
· Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
· [Discussions](https://github.com/totalmarkdown/escalation.md/discussions)

> TotalMarkdown.ai is currently in development. Star this repo to follow progress.

---

> **Canonical Source:** This spec is maintained in the main
> [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs) repository.
> This repo is an auto-synced mirror for easy discovery and download.
> To report issues or submit changes, please open a PR or issue on the
> [main repository](https://github.com/totalmarkdown/agent-md-specs).

## What is ESCALATION.md?

ESCALATION.md is the human-in-the-loop safety spec. It defines the triggers, levels, and contacts for when an agent needs human intervention — from simple approvals to emergency shutdowns.

Every enterprise deployment needs clear escalation paths. Without them, agents either block on uncertainty (wasting time) or proceed recklessly (causing harm). ESCALATION.md ensures the right human gets involved at the right time.

Create an ESCALATION.md for any agent that makes decisions affecting real systems, processes sensitive data, or operates in regulated environments.

---

## Quick Start

```bash
curl -O https://raw.githubusercontent.com/totalmarkdown/escalation.md/main/ESCALATION.md
```

Add to your project root and customize for your agent.

---

## When to use ESCALATION.md

- Any agent that makes decisions affecting real systems or people
- Agents handling sensitive data or financial transactions
- Multi-agent fleets where failures need clear escalation paths

---

## Where it fits

Works alongside LIMITS.md (hard stops that trigger escalation), DELEGATION.md (authority chain that defines who to escalate to), CIRCUITBREAKER.md (failure-triggered escalation), and ENFORCEMENT.md (policy violations trigger escalation).

---

## The Full Spec

→ [ESCALATION.md](./ESCALATION.md)

---

## Part of agent-md-specs

One of 178 specs in [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
— the open standard library covering every dimension of AI agent configuration.

---

## Contributing

1. Open an issue describing your proposed change
2. Fork and make your edit
3. Open a PR — all contributions must be CC0

---

## License

[CC0 1.0 Universal](./LICENSE) — Public Domain.
Use freely for any purpose, no attribution required.

---

*Maintained by TotalMarkdown.ai*
*Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)*
