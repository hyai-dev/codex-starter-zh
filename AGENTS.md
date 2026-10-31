# AGENTS.md — project instructions template

> Replace this file with rules for **this** repository. Codex (and similar agents) may read it as standing guidance.
> Do not put API keys, passwords, session tokens, or customer data here.

## Project goal

- One sentence: what this repo is for.
- Out of scope: what the agent must not change.

## Working rules

1. Prefer small, reviewable diffs.
2. Run the project's existing checks before claiming done.
3. Never commit secrets; never print `.env` or credential files.
4. Ask before deleting data, force-pushing, or changing billing/auth config.

## Commands

```bash
# install / test / lint — fill in real commands for this repo
# npm test
# npm run lint
```

## Review checklist

- [ ] Change matches the requested task
- [ ] Tests or manual verification noted
- [ ] No secrets in the diff

