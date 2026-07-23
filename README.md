# CodeForge Hardware Store

Reusable, engine-agnostic Python cores, proven in the CodeForge MUD and poured here as a
standalone package. No game engine is required to use them.

Third-party dependencies: fastapi, pydantic, structlog.

## Cores (27)

- `codeforge_shelf.bulkhead`
- `codeforge_shelf.circuit_breaker`
- `codeforge_shelf.config`
- `codeforge_shelf.console`
- `codeforge_shelf.deadline`
- `codeforge_shelf.feature_flags`
- `codeforge_shelf.hashchain`
- `codeforge_shelf.health`
- `codeforge_shelf.hourglass`
- `codeforge_shelf.loader_cache`
- `codeforge_shelf.observability`
- `codeforge_shelf.plugin_registry`
- `codeforge_shelf.record_loader`
- `codeforge_shelf.reporting`
- `codeforge_shelf.repository`
- `codeforge_shelf.retry`
- `codeforge_shelf.sanitizer`
- `codeforge_shelf.signal_bus`
- `codeforge_shelf.statemachine`
- `codeforge_shelf.stats`
- `codeforge_shelf.stream_framer`
- `codeforge_shelf.telnet_codec`
- `codeforge_shelf.test_evidence`
- `codeforge_shelf.token_bucket`
- `codeforge_shelf.validation`
- `codeforge_shelf.weighted_table`
- `codeforge_shelf.workflow`

## Tests

25 test twins ship with the package and pass with no engine present (`pip install .[test] && pytest`).

2 core(s) keep their tests in the CodeForge repo -- those tests exercise the core against the live engine (integration): console, observability.
