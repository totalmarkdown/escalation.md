# ESCALATION.md

> *Defines when and how an AI agent should escalate decisions to humans*

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

ESCALATION.md defines the rules for human-in-the-loop safety. It specifies the conditions under which an agent must stop and ask a human, the urgency levels for different types of escalations, and the channels through which escalations happen.

Every autonomous agent will eventually encounter a situation it shouldn't handle alone — a decision with irreversible consequences, an ambiguous instruction, or a scenario outside its training. ESCALATION.md ensures these moments are handled gracefully rather than recklessly.

Create an ESCALATION.md for any agent that operates with autonomy. The more autonomous the agent, the more important its escalation protocol becomes.

---

## Quick Start

```bash
curl -O https://raw.githubusercontent.com/totalmarkdown/escalation.md/main/ESCALATION.md
```

Add to your project root and customize for your agent.

---

## When to use ESCALATION.md

- Defining when a customer support agent should transfer to a human representative
- Setting thresholds for a trading agent to pause and await human confirmation
- Establishing escalation channels for an agent that manages infrastructure changes

---

## Where it fits

Critical companion to LIMITS.md (hard boundaries) and GUARDRAILS.md (runtime safety). Works with ICE.md (emergency protocols). Referenced by AGENTS.md and CLAUDE.md.

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
