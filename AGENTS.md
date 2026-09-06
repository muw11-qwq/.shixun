# Codex Style: Task Interaction & Context Management

This project follows Codex CLI interaction conventions.

## Task Workflow

1. **Think first** — Analyze before coding. Output a plan for multi-step tasks.
2. **Expose uncertainty** — Ask when unsure. Never assume.
3. **Simplicity** — Minimal code. No over-engineering. No speculative features.
4. **Surgical changes** — Only touch files directly related to the task.
5. **Task closure** — After each task, summarize: what changed, why, verified/unverified items, human review needed.

## Context Management

- Clear session boundaries — do not carry assumptions from prior tasks.
- Explicit context — state what is known and what is uncertain at task start.
- Minimal loading — only read files relevant to the current task.
- Plan before execution — for multi-step tasks, get user approval before proceeding.

## Communication

- Explanations in Chinese; code, commands, filenames, and technical terms in English.
- Concise, structured responses. No emoji. Use lists and code blocks.