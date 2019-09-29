Range
=====

The Range module defines various numeric range field types for the Field module.
Ranges can be in integer, decimal, or floating-point form, and they can be
formatted when displayed. Range fields can be limited to a specific set of input
values or to a range of values.


Installation
------------

- Install as usual
- Add a range field in the field UI
- Manage the display of the prefix/suffix and separator at the field display UI.

Features
--------

Field types:
- Integer range (range_integer)
- Float range (range_float)
- Decimal range (range_decimal)

The following settings can be specified:

- Minimum and maximum values
- Precision and scale [for decimal ranges]
- Decimal separator [for decimal and float ranges]
- FROM value prefix and suffix
- TO value prefix and suffix
- FIELD value prefix and suffix
- COMBINED value prefix and suffix

Widgets:

- Two textfields

Widget options:

- FROM and TO form subelements labels

Formatters:

- Default
- Formatted string (using sprintf())
- Unformatted

Formatter options:

- Range separator
- Combine equal values into a single one
- Thousand separator
- Decimal separator [for decimal & float ranges]
- Scale [for decimal & float ranges]
- Show FROM value prefix & suffix
- Show TO value prefix & suffix
- Show FIELD value prefix & suffix
- Show COMBINED value prefix & suffix

Current Maintainers
-------------------

Maintainers wanted

Credits
-------

Taran2L on Drupal (https://www.drupal.org/u/taran2l)
Ported to Backdrop by docwilmot (https://github.com/docwilmot)

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

