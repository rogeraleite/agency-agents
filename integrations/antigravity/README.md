# Antigravity Integration

Installs the full Agency roster as Antigravity skills. Each agent is prefixed
with `agency-` to avoid conflicts with existing skills.

## Quick Navigation

- Install all skills globally: `./scripts/install.sh --tool antigravity`
- Regenerate skills after editing source agents: `./scripts/convert.sh --tool antigravity`
- Call a specific agent in Antigravity: use the `agency-<agent-name>` slug

## Install

```bash
./scripts/install.sh --tool antigravity
```

This copies generated files into `~/.gemini/antigravity/skills/`.

## How To Invoke Skills

```text
Use the agency-frontend-developer skill to review this component.
```

Common slugs:
- `agency-frontend-developer`
- `agency-backend-architect`
- `agency-reality-checker`
- `agency-growth-hacker`

## Generated File Shape

Each skill is a `SKILL.md` with Antigravity-compatible frontmatter:

```yaml
---
name: agency-frontend-developer
description: Expert frontend developer specializing in...
risk: low
source: community
date_added: '2026-03-08'
---
```
