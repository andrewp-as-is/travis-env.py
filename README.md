[![](https://img.shields.io/pypi/pyversions/travis-env.svg?longCache=True)](https://pypi.org/project/travis-env/)
[![](https://img.shields.io/pypi/v/travis-env.svg?maxAge=3600)](https://pypi.org/project/travis-env/)
[![Travis](https://api.travis-ci.org/looking-for-a-job/travis-env.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/travis-env.py/)

#### Install
```bash
$ [sudo] pip install travis-env
```

#### Features
+   add, get, delete Travis CI environment variables

#### Config
```bash
$ travis token
xxx
$ export TRAVIS_TOKEN="xxx"
```

#### Functions
function|`__doc__`
-|-
`travis_env.add(repo, var_name, var_value, public=False)`|add environment variable
`travis_env.clear(repo)`|clear all environment variables
`travis_env.delete(repo, var_name)`|delete environment variable
`travis_env.update(repo, **kwargs)`|update environment variable
`travis_env.vars(repo)`|

#### CLI
usage|`__doc__`
-|-
`python -m travis_env.clear repo`|clear all environment variables
`python -m travis_env.delete repo var_name ...`|delete environment variables by name
`python -m travis_env.set repo var_name var_value`|set environment variable
`python -m travis_env.vars repo`|print environment variable names

#### Examples
```bash
$ python -m travis_env.set WEBHOOK_URL url
$ python -m travis_env.vars
WEBHOOK_URL
```

<p align="center"><a href="https://pypi.org/project/readme-md/">readme-md</a> - README.md generator</p>