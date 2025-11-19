Utra-strict Python project template for Qoder
==============================================

Ultra-strict Python project template using uv, ruff, and basedpyright.

# Toolbox

- Python: 3.12+
- Dependency manager: [uv](https://docs.astral.sh/uv/)
- Type checker: [basedpyright](https://docs.basedpyright.com/latest/) (strict mode)
- Linter/formatter: [ruff](https://docs.astral.sh/ruff/) (with many plugins enabled)
- Config & env: python-dotenv, typing-extensions
- Data validation: [pydantic](https://docs.pydantic.dev/latest/)>=2
- Task runner: [poethepoet](https://github.com/nat-n/poethepoet) (format, check, metrics, etc.)
- Code quality tools: [radon](https://pypi.org/project/radon/), [skylos](https://github.com/duriantaco/skylos)
- Testing & coverage: pytest + coverage (80% minimum by default)

# Tasks 

Please use `poe task_name` or `uv run poe task_name` to run tasks.

* format: formats code, fixes issues, and type checks
* lint-unsafe: Lint with unsafe fixes enabled (more aggressive)
* quality: Full quality check: format, lint, type check, and metrics
* metrics: Check code quality: dead code, complexity, and maintainability
* lint: Only linting, no type checking
* check: Lint and type check without fixing

# References

* basedpyright Configuration: https://docs.basedpyright.com/v1.20.0/configuration/config-files/
* Ruff Rules: https://docs.astral.sh/ruff/rules/
* [PyStrict-strict-python](https://github.com/Ranteck/PyStrict-strict-python): Ultra-strict Python project template
  using uv, ruff, and basedpyright, inspired by TypeScript’s --strict mode.
* [Qoder](https://qoder.com/): Agentic Coding Platform for Real Software
