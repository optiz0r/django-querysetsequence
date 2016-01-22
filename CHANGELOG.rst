.. :changelog:

Changelog
#########

0.2.4 (2016-01-21)
==================

* Add support for Django 1.9.1
* Support ``order_by()`` that references a related model (e.g. a ``ForeignKey``
  relationship using ``foo`` or ``foo_id`` syntaxes)
* Support ``order_by()`` that references a field on a related model (e.g.
  ``foo__bar``)

0.2.3 (2016-01-11)
==================

* Fixed calling ``order_by()`` with a single field

0.2.2 (2016-01-08)
==================

* Support the ``get()`` method on ``QuerySetSequence``

0.2.1 (2016-01-08)
==================

* Fixed a bug when there's no data to iterate.

0.2 (2016-01-08)
================

* Fixed packaging for pypi
* Do not try to instantiate ``EmptyQuerySet``

0.1 (2016-01-07)
================

* Initial release to support Django 1.8.8