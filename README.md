Please see the upstream Satellite repo in [codeberg](https://codeberg.org/tpikonen/satellite).

To refresh the python module dependencies, run:

```
flatpak-pip-generator -o python3-requirements.json --pyproject-file upstream-pyproject.toml --ignore-pkg pygobject
```
