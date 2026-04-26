# Changelog

## Unreleased

### Surface sync

- `tile.json` adds `entrypoint: README.md` per `jbaruch/coding-policy: context-artifacts`.
- `CHANGELOG.md` introduced (none existed previously). Maintained going forward as required by the policy.
- The `docs: docs/index.md` field is retained for now alongside the new `entrypoint`. Per the policy, "Don't add a separate `docs` field — keep all documentation in the entrypoint to avoid duplicate tables that drift out of sync." A follow-up PR should fold `docs/index.md` content into `README.md` and drop the `docs` field.
- Steering files live under `steering/` rather than the policy's standard `rules/`. That's a pre-existing structural choice; not changed here.
