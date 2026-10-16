---
name: using-superpowers
description: Use at the start of a conversation - explains how superpowers skills are found and when to invoke one
---

<SUBAGENT-STOP>
If you were dispatched as a subagent to execute a specific task, ignore this skill.
</SUBAGENT-STOP>

# Using superpowers skills

Superpowers skills hold workflows that have worked: brainstorming before building, test-driven
development, systematic debugging, verification before claiming success, writing plans and
skills. They help when a task matches them; on a task they do not match, they only cost time.

## When to invoke a skill

Before starting a task, look at the skills listed for this session. When a skill's description
matches the task in front of you, invoke it with the Skill tool and follow it. Read its current
version rather than recalling it, because skills change between versions.

A question, an explanation, or an edit whose result is fully specified (a rename, a version
bump, a one-line config, a given wording) needs no skill: answer it or do it. Writing new
behavior, even one small function, is not such an edit.

When several skills apply, start with the one that sets the approach (brainstorming,
systematic-debugging), then the ones that carry it out. When you invoke one, say in a line which
one and why. If it turns out not to fit, say so and go on without it.

## Platform Adaptation

If your harness appears here, read its reference file for special instructions:

- Claude Code: `references/claude-code-tools.md`
- Codex: `references/codex-tools.md`
- Pi: `references/pi-tools.md`
- Antigravity: `references/antigravity-tools.md`
- Hermes Agent: `references/hermes-tools.md`
- Muse: `references/muse-tools.md`

## User Instructions

User instructions (CLAUDE.md, AGENTS.md, GEMINI.md, direct requests) take precedence over
skills, which in turn take precedence over default behavior. When a skill conflicts with the
user's instructions, follow the user and mention the conflict.
