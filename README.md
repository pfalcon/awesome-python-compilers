Projects with code deliverables
===============================

* 1997-1999 [Python2C](https://web.archive.org/web/20011025084441/http://www.mudlib.org/~rassilon/p2c/)
* 2002-2011 [Psyco](http://psyco.sourceforge.net/), https://bitbucket.org/arigo/psyco
  * Was actually used in production for many projects
* 2003, active [PyPy](https://bitbucket.org/pypy/pypy)
* 2006 Grant Olson's [Compyler](https://www.grant-olson.net/projects/misc.html)
* 2008, active [Shedskin](https://github.com/shedskin/shedskin)
* 2009-2010 Unladen Swallow
  * [Postmortem](http://qinsb.blogspot.com/2011/03/unladen-swallow-retrospective.html)
* 2011, active [Nuitka](https://github.com/Nuitka/Nuitka)
* 2010-2011 HotPy
* 2012-2012 HotPy2
  * https://sites.google.com/site/makingcpythonfast/
  * https://sites.google.com/site/makingcpythonfast/
  * https://code.google.com/archive/p/hotpy/
  * https://bitbucket.org/markshannon/hotpy_2
* 2012-2012 [pymothoa](https://github.com/sklam/pymothoa)
  * https://code.google.com/archive/p/pymothoa/
  * https://www.phoronix.com/scan.php?page=news_item&px=MTEzMDQ
* 2012-2013 [Parakeet](https://github.com/iskandr/parakeet)
* 2012, active [Pythran](https://github.com/serge-sans-paille/pythran)
  * [docs](https://pythran.readthedocs.io)
  * 2019-01-24 [Pythran: Python at C++ speed !](https://medium.com/@olivier.borderies/pythran-python-at-c-speed-518f26af60e8)
* 2012-2018 [reticulated](https://github.com/mvitousek/reticulated)
* 2014-2017 https://github.com/darius/tailbiter - Simple teaching metacircular bytecode compiler
  * [Originally](https://github.com/darius/500lines/tree/master/bytecode-compiler)
    for book "500 Lines or Less" (didn't fit)
  * 2014-02-24 http://abecedarius.tumblr.com/post/77679122389/ouroborospy
  * 2014-03-17 http://abecedarius.tumblr.com/post/79850464139/tail-eaten-well-almost
  * 2017-02 [Dragon taming with Tailbiter, a bytecode compiler for Python](https://codewords.recurse.com/issues/seven/dragon-taming-with-tailbiter-a-bytecode-compiler) -
* 2014-2017 [Pyston](https://github.com/dropbox/pyston)
  * 2014-04-03 [Announcement](https://blogs.dropbox.com/tech/2014/04/introducing-pyston-an-upcoming-jit-based-python-implementation/)
  * 2017-01-31 [Postmortem](https://blog.pyston.org/2017/01/31/pyston-0-6-1-released-and-future-plans/)
* 2015-2015 https://github.com/lukasmartinelli/py14 - Python to C++ 14 transpiler
* 2015-2019 [numpile](https://github.com/sdiehl/numpile) - A tiny 1000 line LLVM-based numeric specializer for scientific Python code
  * [Let's Write an LLVM Specializer for Python!](http://dev.stephendiehl.com/numpile/)
* 2015-2016 [FAT Python](https://faster-cpython.readthedocs.io/fat_python.html)
  * https://github.com/vstinner/fatoptimizer

Academic and theoretical research, and just no code available
=============================================================

* 1997-2000 PyFront (afterwards Basil)
* 2000 [Basil](http://wildideas.org/basil/)
  * https://sourceforge.net/projects/basil/ - No files, no VCS
  * http://wiki.c2.com/?BasilProject
  * http://wiki.c2.com/?BasilProjectLog
* 2002-2003 UCPy compiler + Mamba VM
  * [UCPy: Reverse-Engineering Python](https://pages.cpsc.ucalgary.ca/~aycock/papers/ucpy.pdf)
* 2004-2004 Starkiller
  * [Faster than C: Static Type Inference with Starkiller](http://citeseer.ist.psu.edu/viewdoc/summary?doi=10.1.1.95.3786)
  * Shedskin seems to be based on similar ideas and provides concrete deliverables

Python Conferences and SIGs
===========================

* 1998-11 7th International Python Conference
  * From Jon Riehl's [notes](https://wildideas.org/basil/):
  > Last year (IPC7,) I thought I was going to surprise the Python community
  > by presenting a prototype Python to C translator. Little did I know,
  > I was only one of three people who announced such a product.
 * These apparently were:
   * "Converting Python Virtual Machine Code to C", John Aycock
   * "PyFront: Conversion of Python to C Extension Modules", Jon Riehl
   * (3rd - ???)
* 2000-01 8th International Python Conference
  * From Jon Riehl's [notes](https://wildideas.org/basil/):
  > This year (IPC8,) in the interest of keeping people up to date,
  > there was a two hour session that hosted the developers of these
  > prototypes. The only system left standing is now complete and under
  > beta test. Bill Tutt and Greg Stein cowrote Python2C, which they
  > have been continuing to work on at (http://www.mudlib.org/~rassilon/p2c/).
  > The other player is John Aycock. John declared he would look into run time
  > type instrumentation, which I think should end up forming some sort of a
  > JIT for Python. He lives at: (http://gulf.uvic.ca/~aycock/) 
* 2000 [Compiler-SIG](ftp://ftp.ntua.gr/mirror/python/sigs/compiler-sig/index.html)
  * "This SIG grew out of a Developers' Day session at the 8th International Python
    Conference. Ka-Ping Yee took
    [notes on the session](ftp://ftp.ntua.gr/mirror/python/sigs/compiler-sig/dev-day-notes.txt)."

PEPs
====
* [PEP 267](https://www.python.org/dev/peps/pep-0267/), 2001-05, Py2.2: Optimized Access to Module Namespaces
* [PEP 266](https://www.python.org/dev/peps/pep-0266/), 2001-08, Py2.3: Optimizing Global Variable/Attribute Access
* [PEP 280](https://www.python.org/dev/peps/pep-0280/), 2002-02, Py2.3: Optimizing access to globals

* [PEP 329](https://www.python.org/dev/peps/pep-0329/), 2004-04, Py2.4: Treating Builtins as Constants in the Standard Library

* [PEP 510](https://www.python.org/dev/peps/pep-0510/), 2016-01, Py3.6: Specialize functions with guards
* [PEP 511](https://www.python.org/dev/peps/pep-0511/), 2016-01, Py3.6: API for code transformers


Static Analysis
===============

* https://github.com/sdiehl/subpy - Subpy is a library for defining subsets
of the Python language and querying ASTs for language-level properties that
are specified as sets of features.


Parsers
=======

* https://github.com/python/typed_ast - Modified fork of CPython's ast module
  that parses `# type:` comments.
* https://github.com/m-labs/pythonparser - "Parses source code into an AST
  that is a superset of Python’s built-in ast module".
* https://github.com/lark-parser/lark/blob/master/examples/python3.lark - Python3
  grammar for Lark parser.
* 2013-07-26 [The obvious Python parser](http://blog.nullspace.io/obvious-python-parser.html) -
  Constructing Python3 parser. In Haskell, d'oh. Code: https://github.com/hausdorff/pyli

---
This list is compiled and maintained by Paul Sokolovsky, and released under
[Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).
