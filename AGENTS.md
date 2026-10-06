# AGENTS.md

- 所有的回應都使用繁體中文。
- 專案所使用的程式語言為 Python。
- 使用 conda 管理 Python 套件，環境名稱為 `iem_python`；不要使用 `pip`、`venv` 或其他環境。
- 執行與驗證一律使用 `conda run -n iem_python python <file>.py`；安裝套件使用 `conda install -n iem_python <pkg>`。

- Greenfield repo: only `README.md` + Python `.gitignore` exist. No source, manifests, tests, CI, or lint config yet.
- Course codebase for 115-1 computer programming. Expect small standalone Python scripts/exercises, not a packaged app or monorepo.
- Do not assume a toolchain: no `pyproject.toml`, `requirements*.txt`, `pytest.ini`, `tox.ini`, `Makefile`, or workflows to trust. Verify with `ls` before running build/test/lint commands.
- Respect `.gitignore`: `__pycache__/`, `.venv/`, `venv/`, `.pytest_cache/`, `.ruff_cache/` etc. are ignored. Never commit virtualenvs or bytecode.
