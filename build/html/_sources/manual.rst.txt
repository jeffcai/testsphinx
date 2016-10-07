User Manual
============

This is the documentation for the Sphinx documentation builder.  Sphinx is a
tool that translates a set of reStructuredText_ source files into various output
formats, automatically producing cross-references, indices etc.  That is, if
you have a directory containing a bunch of reST-formatted documents (and
possibly subdirectories of docs in there as well), Sphinx can generate a
nicely-organized arrangement of HTML files (in some other directory) for easy
browsing and navigation.  But from the same source, it can also generate a
LaTeX file that you can compile into a PDF version of the documents, or a
PDF file directly using `rst2pdf <https://github.com/rst2pdf/rst2pdf>`_.

The focus is on hand-written documentation, rather than auto-generated API docs.
Though there is support for that kind of docs as well (which is intended to be
freely mixed with hand-written content), if you need pure API docs have a look
at `Epydoc <http://epydoc.sourceforge.net/>`_, which also understands reST.

For a great "introduction" to writing docs in general -- the whys and hows, see
also `Write the docs <http://write-the-docs.readthedocs.org/>`_, written by Eric
Holscher.

please refer to below screenshot for details

.. image:: _static/diablo1.jpg
This is the caption of the figure (a simple paragraph).

Continues ...

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+

This is a paragraph that contains `a link`_.

.. _a link: http://example.com/


=================
This is a heading
=================