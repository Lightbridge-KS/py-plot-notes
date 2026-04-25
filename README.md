# Python Plotting Notes

> Notes on learning plotting in Python, including Matplotlib, Seaborn, and related visualization tools.

## Local Python environment

This book uses a project-local Python environment managed by `uv`.

```bash
uv sync
```

Start Jupyter Notebook from the project environment:

```bash
uv run jupyter notebook
```

Render the book through the same environment so Quarto can execute Python/Jupyter cells with the project dependencies:

```bash
uv run quarto render --execute
```

For a clean execution pass, especially after changing notebook kernels or dependencies:

```bash
uv run quarto render --execute --execute-daemon-restart
```
