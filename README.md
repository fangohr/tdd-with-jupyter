# Test driven development for Jupyter?

Some ideas of realising Test Driven Development (TDD) with the Jupyter
notebook, following discussion on the testing-in-python mailing list:
http://lists.idyll.org/pipermail/testing-in-python/2016-June/006770.html

## Directory `convert-to-py`

Example that converts a libary notebook `foo.ipynb` into a python file
`foo.py` which is tested by tests in `test_foo` (which in turn is
produced from `test_foo.ipynb`.

The basic ideas is to write the tests as conventional test code (for
example one per cell, if we write the tests in test_foo.ipynb, but we
could also just write the tests in a normal python file test_foo.pi),
and to convert the notebook with the implementation of the tested
functionality to another python file, and run testing on the resulting
python files.




