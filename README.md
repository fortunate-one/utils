# Tils

Collection of Python utility functions

## Deployment to PyPi

Add credential to `~/.pypirc` file.

```bash
echo "[pypi]
username = __token__
password = $PIPY_TOKEN" >> ~/.pypirc
```

Build the package and then upload it to PyPi.

```bash
python -m build
python -m twine upload --repository testpypi dist/*
```
