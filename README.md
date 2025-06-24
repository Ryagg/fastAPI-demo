# Fast API Project

Following the official [FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/) with a professional-grade dev setup including:

- 🐍 Python 3.12 (managed via `pyenv`)
- 📦 Poetry for dependency management
- 🎯 Pre-commit hooks (black, isort, trailing whitespace, etc.)
- 🔐 GPG-signed commits
- 🧪 VS Code + `.vscode/settings.json` + launch/debug config

## 🚀 Getting Started

```bash
poetry install
poetry shell
uvicorn main:app --reload
Copy .env.template to .env and update values as needed
