# Documentation progress

## Current status

- Canonical Mintlify root: `public/`.
- Current increment: normalized information architecture, façade-first imports, PSX Markup curriculum, and example/test structure.
- Product changes: none.

## Verification ledger

| Area | Evidence | Status |
| --- | --- | --- |
| Façade exports | `velto/velto/__init__.py` and namespace `__all__` lists | inventoried |
| PSX Markup | parser, compiler, transform, expressive runtime, markup tests | page set created; examples require per-page execution |
| Boilerplate | `main.py` imports `velto`; metadata omits it | blocking generated-project certification |
| Mintlify | `package.json` pins Mint 4.2.988 | validation pending dependency installation |

## Next actions

1. Run the public API inventory check and fill evidence links for each completed reference.
2. Execute FocusBoard stages through Headless and record results in `example-manifest.json`.
3. Resolve the boilerplate metadata discrepancy before certifying CLI-generated projects.
