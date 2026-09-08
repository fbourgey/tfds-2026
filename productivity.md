# ⏱️ Productivity Tools

- [Python documentation](https://docs.python.org/3/)

- Python libraries: [NumPy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), [SciPy](https://scipy.org/), [statsmodels](https://www.statsmodels.org/), [scikit-learn](https://scikit-learn.org/), and [Matplotlib](https://matplotlib.org/).

- Learn some [Markdown](https://www.markdownguide.org/) (for README files, [Jupyter notebooks](https://jupyter.org/), etc.).

- Learn the basics of the CLI (Command Line Interface). Command-line workflows are easier to reproduce and automate, while GUI tools remain useful for exploration and debugging.

- Use Jupyter notebooks for interactive coding, visualization, and documentation. Before sharing a notebook, restart the kernel and run all cells from top to bottom. Move reusable code into `.py` files.

- Use version control with [Git](https://git-scm.com/) and [GitHub](https://github.com/) for collaboration and code management. Include a README explaining how to reproduce your results, and never commit credentials or API keys.

- [VS Code](https://code.visualstudio.com/) for efficient coding and debugging (extensions, Copilot, shortcuts):
  - Customize VS Code settings (see [here](https://code.visualstudio.com/docs/getstarted/settings)).
  - Use keyboard shortcuts (see [here](https://code.visualstudio.com/docs/getstarted/keybindings)).
  - Install useful extensions (see [here](https://code.visualstudio.com/docs/editor/extension-gallery)).

- Leverage AI tools (e.g., Claude code, Codex, GitHub Copilot, etc.) to assist with coding, debugging, and learning. Always read, run, and test generated code, and verify important claims against reliable sources.

- Use virtual environments to isolate project dependencies. For new projects, consider [`uv`](https://docs.astral.sh/uv/) with a `pyproject.toml` and a committed `uv.lock` file. [Conda](https://docs.conda.io/en/latest/) remains useful for projects with specialized non-Python dependencies.

- [ruff](https://docs.astral.sh/ruff/): an extremely fast Python linter, formatter, and code fixer.

- [pytest](https://docs.pytest.org/): test important calculations, data transformations, and edge cases. Use approximate comparisons for floating-point results.

- Write docstrings for public functions and classes (see [PEP 257](https://peps.python.org/pep-0257/)).
  - I use NumPy-style docstrings (see [here](https://numpydoc.readthedocs.io/en/latest/format.html)).
  - Use type hints for function arguments and return types (see [Python typing documentation](https://docs.python.org/3/library/typing.html)).

- Bonus:
  - Contribute to open source projects on GitHub.
    - Examples: [pandas](https://github.com/pandas-dev/pandas), [scikit-learn](https://github.com/scikit-learn/scikit-learn), [SciPy](https://github.com/scipy/scipy).
  - Write technical blogs or tutorials.
