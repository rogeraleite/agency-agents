# GitHub Copilot Integration

Use this integration when you want Agency agents available natively in GitHub Copilot without conversion.

## Quick Navigation

- Install all agents: `./scripts/install.sh --tool copilot`
- Copy only one category: `cp <category>/*.md ~/.github/agents/`
- Browse the roster: see the [main README](../../README.md)

## Install

```bash
# Copy all agents to your GitHub Copilot agents directories
./scripts/install.sh --tool copilot
```

Or copy one category manually:

```bash
cp engineering/*.md ~/.github/agents/
cp engineering/*.md ~/.copilot/agents/
```

## How To Invoke Agents

```text
Activate Frontend Developer and help me build a React component.
```

```text
Use the Reality Checker agent to verify this feature is production-ready.
```
