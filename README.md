# Butterbricks for AI assistants

The source of the plugin published at https://github.com/masonhgn/butterbricks-claude: edit it here, then run
`tools/publish_claude_plugin.sh`. The site's build also zips the skill (web/ai/).

A tutor for [Butterbricks](https://butterbricks.org): algorithm patterns one small idea at a time.

- **skills/butterbricks-tutor**: how to tutor with the course (hints, not answers; the five-step sequence; the named
  mistakes each test catches), plus mock interviews and recognition drills.
- **.mcp.json**: connects to the course at `https://butterbricks.org/mcp` (read-only, free content).
- **commands/**: `/butterbricks:interview` and `/butterbricks:drill` in Claude Code.

Install in Claude Code:

```
/plugin marketplace add masonhgn/butterbricks-claude
/plugin install butterbricks@butterbricks
```

Install in Gemini CLI (`gemini-extension.json`: the same connector, with the skill as the context file):

```
gemini extensions install https://github.com/masonhgn/butterbricks-claude
```

Claude, ChatGPT, the Gemini app, Antigravity, Codex and anything else that takes remote MCP servers: connect
`https://butterbricks.org/mcp` and sign in. The skill is at https://butterbricks.org/ai/butterbricks-tutor.zip.
Step by step: https://butterbricks.org/ai/
