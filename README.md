# mFractal

[![pytest](https://github.com/lucasfr/mFractal/actions/workflows/python-package.yml/badge.svg)](https://github.com/lucasfr/mFractal/actions/workflows/python-package.yml)
[![codecov](https://codecov.io/gh/lucasfr/mFractal/branch/main/graph/badge.svg?token=EB7Z9AWZVN)](https://codecov.io/gh/lucasfr/mFractal)
![GitHub](https://img.shields.io/github/license/lucasfr/mFractal)
![PyPI](https://img.shields.io/pypi/v/mFractal?color=purple)
![PyVers](https://img.shields.io/badge/Python-v3.6_|_v3.7_|_v3.8_|_v3.9-blue)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4589625.svg)](https://doi.org/10.5281/zenodo.4589625)

This is a development version of a module for multifractal analyses in Python. It already includes a version of the Chhabra-Jensen method.

:warning: Please, use the following article for references of the Chhabra-Jensen function:

França, L.G.S., Miranda, J.G.V., Leite, M., Sharma, N.K., Walker, M.C., Lemieux, L. and Wang, Y., 2018. [Fractal and Multifractal Properties of Electrographic Recordings of Human Brain Activity: Towards its Use as a Signal Feature for Machine Learning in Clinical Applications](https://www.frontiersin.org/articles/10.3389/fphys.2018.01767/). Frontiers in Physiology, 9, p.1767. DOI: 10.3389/fphys.2018.01767

The code was developed based on the method described in:

Chhabra, A. & Jensen, R., 1989. [Direct determination of the f(α) singularity spectrum](http://link.aps.org/doi/10.1103/PhysRevA.40.5284). Physical Review Letters, 62(12), pp.1327–1330.

If you have any questions or suggestions, please [open an issue in the relevant tab](https://github.com/CoDe-Neuro/dynfc/issues). 

Please do not hesitate to suggest improvements to this module.

## Installation

The easiest way to install mFractal is via pip (PyPI) with the command below.

```
pip install mFractal
```

If you would like to specify a version use the following command to install version *0.0.1a1*, for example.

```
pip install mFractal==0.0.1a1
```

Alternatively one can clone this repository and add it to a project. For that use the following command.

```
git clone https://github.com/lucasfr/mFractal/
```

## LICENSE

This software is licensed under an MIT License.

Copyright (c) 2021 [Lucas G S França](https://www.lfranca.uk/), [Yujiang Wang](http://xaphire.de/), José G V Miranda.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
