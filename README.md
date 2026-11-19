# ClaudeSkills

Personal Claude Code plugin marketplace. One plugin, `my-skills`, bundles:

| Source | What |
|---|---|
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | `impeccable` design skill, 5 agents, design-check hook |
| [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | `security-audit` |
| [Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills) | 67 fullstack skills, `/common-ground`, `/project:*` commands |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | 27 standalone skills (Composio app connectors and Anthropic-licensed docx/pdf/pptx/xlsx not included; use `anthropic-skills:*`) |
| [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice) | `agent-browser`, example skills, agents and commands |

Each skill keeps its upstream license file where one was shipped.

## Install

In Claude Code:

```
/plugin marketplace add utkarshgdb/ClaudeSkills
/plugin install my-skills@utkarsh-skills
```

Skills appear as `my-skills:<name>`.

## Update

Edit files under `plugin/`, bump `version` in `plugin/.claude-plugin/plugin.json`, push, then run `/plugin marketplace update utkarsh-skills`.
