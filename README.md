# Tricks-FIX-BUG-in-Python

## How to fix: /usr/bin/python: bad interpreter: No such file or directory

### From Command Line 
```bash
ln -s /usr/local/bin/python /usr/bin/python
```

## How to fix: ERROR: Package 'setuptools' requires a different Python: 2.7.5 not in '>=3.5'
### From Command Line 
```bash
pip install --upgrade 'setuptools<45.0.0'
```

## Hown to Find full path of the Python interpreter?
### From Command Line
```bash
$ which python
/usr/bin/python

$ whereis python
python: /usr/bin/python /usr/bin/python3.4 /usr/lib/python2.7 /usr/lib/python3.4        /usr/include/python2.7 /usr/include/python3.4m /usr/share/man/man1/python.1.gz

$ which python3
/usr/bin/python3

$ command -v python
/usr/bin/python

$ type python
python is hashed (/usr/bin/python)
```

## How to set Python3 as default Python version on CentOS?
### From Command Line
```bash
$ sudo ln -fs /usr/bin/python3 /usr/bin/python
$ alias python="/usr/bin/python3.6"
```
