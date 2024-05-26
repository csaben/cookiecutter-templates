# {{ cookiecutter.project_name }}

{{ cookiecutter.description }}

## Installation

### Inside current `venv`

```bash
python -m pip install -e .
```

### Inside new `venv`
```bash
conda create -n {{ cookiecutter.package_name }} python=3.10
conda activate {{ cookiecutter.package_name }}
python -m pip install -e .
```


