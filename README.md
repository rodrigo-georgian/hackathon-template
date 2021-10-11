# python-template
Personal cookiecutter template for Python projects.

## Included
- Package management with Poetry
- pre-commit hooks
- Liting with flake8, black, isort
- Type Checking with mypy
- Tests with pytest, pytest-cov
- CI with Github Actions

## Usage
Install [cookiecutter](https://cookiecutter.readthedocs.io/en/1.7.2/) with [pipx](https://github.com/pypa/pipx)
```
pipx install cookiecutter
```

Set up a new project with this template
```
cookiecutter https://github.com/kennethcheo/python-template.git
cookiecutter git+ssh://git@github.com/kennethcheo/python-template.git
```

### Todo
- Configure dependence of `pre-commit` hooks versions to `poetry`
- Consider `[nox](https://nox.thea.codes/en/stable/)` for automating test suite
- Add Sphinx documentation generation when necessary
- Add Build workflow
