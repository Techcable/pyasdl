Abstract Syntax Description Language
====================================
Code originally taken from CPython [`Parser/asdl.py`](https://github.com/python/cpython/blob/main/Parser/asdl.py)

Good explanation here: https://www.oilshell.org/blog/2016/12/11.html

I have made a few improvements and cleanups. In particular, the AST for the asdl package now uses dataclasses.

This repo does not include the `Python.asdl` grammar description.
It depends too much on the specific python version (which is not the focus of this repo).
