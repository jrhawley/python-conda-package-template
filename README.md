# python-conda-package-template

Template for building Python packages that can be easily bundled as Anaconda packages, too

# Usage

To use this package, when creating the new repository for your project, select this project as the template.
Then, replace all occurrences of "PACKAGENAME", "URL", "GIT_URL", and other filler values in `setup.py` and `meta.yaml`.
Set version numbers as needed in `PACKAGENAME/__init__.py` and `meta.yaml`, and add your code where applicable.

# Building you package

## PyPI

```shell
python setup.py install
```

## Anaconda

```shell
conda build --python {PYTHON_VERSION} meta.yaml
```
