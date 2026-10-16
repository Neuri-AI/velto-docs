# Known discrepancies and blockers

## Generated Velto boilerplate is not reproducible yet

`velto-boilerplate/main.py` imports `velto`, but `velto-boilerplate/pyproject.toml` does not declare the `velto` distribution. The template also permits Python versions beyond Velto's declared `<3.14` range.

The probable product correction is to add the `velto` dependency while retaining the selected native binding, then align the template's Python range. This is a product and template change, so documentation must not make it without separate authorization. Until then, generated-project installation is documented as blocked and the manual examples are the reproducible path.

## CLI name

The installed local CLI command is `qyro`; there is no verified `velto` CLI command. Documentation uses `qyro init`, `qyro start`, `qyro build`, `qyro bundle`, and `qyro sign` only where the local implementation supports them.
