# Documentation decisions

- Public documentation is written in English and published from `public/`.
- `velto.*` is the canonical import family for application documentation.
- Original `psx`, `pydux`, and `qyro` imports remain valid and are covered by compatibility material.
- PSX Markup runtime templates and statically transformed component markup are documented separately.
- Examples live in `velto/examples/documentation/`; Mintlify pages link to them and never claim that an isolated snippet is a complete application.
- A page must state its prerequisites and verification level: static, Headless, native, or conceptual.
