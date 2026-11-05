# Authoring rules

- One skill per folder: `skills/<name>/SKILL.md`. `name` equals the folder name (lowercase, digits, hyphens, 64 characters max).
- Frontmatter uses the open Agent Skills fields only: `name`, `description`, and optionally `license`, `compatibility`, `metadata`.
- Quote `description`. State what the skill does and when to use it, with trigger words first. 1024 characters max.
- Keep `SKILL.md` under 500 lines. Put detail in `references/`, helpers in `scripts/`, templates in `assets/`, one level deep.
- New work starts in `_incubating/`. Retired skills move to `_deprecated/` with a note in its README.
- Update the README skill index and `CHANGELOG.md` with every change to `skills/`.
