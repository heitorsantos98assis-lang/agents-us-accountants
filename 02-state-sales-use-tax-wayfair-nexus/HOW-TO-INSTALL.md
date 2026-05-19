# 02-state-sales-use-tax-wayfair-nexus — Claude Code Agent

A specialist subagent from the **57 Agents for US Accountants** bundle (Bravy / ASV Digital).

## What this agent does

See `02-state-sales-use-tax-wayfair-nexus.md` for the full description, frameworks, reference tables, and operating flow.

## Installation

### Prerequisites

- [Claude Code](https://docs.claude.com/claude-code) installed and logged in
- A terminal with `unzip`

### Install in 30 seconds

**1. Unzip this archive:**

```bash
unzip 02-state-sales-use-tax-wayfair-nexus.zip
```

**2. Copy the agent into your Claude Code project:**

```bash
mkdir -p .claude/agents
cp 02-state-sales-use-tax-wayfair-nexus.md .claude/agents/

# OR install globally for all projects:
mkdir -p ~/.claude/agents
cp 02-state-sales-use-tax-wayfair-nexus.md ~/.claude/agents/
```

**3. Restart Claude Code** (or run `/agents` to refresh).

**4. Invoke the agent.** Just describe your task — Claude Code will pick this subagent automatically when relevant, or call it explicitly:

```
Use the state-sales-use-tax-wayfair-nexus subagent to ...
```

## Verifying installation

```bash
ls .claude/agents/   # should list 02-state-sales-use-tax-wayfair-nexus.md
# OR
ls ~/.claude/agents/ # for global install
```

In Claude Code, run `/agents` to see the agent listed.

## Updating

When a new version is released, re-run the unzip + copy steps above. The new file overwrites the old one.

## Uninstall

```bash
rm .claude/agents/02-state-sales-use-tax-wayfair-nexus.md
# OR
rm ~/.claude/agents/02-state-sales-use-tax-wayfair-nexus.md
```

## Support

- Documentation: [Claude Code docs — Subagents](https://docs.claude.com/claude-code)
- Issues / questions: open an issue at the repo where you bought this bundle.

---

© Bravy / ASV Digital — 57 Agents for US Accountants
