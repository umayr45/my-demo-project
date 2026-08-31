# Repository Git standards
- Branch format: `feature/<WORK-ITEM-ID>-<short-kebab-case-title>`.
- WIP commit format: `wip(<WORK-ITEM-ID>): <short-progress-summary>`.
- Default base branch is `main` unless explicitly supplied.
- Use fast-forward-only pulls.
- Require human approval before create, push, stage, or commit.
- Stage only reviewed files.
- Never expose or commit credentials, tokens, private keys, `.env` files, generated binaries, or build output.
- Never force-push, reset, amend, merge, rebase, or delete branches.
