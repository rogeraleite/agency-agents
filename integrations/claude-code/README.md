# Claude Code Integration

Use this integration when you want the source Agency agents to work natively in Claude Code without conversion.

## Quick Navigation

- Install all agents: `./scripts/install.sh --tool claude-code`
- Copy only one category: `cp <category>/*.md ~/.claude/agents/`
- Find the full roster: see the [main README](../../README.md)

## Install

```bash
./scripts/install.sh --tool claude-code
```

Or copy only one category:

```bash
cp engineering/*.md ~/.claude/agents/
```

## How To Invoke Agents

```text
Activate Frontend Developer and help me build a React component.
```

```text
Use the Reality Checker agent to verify this feature is production-ready.
```

## Agent Directory

Agents are organized into divisions. See the [main README](../../README.md) for
the full Agency roster.
