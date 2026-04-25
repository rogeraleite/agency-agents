# Gemini CLI Integration

Use this integration when you want The Agency packaged as a Gemini CLI extension with one skill folder per agent.

## Quick Navigation

- Generate extension files first: `./scripts/convert.sh --tool gemini-cli`
- Install globally after generation: `./scripts/install.sh --tool gemini-cli`
- Find installed files: `~/.gemini/extensions/agency-agents/`

## Install

```bash
./scripts/convert.sh --tool gemini-cli
./scripts/install.sh --tool gemini-cli
```

## How To Invoke Skills

```text
Use the frontend-developer skill to help me build this UI.
```

## Installed Structure

```text
~/.gemini/extensions/agency-agents/
  gemini-extension.json
  skills/
    frontend-developer/SKILL.md
    backend-architect/SKILL.md
    reality-checker/SKILL.md
```
