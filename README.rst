=========
Archivist
=========

Archivist is used to check the md5 and file size of any version of `Anaconda <https://store.continuum.io/cshop/anaconda/>`_ against the expected md5 and size listed in the archive.

===
Use
===

From the Archivist directory, run the script, giving the desired version of Anaconda as an argument:

.. code-block:: bash

    $ python archivist.py -v 1.5.0

Each version of Anaconda meeting this requirement will be downloaded from the `Continuum <http://continuum.io>`_  archives, then checked to be sure that the size and md5 are correct.

============
Dependencies
============

* [OPTIONAL] The `conda <https://conda.pydata.org/miniconda.html#miniconda>`_ package manager.


* `beautifulsoup4 <http://www.crummy.com/software/BeautifulSoup/>`_ - Now available in `Anaconda 1.8.0 <https://store.continuum.io/cshop/anaconda/>`_

.. code-block:: bash

   $ conda install beautiful-soup

* [OPTIONAL] `colorama <https://pypi.python.org/pypi/colorama>`_

.. code-block:: bash

   $ conda install colorama

* `curl <http://curl.haxx.se/docs/manpage.html>`_

====
TODO
====

Allow for selection of individual packages.

Add a gui option.
