# Cursor Integration

Converts the full Agency roster into Cursor `.mdc` rule files. Rules are
**project-scoped** — install them from your project root.

## Quick Navigation

- Install into a project: run the installer from that project root
- Find generated rules: `.cursor/rules/<agent-slug>.mdc`
- Make a rule always-on: edit its frontmatter and set `alwaysApply: true`
- Regenerate after agent changes: `./scripts/convert.sh --tool cursor`

## Install

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool cursor
```

## How To Invoke Rules

```text
@frontend-developer Review this React component for performance issues.
```

## Always-On Example

```yaml
---
description: Expert frontend developer...
globs: "**/*.tsx,**/*.ts"
alwaysApply: true
---
```
