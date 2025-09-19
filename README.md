# cdsw-python
Python Bibliotheken für das CoderDojo Schöneweide

## Installation

```sh
python -m venv venv
. venv/bin/activate
pip install -e .
```

## Neue Version veröffentlichen

Version in `pyproject.toml` ändern.

```sh
python -m build
twine upload dist/*
```
