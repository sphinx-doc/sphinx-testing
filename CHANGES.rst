Changelog
==========

1.0.1 (2019-04-15)
-------------------
- Support Sphinx-2.0.1

1.0.0 (2019-01-27)
-------------------
- Support Sphinx-2.0 (unreleased yet)
- Fix a bug:

  - #12: @with_app decorator should return the value of the decorated function

0.8.1 (2018-11-24)
-------------------
- Fix a bug:

  - #9: warningiserror=True is broken with Sphinx 1.8.2

0.8.0 (2018-11-13)
-------------------
- Drop py33 support
- Fix bug:

  - #8: Tests are failing with Sphinx 1.8.2

0.7.2 (2017-05-03)
-------------------
- Fix bug:

  - #2: Fix cleanups for Sphinx 1.6

0.7.1 (2015-05-24)
-------------------
- Fix bug:

  - Fix write_docstring should refer master_doc and source_suffix

0.7.0 (2015-03-21)
-------------------
- PR#1 Enable verbosity and parallel arguments.

0.6.0 (2014-10-17)
-------------------
- Add python 3.2 support (with Sphinx < 1.3)
- Replace ListOutput with StringIO

0.5.2 (2014-10-16)
-------------------
- Fix bug:

   - Fix srcdir and confdir are not abspath

0.5.1 (2014-10-15)
-------------------
- Reimplement with_app decorator as class
- Set copy_srcdir_to_tmpdir=True if write_docstring is specified

0.5.0 (2014-10-15)
-------------------
- Add write_docstring option to with_app()

0.4.0 (2014-09-30)
-------------------
- Add pathlib like accessors to path class: parent, name, suffix and stem
- Fix bug:

   - #1 Fix exc assignment in with_app decorator.

0.3.0 (2014-09-27)
-------------------
- Rename sphinx.testing package to sphinx_testing

0.2.0 (2014-09-24)
-------------------
- Add path#utime() and path#listdir()
- Change interface of @with_app: Give `status` and `warning` to decorated function as a argument

0.1.0 (2014-09-20)
-------------------
- Initial release
