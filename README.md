# Tricks-FIX-BUG-in-Python
* How to fix: /usr/bin/python: bad interpreter: No such file or directory
=> ln -s /usr/local/bin/python /usr/bin/python

* How to fix: ERROR: Package 'setuptools' requires a different Python: 2.7.5 not in '>=3.5'
=> pip install --upgrade 'setuptools<45.0.0'
