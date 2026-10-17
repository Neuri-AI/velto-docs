# Velto CLI configuration documentation — expanded edition

This bundle **continues** the previous `velto-cli-editorial-revision.zip` instead of replacing the documentation with unrelated tutorials.

## Sources

- `Neuri-AI/Velto-CLI` `release`: `README.md`, `docs/configuration.md`; previously checked parser, command modules and `pyproject.toml`.
- `Neuri-AI/qyro` `release`: `qyro/adapters/settings/json_settings.py`, `qyro/client/velto_context.py`, `qyro/container.py`, `qyro/adapters/telemetry/sentry_hook.py`, `qyro/adapters/telemetry/console_hook.py`, `qyro/adapters/resources/protected_bundle.py`, `qyro/adapters/resources/filesystem_resources.py`.
- User-provided generated/project JSON snapshots: `base.json`, `windows.json`, `linux.json`, `mac.json`, `release.json`.
- Prior Qyro documentation uploaded by user used for background only, not current command naming.

## Files changed

- `cli/configuration-files.mdx`: extensive field-level reference and five exact supplied JSON examples.
- `cli/telemetry.mdx`: verified flat `sentry_dsn` contract and exception-hook selection.
- `cli/protected-resources.mdx`: build/Engine mechanism distinction and integrity mechanism.
- `cli/build-and-freeze.mdx`, `cli/bundle-and-sign.mdx`, `cli/secrets-and-protection.mdx`, `cli/overview.mdx`: relevant configuration explanations, links and caveats.
- `runtime/settings-and-configuration.mdx`: runtime-specific settings implementation and precedence.
- `docs.json`: preserved from the preceding reviewed ZIP.

## Verification limitations

Sources were inspected statically from the named `release` branches; commands and frozen artifacts were not integration-tested. The user-provided Qyro Settings Builder URL was not reachable for direct live UI inspection here, so its exact controls and form schema were not asserted. Repository READMEs confirm the general external editor/export workflow.

**Import paths and instructions are for Velto CLI (`velto`), not the legacy `qyro` console command.**
