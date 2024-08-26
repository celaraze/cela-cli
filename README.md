# Cela Client

A Command-line client for [Cela](https://github.com/celaraze/cela.git).

## Quick Start

```shell
pip install cela
cela connect http://localhost:8000
cela login admin admin
cela todo list
```

## Publish By Github Actions

```shell
git tag v0.0.5-alpha
git push origin v0.0.5-alpha
# or
# git push origin -tags
```

## Publish Manually

```shell
pip install twine
python setup.py bdist_wheel --universal
twine upload dist/*
```