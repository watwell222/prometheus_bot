# AI Agent Context

Universal context for any AI agent. For Claude Code specifics see [`CLAUDE.md`](CLAUDE.md).

## What this repo is

<!-- TODO: 2-3 предложения о роли этого репо в экосистеме watwell222 -->

## Organization-wide knowledge base

This repo lives in the **watwell222** organization. The central KB is:
<https://github.com/watwell222/ww-knowledge-base>

Pull it locally for architecture docs + sibling service sources:

```bash
gh repo clone watwell222/ww-knowledge-base /tmp/ww-kb
git -C /tmp/ww-kb submodule update --init --recursive
```

## Key conventions

<!-- TODO: 3-5 самых важных соглашений, без знания которых сломаешь вещи -->

## Do not touch

- `.env*`, `secrets/`, `*.key`, `*.pem` — credentials
- Archived branches
- <!-- TODO: специфичные для этого репо "горячие" пути -->

## Useful commands

<!-- TODO: повторно-используемые команды для работы в этом репо -->
