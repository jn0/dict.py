[![](https://img.shields.io/pypi/pyversions/dict.svg?maxAge=86400)](https://pypi.org/pypi/dict/)
[![](https://img.shields.io/pypi/v/dict.svg?maxAge=86400)](https://pypi.org/pypi/dict/)
[![](https://img.shields.io/badge/libraries.io-dict-green.svg)](https://libraries.io/pypi/dict)

[![CodeFactor](https://www.codefactor.io/repository/github/looking-for-a-job/dict.py/badge)](https://www.codefactor.io/repository/github/looking-for-a-job/dict.py)
[![CodeClimate](https://codeclimate.com/github/looking-for-a-job/dict.py/badges/gpa.svg)](https://codeclimate.com/github/looking-for-a-job/dict.py)
[![Scrutinizer](https://scrutinizer-ci.com/g/looking-for-a-job/dict.py/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/looking-for-a-job/dict.py/)
[![BetterCodeHub](https://bettercodehub.com/edge/badge/looking-for-a-job/dict.py?branch=master)](https://bettercodehub.com/results/looking-for-a-job/dict.py)
[![Sonarcloud](https://sonarcloud.io/api/project_badges/measure?project=dict.py&metric=code_smells)](https://sonarcloud.io/dashboard?id=dict.py)

[![Codecov](https://codecov.io/gh/looking-for-a-job/dict.py/branch/master/graph/badge.svg)](https://codecov.io/gh/looking-for-a-job/dict.py)
[![CircleCI](https://circleci.com/gh/looking-for-a-job/dict.py/tree/master.svg?style=svg)](https://circleci.com/gh/looking-for-a-job/dict.py/tree/master)
[![Scrutinizer](https://scrutinizer-ci.com/g/looking-for-a-job/dict.py/badges/build.png?b=master)](https://scrutinizer-ci.com/g/looking-for-a-job/dict.py/)
[![Semaphore CI](https://semaphoreci.com/api/v1/looking-for-a-job/dict-py/branches/master/shields_badge.svg)](https://semaphoreci.com/looking-for-a-job/dict-py)
[![Travis](https://api.travis-ci.org/looking-for-a-job/dict.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/dict.py/)

### Install
```bash
[sudo] pip install dict
```

### Features

*	**attribute-style access**
* 	**None** instead of **KeyError**
* 	safe **remove**
* 	jQuery like **methods chaining**

### Usage
```python
>>> from dict import dict
```

### Examples
```python
>>> dict(k="v")["k"]
"v"

>>>  dict(k="v").k
"v"

>>> dict(k="v")["not_existing"]
None

>>> dict(k="v").not_existing
None

>>> dict(k="v").get("K",i=True) # case insensitive
```

### Sources
+   [`dict.dict(dict)`](https://github.com/looking-for-a-job/dict.py/blob/master/dict/__init__.py)