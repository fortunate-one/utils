# Tils

Collection of Python utility functions

## Deployment to PyPi

Need to first build the package and then upload it to PyPi.

```bash
python -m build
python -m twine upload --repository testpypi dist/*
```
