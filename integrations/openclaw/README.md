# OpenClaw Integration

Use this integration when you want each Agency agent packaged as an OpenClaw workspace.

## Quick Navigation

- Generate workspaces first: `./scripts/convert.sh --tool openclaw`
- Install them globally: `./scripts/install.sh --tool openclaw`
- Find installed workspaces: `~/.openclaw/agency-agents/`
- If the gateway is already running, restart it after install

## Install

```bash
./scripts/convert.sh --tool openclaw
./scripts/install.sh --tool openclaw
```

## How It Works

Each installed agent is a workspace containing:
- `SOUL.md`
- `AGENTS.md`
- `IDENTITY.md`

After installation, invoke the agent by its `agentId` in OpenClaw sessions.

## Gateway Restart

```bash
openclaw gateway restart
```
