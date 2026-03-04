# LongBrain Plugin Marketplace

Persistent memory for Claude — remembers your preferences, decisions, and lessons across sessions.

## Install

### Claude.ai (GUI)

1. Settings → Plugins → Add Marketplace
2. Enter: `eng-in-law/longbrain-plugins`
3. Install the **longbrain** plugin
4. Set environment variables:
   - `LONGBRAIN_API_KEY` — your API key from [connect.longbrain.me](https://connect.longbrain.me)
   - `LONGBRAIN_BRAIN_ID` — your brain ID (e.g., `my-brain`)

### Claude Code (CLI)

```
/plugin marketplace add eng-in-law/longbrain-plugins
/plugin install longbrain@longbrain
```

Set environment variables:

```bash
export LONGBRAIN_API_KEY=your-api-key
export LONGBRAIN_BRAIN_ID=your-brain-id
```

## Get your API key

Visit [connect.longbrain.me](https://connect.longbrain.me) to create a brain and get your API key.

## Tools

Once installed, Claude gets access to:

| Tool | Description |
|------|-------------|
| `brain_whoami` | View and update your identity |
| `brain_remember` | Save decisions, corrections, and patterns |
| `brain_recall` | Search your memories |
| `brain_sense` | Check current time and memory state |
| `brain_forget` | Suppress a memory |

## Links

- [LongBrain](https://longbrain.me)
- [Documentation](https://docs.longbrain.me)
