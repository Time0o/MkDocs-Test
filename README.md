```
uv venv
source .venv/bin/activate
uv pip install mkdocs-material mkdocstrings-python
PYTHONPATH=src uv run mkdocs build
open site/index.html
```
