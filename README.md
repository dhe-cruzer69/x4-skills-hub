# x4-skills-hub

**Verified AI agent skills registry and MCP skill contracts.**

Quality, security, and compatibility scoring for production skills. Ships with 5 seed skills ready for MCP registries.

## Seed Skills

1. `web-search` — constrained search tool
2. `code-review` — diff + evidence review
3. `repo-inventory` — fleet metadata collector
4. `sarif-report` — security findings emitter
5. `session-memory` — context compression helper

## Quick Start

```bash
pip install -e ".[dev]"
python -m x4_skills_hub.validate skills/
```

## License

Apache-2.0
