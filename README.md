# Python 2 Conan Package

Provides a conan package for Python 2 (https://github.com/python/cpython).

## How-to

Export the package to a user/channel combination:
```
conan export <user>/<channel>
```

Build the package:
```
conan install python2/2.7.13@<user>/<channel> --build -g virtualenv
```

Activate the package:
```
source ./activate.sh
```

Verify that python2.7 points to the correct path:
```
which python2.7
echo $PYTHONPATH
```
