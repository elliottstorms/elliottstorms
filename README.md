# Elliott Storms

Fintech implementation and digital banking, 13+ years. Now building the automation that used to need a team.

Most of my public work comes back to one question: how much of an operation can you hand to AI agents before it stops being trustworthy? So far the answer is "more than you would expect, as long as the guardrails are scripts with exit codes rather than good intentions."

## Repositories

### [moonops-toolkit](https://github.com/elliottstorms/moonops-toolkit)

`Python` · MIT

The operator toolkit for running an AI setup on top of [Claude Code](https://docs.claude.com/en/docs/claude-code): seven single-purpose sub-agents, hook scripts, a self-healing skill library, a small dark-mode design system, and a set of working templates.

It also ships a PII kit (a checksum-validating scanner, gates on both the tool-call and commit paths, and two adversarial review agents) for working with AI assistants around personal data.

The pipeline that generates the repo treats its own author as a security risk: a deny-by-default allowlist plus a fail-closed secrets tripwire. That is the intended amount of trust.

### [moonstorms](https://github.com/elliottstorms/moonstorms)

`HTML` · GitHub Pages

Landing page for a long-form sleep audio catalog. Static, no dependencies, served directly from Pages.

## How I build

1. The intelligence belongs in scripts and contracts, not in the model. Every check has an exit code, so it behaves the same on any model tier.
2. Deny-by-default on anything that ships publicly.
3. "The tool returned success" is a claim, not a verification.
4. Read before writing, and report every change. No silent edits.

## Elsewhere

[moonops.org](https://www.moonops.org)
