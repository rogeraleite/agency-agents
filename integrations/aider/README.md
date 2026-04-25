# Aider Integration

The full Agency roster is consolidated into a single `CONVENTIONS.md` file.
Aider reads this file automatically when it's present in your project root.

## Quick Navigation

- Install into a project: run the installer from that project root
- Change conversion output: inspect the generated `CONVENTIONS.md`
- Regenerate after agent edits: run `./scripts/convert.sh --tool aider`

## Install

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool aider
```

## How It Works

- All Agency agents are consolidated into one `CONVENTIONS.md`
- Aider reads this file automatically when it exists in the project root
- You can invoke a specialist by naming the agent in your prompt

## Example Prompts

```text
Use the Frontend Developer agent to refactor this component.
```

```text
Apply the Reality Checker agent to verify this is production-ready.
```

## Manual Usage

```bash
aider --read CONVENTIONS.md
```
