# Contributing — Issues only

This repository tracks **issues and discussions only**. Code changes happen in private repositories; reference issues here for traceability.

## Filing an issue

1. Search [existing issues](../../issues) to avoid duplicates.
2. Use a template: **Bug** or **Feature**.
3. Pick the closest `area:*` label (maintainers may adjust).
4. Write titles as: `[area] short summary` — e.g. `[clip] WeChat clipboard format support`.

## Commit message references

Format (Conventional Commits + issue ref):

```text
<type>(<scope>): <subject> QuickerHub/cea-action-issues#<N>
```

Examples:

```text
fix(qkrpc): preserve subprogram inputParams QuickerHub/cea-action-issues#8
feat(clip): WeChat text+image clipboard adapter QuickerHub/cea-action-issues#12
```

In PR descriptions (auto-close on merge):

```text
Fixes QuickerHub/cea-action-issues#12
```

Works from private repos in the same GitHub organization.

## Scopes (suggested)

| Scope | Maps to |
|-------|---------|
| `clip` | Clipboard apps |
| `packages/<name>` | DLL package |
| `qkrpc` | quicker-rpc submodule |
| `actions` | Quicker action/subprogram |
| `userscripts` | Tampermonkey scripts |

## What not to post

- API keys, passwords, tokens
- Private file paths or internal hostnames
- Unredacted user data
