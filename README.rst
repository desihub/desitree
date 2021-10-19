========
desitree
========

Introduction
------------

This product is used to maintain the DESI directory hierarchy and to map
directories to environment variables.

Change Log
-----------

0.6.0 (unreleased)
~~~~~~~~~~~~~~~~~~

* Define ``${DESI_ROOT}`` external to this module file for compatibility with
  Lmod_ and Perlmutter_ (PR `#7`_).

.. _`#7`: https://github.com/desihub/desitree/pull/7
.. _Lmod: https://lmod.readthedocs.io/en/latest/
.. _Perlmutter: https://www.nersc.gov/systems/perlmutter/

0.5.0 (2020-01-19)
~~~~~~~~~~~~~~~~~~

* Migrate ``/global/project/projectdirs`` to ``/global/cfs/cdirs``.

0.4.0 (2019-04-02)
~~~~~~~~~~~~~~~~~~

* Remove unused ``${DESI_IMAGING_DATA}`` (PR `#5`_).

.. _`#5`: https://github.com/desihub/desitree/pull/5

0.3.0 (2016-10-12)
~~~~~~~~~~~~~~~~~~

* Update based on desiconda migration (PR `#3`_).

.. _`#3`: https://github.com/desihub/desitree/pull/3

0.2.0 (2015-10-30)
~~~~~~~~~~~~~~~~~~

* Add additional variables needed for pipeline processing (PR `#1`_).

.. _`#1`: https://github.com/desihub/desitree/pull/1

0.1.0 (2015-10-30)
~~~~~~~~~~~~~~~~~~

* Reference tag to archive original code.
