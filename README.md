# harness-engineering

## Jupyter Setup (uv)

Jupyter is configured as a development dependency in `pyproject.toml`.

### Install dependencies

```bash
uv sync
```

### Start JupyterLab

```bash
uv run jupyter lab
```

### Optional: Start classic notebook server

```bash
uv run jupyter notebook
```

### Open the starter notebook

Use:

- `notebook/safety.ipynb`

When opening the notebook in VS Code, select the Python interpreter from this project (`.venv`) as the kernel.
