# OpenCode Integration

Use this integration when you want Agency agents available as on-demand OpenCode subagents.

## Quick Navigation

- Install into one project: run the installer from that project root
- Find generated files: `.opencode/agents/<slug>.md`
- Invoke a specialist on demand: use `@agent-name`
- Promote agents to global availability: copy them into `~/.config/opencode/agents/`

## Install

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool opencode
```

## How To Invoke Agents

```text
@frontend-developer help build this component.
```

```text
@reality-checker review this PR.
```

## Generated Format

```yaml
---
name: Frontend Developer
description: Expert frontend developer specializing in modern web technologies...
mode: subagent
color: "#00FFFF"
---
```

- `mode: subagent`
  keeps the agent on-demand instead of cluttering the primary picker
- `color`
  stores a hex code converted from the source metadata

## Project vs Global

Agents in `.opencode/agents/` are **project-scoped**. To make them available
globally across all projects, first generate the agent files, then install
with `--path`:
```bash
./scripts/convert.sh --tool opencode
./scripts/install.sh --tool opencode --path ~/.config/opencode/agents
```
