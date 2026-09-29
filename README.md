# my-skills

Skills for coding agents in this repository. Canonical tree: `.agents/skills/<name>/SKILL.md`.

This catalog does not commit client install copies under `.claude/skills`, `.devin/skills`, or `.cursor/skills`. Those paths are gitignored.

## Skills

| Skill | Use when |
|-------|----------|
| [superdesign-inspo](.agents/skills/superdesign-inspo/SKILL.md) | Design or redesign a UI from real shipped websites when both Inspo and Superdesign are available. Returns a canvas draft and an implementation prompt. Does not write product code. |

## Where clients read skills

Cursor reads `.agents/skills` when this repository is the workspace. Codex and hosted Devin use the same path. Claude Code does not; see [CLAUDE.md](CLAUDE.md).

## License

MIT. See [LICENSE](LICENSE).
