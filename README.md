# test-app

[![Release](https://img.shields.io/github/v/release/bhjelmar/test-app)](https://img.shields.io/github/v/release/bhjelmar/test-app)
[![Build status](https://img.shields.io/github/workflow/status/bhjelmar/test-app/merge-to-main)](https://img.shields.io/github/workflow/status/bhjelmar/test-app/merge-to-main)
[![Commit activity](https://img.shields.io/github/commit-activity/m/bhjelmar/test-app)](https://img.shields.io/github/commit-activity/m/bhjelmar/test-app)
[![Docs](https://img.shields.io/badge/docs-gh--pages-blue)](https://bhjelmar.github.io/test-app/)
[![Code style with black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Imports with isort](https://img.shields.io/badge/%20imports-isort-%231674b1)](https://pycqa.github.io/isort/)
[![License](https://img.shields.io/github/license/bhjelmar/test-app)](https://img.shields.io/github/license/bhjelmar/test-app)

This is a template repository for Python projects that use Poetry for their dependency management.

- **Github repository**: <https://github.com/bhjelmar/test-app/>
- **Documentation** <https://bhjelmar.github.io/test-app/>

## Releasing a new version

- Create an API Token on [Pypi](https://pypi.org/).
- Add the API Token to your projects secrets with the name `PYPI_TOKEN` by visiting 
[this page](https://github.com/bhjelmar/test-app/settings/secrets/actions/new).
- Create a [new release](https://github.com/bhjelmar/test-app/releases/new) on Github. 
Create a new tag in the form ``*.*.*``.

For more details, see [here](https://fpgmaas.github.io/cookiecutter-poetry/releasing.html).

---

Repository initiated with [fpgmaas/cookiecutter-poetry](https://github.com/fpgmaas/cookiecutter-poetry).