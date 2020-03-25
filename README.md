# Install-PyQt5-in-Python-3-virtual-environment

It’s been a while since I last made something with PyQt, so I decided to check out what’s it like nowadays. I’m curious to see what’s new in Qt5 and how does it differ from Qt4. Qt5 also can run under python 3 so I figured to give it a try.

Fedora 21 comes with both python 2.7 and python 3.4, but the default version is 2.7, which means if PyQt5 is installed through the package manager, it will be installed against 2.7. As I’m not currently in the mood of bricking my laptop by changing the default python version, I decided to install PyQt5 in a python virtual environment. Btw, Fedora 22 should have python 3 by default.

In the code samples below, assume the working directory is always ~/pyqt.

# Create a virtual environment
virtualenv --python=python3.4 env
