# Contributing

Keep changes focused and review skill instructions for clarity, grammar, and consistency with their agent metadata.

## Commit messages

Use Conventional Commits:

```text
<type>(<scope>): <description>
```

- `type`: use `feat` for new skills or capabilities, `fix` for corrections, `docs` for documentation, and `chore` for maintenance.
- `scope`: use the skill name. Omit the scope for repository-wide changes.
- `description`: write a concise summary in English, starting with a lowercase imperative verb. Do not add a trailing period.

Examples:

```text
feat(grilling): add a shared understanding confirmation step
fix(grilling): correct grammar in clarification instructions
chore(ponytail): update from upstream
docs: document the commit message format
```

Keep each commit focused on one logical change. Use the body when the reason for a change is not clear from the subject.
