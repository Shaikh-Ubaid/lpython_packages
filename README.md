# LPython Packages

This is a repository to hold source code of packages built for the [LPython](https://github.com/lcompilers/lpython) compiler. Each individual package has its own **LICENSE** file.

Currently, we have the following packages:
- **lpynn:** A basic neural networks python package
- **lpdraw:** A simple python drawing package
- **lptypes:** Package for adding type information to python code
- **nrp:** A package for root computation of mathematical functions

# Build instructions

- One can build the packages using `python3 -m build` (please note that on needs to have `build` installed, one can install it via `python3 -m pip install --upgrade build`).
- One can install the built package locally using `python3 -m pip install -e .`

**Note:** The above commands are to be executed from the root directory of the particular project
