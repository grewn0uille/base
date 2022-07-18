```
git clone https://github.com/grewn0uille/base.git

cd base

python -m venv venv

venv/bin/pip install ".[test]"

venv/bin/pytest

venv/bin/pytest --cov
```
