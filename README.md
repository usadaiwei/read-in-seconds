# read-in-seconds

An agent skill that makes reports readable in seconds: **verdict first, what you
must do next, a few trust-critical facts, stop.** Shortens the writing, never the
checking. ADHD-friendly by design.

让 agent 的汇报几秒读完：结论先行 → 需要你做的 → 少量关键事实 → 结束。只省文字，不省核查。

## Install

Copy `SKILL.md` into a folder named `read-in-seconds` under your host's skill
directory (Claude Code: `~/.claude/skills/`, Codex: `~/.agents/skills/`).
For always-on behavior, also add one line to your global instructions, e.g.
"All reports follow the read-in-seconds skill."

MIT licensed.
