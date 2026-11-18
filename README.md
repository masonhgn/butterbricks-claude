# Butterbricks for Claude

A tutor for [Butterbricks](https://butterbricks.org), the interview-prep course that teaches algorithm patterns one
small idea at a time.

- **skills/butterbricks-tutor**: how to tutor with the course: hints, not answers; the five-step sequence (worked
  example, twin, practice, variation, stretch); the named mistakes each hidden test catches. Plus mock interviews and
  pattern-recognition drills.
- **.mcp.json**: the Butterbricks connector, `https://butterbricks.org/mcp`.
- **commands/**: `/butterbricks:interview` and `/butterbricks:drill`.

## Install in Claude Code

```
/plugin marketplace add masonhgn/butterbricks-claude
/plugin install butterbricks@butterbricks
```

## On claude.ai or the desktop app

Add `https://butterbricks.org/mcp` as a custom connector, and upload the skill
([butterbricks-tutor.zip](https://butterbricks.org/claude/butterbricks-tutor.zip)). Details:
https://butterbricks.org/claude/
