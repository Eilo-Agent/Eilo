# Implementation Mapping

The `src/eilo/` package and `tests/` directory are the reference implementation mapped into the Eilo handbook repository from the `Tmp-Eilo` project.

## Source and hardening

- Baseline implementation source: `hakuramasam/Tmp-Eilo` `main`
- Hardening source: `fix/memory-and-tool-registry`
- Integrated components: configuration, OpenAI-compatible client, bounded agent loop, approval manager, SQLite memory, tool registry, built-in safe tools, CLI, and tests
- CI: GitHub Actions workflow in `.github/workflows/ci.yml`

## Documentation policy

The detailed root `AGENTS.md` and the existing handbook documentation remain canonical for organization-level operating rules. Shared documentation was not blindly replaced; only implementation-specific files and documentation paths absent from the handbook were added.
