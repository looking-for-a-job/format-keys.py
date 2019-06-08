<!--
https://pypi.org/project/readme-generator/
https://pypi.org/project/python-readme-generator/
-->

[![](https://img.shields.io/pypi/pyversions/format-keys.svg?longCache=True)](https://pypi.org/project/format-keys/)
[![](https://img.shields.io/pypi/v/format-keys.svg?maxAge=3600)](https://pypi.org/project/format-keys/)
[![Travis](https://api.travis-ci.org/looking-for-a-job/format-keys.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/format-keys.py/)

#### Installation
```bash
$ [sudo] pip install format-keys
```

#### Functions
function|`__doc__`
-|-
`format_keys.keys(string)` |return a list of format keys

#### Examples
```python
>>> import format_keys
>>> format_keys.keys("https://api.travis-ci.org/{fullname}.svg?branch={branch}")
['fullname', 'branch']
```

<p align="center">
    <a href="https://pypi.org/project/python-readme-generator/">python-readme-generator</a>
</p>