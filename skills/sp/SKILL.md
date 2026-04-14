---
name: sp
description: "Shortcut alias for /superplan. Break large features into milestones and tasks, track progress in git-committed markdown, and execute autonomously with /loop. Use when starting a multi-hour feature, complex refactor, or any task too large for a single session."
when_to_use: "create a plan, plan this feature, break this down, I need a structured approach, /sp, sp"
allowed-tools: Bash(git:* ls:* cat:*) Read Glob Grep Edit Write Agent Task
argument-hint: <description or ticket_id> | status | next <plan_file> [--yes] | review <plan_file>
---

This is a shortcut alias for `/superplan`. Read and follow the instructions in the `superplan` skill (installed alongside this one as `~/.claude/skills/superplan/SKILL.md`).

Execute exactly as if the user typed `/superplan` with the same arguments — same routing, same subcommands, same behavior.
