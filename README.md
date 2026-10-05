# ai-skill-commit

Write and validate Conventional-Commits messages in a house style, matching the repo's own history. Use when committing, splitting work into commits, or checking a commit message.

## Install

### Any agent

The [`skills`](https://github.com/vercel-labs/skills) CLI installs into Codex, OpenCode, Gemini CLI, Cursor, Copilot, Claude Code, and 70+ other agents:

```bash
npx skills add guillempuche/ai-skill-commit
```

### Claude Code

```bash
# Add marketplace (uses repo slug)
/plugin marketplace add guillempuche/ai-skill-commit

# Install plugin (plugin name is topic-only)
/plugin install commit@guillempuche-ai-skill-commit
```

### Gemini CLI

```bash
gemini skills install https://github.com/guillempuche/ai-skill-commit.git --path skills/commit
```

### Manual

Copy `skills/commit` into `.agents/skills/` (Codex, Gemini CLI, OpenCode, Mastra Code, Cursor, Copilot) or `.claude/skills/` (Claude Code).

## Part of AI Standards

This skill is also available in the [ai-standards](https://github.com/guillempuche/ai-standards) bundle with other skills and agents.

## License

MIT
