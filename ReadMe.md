﻿Python scripting interface for Comsol Multiphysics®

[Comsol][comsol] is a commercial software application that is widely
used in science and industry alike for research and development. It
excels in modeling almost any (multi-)physics problems by solving the
governing set of partial differential equations via the finite-element
method. It comes with a modern graphical user interface to set up
simulation models and can be scripted from Matlab® or via its native
Java API.

This library brings the dearly missing power of Python to the world
of Comsol — at least on Windows (for now). It leverages the universal
Python-to-Java bridge provided by [JPype][jpype] to access the native
API, and wraps it in a layer of pythonic ease-of-use. The Python
wrapper only covers common scripting tasks, such as loading a model
from a file, modifying some parameters, running the simulation, to
then evaluate the results. Though the full functionality is available
to those who dig down to the Java layer underneath.

Comsol models are marked by their `.mph` file extension, which stands
for multiphysics. Hence the name of this library. It is open-source
and in no way associated with Comsol Inc., the company that develops
and licenses the simulation software.

Find the [full documentation on Read-the-Docs][docs].


[comsol]: https://www.comsol.com
[jpype]:  https://pypi.org/project/JPype1
[docs]:   https://mph.readthedocs.io

[![version](https://img.shields.io/pypi/v/mph.svg)](https://pypi.python.org/pypi/mph)
[![downloads](https://pepy.tech/badge/mph)](https://pepy.tech/project/mph)
[![license](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![documentation](https://readthedocs.org/projects/mph/badge/?version=latest)](https://mph.readthedocs.io/en/latest/?badge=latest)