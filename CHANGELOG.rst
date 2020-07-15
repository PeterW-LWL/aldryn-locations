CHANGELOG
=========

1.1.6 (unreleased)
------------------

* TODO


1.1.5 (2019-07-08)
------------------

* Fix missing 'on_delete' in migrations
* Fix import of 'six'


1.1.4 (2019-04-29)
------------------

* Fix unicode error in python 3
* Fix for 'query' field not used in model for Django 1.11
* Fix leaking the admin url when accessed without login
* Add 'on_delete=models.CASCADE' required for Django 2.0


1.1.3 (2016-10-11)
------------------

* Fix unicode error in location plugin
* Fix error introduced in 1.1.2 (commit f76dedd7)


1.1.2 (2016-10-11)
------------------

* Path location plugin: fix absolute url


1.1.1 (2016-09-14)
------------------

* Fix staticmap with new kml location plugin


1.1.0 (2016-09-14)
------------------

* Add "Location from Path file" plugin
* Drop support for Django 1.6 and below


1.0.5 (2016-08-22)
------------------

* Rename static map url property


1.0.4 (2016-08-22)
------------------

* Fix various `max_length` attributes
* Add static map query url getter


1.0.3 (2016-08-18)
------------------

* Add formatting setting for marker info windows `ALDRYN_LOCATIONS_MARKER_CONTENT_FORMAT`


1.0.2 (2016-08-03)
------------------

* Use Environment variable for API key (when used with aldryn-addons)


1.0.1 (2016-06-21)
------------------

* Added translations infrastructure


1.0.0 (2015-03-10)
------------------

* Add stripped default django templates to `/aldryn_locations/templates`
* Fixed an issue with modal.open
* Removed deprecated sensor attribute


0.5.0 (2015-03-11)
------------------
* Aldryn addon settings update


0.4.0 (2015-02-03)
------------------

* multi-boilerplate support
  new requirement: aldryn-boilerplates (needs configuration)
