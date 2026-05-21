# Project Rules

## Git

- Commit messages must be concise, one-line, in Chinese. Describe what changed in 20 characters or fewer. Format: `type: 简短描述` (e.g. `feat: 添加英文版`)
- Never write long bullet-point commit messages. Never include implementation details in commit messages.
- Before committing, always check `git status` and `git diff` to verify what will be committed.
- NEVER commit unless the user explicitly asks. NEVER amend commits unless asked.
- After amending, push with `--force-with-lease`.
