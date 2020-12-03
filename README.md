<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/travis-env.svg?maxAge=3600)](https://pypi.org/project/travis-env/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/travis-env.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/travis-env.py/actions)

### Installation
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
# export TRAVIS_ENDPOINT="https://api.travis-ci.org"
```

#### Examples
```bash
$ python -m travis_env.set WEBHOOK_URL url
$ python -m travis_env.vars
WEBHOOK_URL
```

#### Related
+   [`travis-cron` - travis cron management](https://pypi.org/project/travis-cron/)
+   [`travis-env` - travis environment variables management](https://pypi.org/project/travis-env/)
+   [`travis-exec` - execute command for every travis repo](https://pypi.org/project/travis-exec/)
+   [`travis-generator` - `.travis.yml` generator](https://pypi.org/project/travis-generator/)
+   [`travis-image-status` - quickly get travis status from an image](https://pypi.org/project/travis-image-status/)

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
