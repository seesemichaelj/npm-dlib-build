[![Build Status](https://travis-ci.org/seesemichaelj/npm-dlib-build-cuda.svg?branch=master)](http://travis-ci.org/seesemichaelj/npm-dlib-build-cuda)
[![Build status](https://ci.appveyor.com/api/projects/status/hrn2w7mkyf912c5t/branch/master?svg=true)](https://ci.appveyor.com/project/seesemichaelj/npm-dlib-build-cuda/branch/master)

A simple script to auto build dlib via npm, which includes CUDA installation.

# IT'S A FORK! </ackbar>
This repository is a fork of the normal [dlib-build](https://github.com/justadudewhohacks/npm-dlib-build) which adds CUDA support.

# Install
```
npm install dlib-build-cuda
```

## With OpenBLAS on windows
```
set OPENBLAS_LIB_DIR=<path to libopenblas.lib>
```

## Requirements
- cmake

### Windows
- VS2017 build tools (not Visual Studio 2017) -> https://www.visualstudio.com/de/downloads/
