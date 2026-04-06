# Agent Portraits — IAI

Public hosting for IAI agent portrait files. Used by Lumen and other agents via the Canva MCP.

## URL pattern

```
https://raw.githubusercontent.com/marnie-iai/agent-portraits/main/portraits/{agent}.png
```

## Usage

Any agent workflow can construct a portrait URL from the agent name alone — no lookup table required.

## Adding portraits

1. Add the portrait PNG to `portraits/` using lowercase agent name: `{agent}.png`
2. Commit and push to `main`
3. The file is immediately accessible via the raw URL above
