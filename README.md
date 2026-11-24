# plain-writing

An [Agent Skill](https://agentskills.io) that makes the assistant write plain, precise prose without the usual AI tells: em dashes, "not X, but Y" contrasts, inflated words, closing summaries, decorative bold. It applies to docs, READMEs, guides, write-ups, messages and emails. Works with any agent that supports the SKILL.md format (Claude Code, Claude.ai, Codex CLI, Gemini CLI, Cursor, and others).

## Install

With Claude Code, from the [viktoras marketplace](https://github.com/viktoras25/skills):

```
/plugin marketplace add viktoras25/skills
/plugin install plain-writing@viktoras
```

Or copy the `skills/plain-writing/` folder into your agent's skills directory, e.g.:

- Claude Code: `~/.claude/skills/plain-writing/`
- Codex CLI: `~/.codex/skills/plain-writing/`
- Other agents: see their docs for the skills folder.

## Use

The skill triggers on its own when you ask for writing meant for people to read. You can also call it by name: "write the release notes with plain-writing", or `/plain-writing` in Claude Code.

## License

MIT
