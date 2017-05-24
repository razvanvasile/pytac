[![Build Status](https://travis-ci.org/simkimsia/UtilityBehaviors.png)](https://travis-ci.org/simkimsia/UtilityBehaviors) [![Coverage Status](https://coveralls.io/repos/github/willrogers/pytac/badge.svg?branch=master)](https://coveralls.io/github/willrogers/pytac?branch=master) [![Health](https://landscape.io/github/willrogers/pytac/master/landscape.svg?style=flat)](https://landscape.io/github/willrogers/pytac/) [![Documentation Status](https://readthedocs.org/projects/pytac/badge/?version=latest)](http://pytac.readthedocs.io/en/latest/?badge=latest)

Python Toolkit for Accelerator Controls (Pytac) is a Python library intended to make it easy to work with particle accelerators.

## Testing

It is simplest to work with a virtualenv.  Then:

* `pip install -r requirements/local.txt`
* `export PYTHONPATH=.`
* `py.test test`

To see a coverage report:

* `py.test --cov=pytac test`

To build documentation correctly:

Change current directory to docs
* `sphinx-build -b html -E . _build/html`
The documentation is build inside _build/html
