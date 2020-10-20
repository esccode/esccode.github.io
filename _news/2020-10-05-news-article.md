---
layout: post
title: Python 3.9.0 is now available
tags: "news, python"

---




Python 3.9.0 is now available, and you can already test 3.10.0a1!
Oct. 5, 2020, 8:09 p.m.
On behalf of the Python development community and the Python 3.9 release team, I’m pleased to announce the availability of Python 3.9.0. Python 3.9.0 is the newest feature release of the Python language, and it contains many new features and optimizations. You can find [Python 3.9.0 here:](https://pythoninsider.blogspot.com/2020/10/python-390-is-now-available-and-you-can.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+PythonInsider+%28Python+Insider%29 ).

## What’s New In Python 3.9
### Dictionary Merge & Update Operator
```
Merge (|) and update (|=) operators have been added to the built-in dict class. Those complement the existing dict.update and {**d1, **d2} methods of merging dictionaries.

Example:

>>>
>>> x = {"key1": "value1 from x", "key2": "value2 from x"}
>>> y = {"key2": "value2 from y", "key3": "value3 from y"}
>>> x | y
{'key1': 'value1 from x', 'key2': 'value2 from y', 'key3': 'value3 from y'}
>>> y | x
{'key2': 'value2 from x', 'key3': 'value3 from y', 'key1': 'value1 from x'
```

## New Modules
### zoneinfo

```

>>> from zoneinfo import ZoneInfo
>>> from datetime import datetime, timedelta

>>> # Daylight saving time
>>> dt = datetime(2020, 10, 31, 12, tzinfo=ZoneInfo("America/Los_Angeles"))
>>> print(dt)
2020-10-31 12:00:00-07:00
>>> dt.tzname()
'PDT'

>>> # Standard time
>>> dt += timedelta(days=7)
>>> print(dt)
2020-11-07 12:00:00-08:00
>>> print(dt.tzname())
PST
```