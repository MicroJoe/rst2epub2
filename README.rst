rst2epub2
===============

This code consists of two tools:

* a binary, ``rst2epub``, to convert rst files into epub2 compliant files (ie that pass epub check, can be loaded into Apple, BN, Kobo, etc. Or converted to mobi and thrown into AMZN)
* a library, ``epublib``, that has the ability to programatically create epub files.

Install
============

run::

  make deps
  env/bin/python setup.py install

Known to work on linux systems. (Should work on apple, cygwin, MS with some futzing).

Docs
======

There are a few rst tweaks to support features such as metadata. See the sample doc for examples of a complete book and how to generate both epub and mobi files.
