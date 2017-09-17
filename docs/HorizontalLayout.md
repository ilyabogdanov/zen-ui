# [Zen UI](../README.md) &#x25B8; Horizontal Layout

Divides area into columns.
Best suited for device-specific views without breakpoints.
Consists of the following components:

* `HorizontalLayout` which has optional property `height`; and
* `HorizontalLayoutColumn` which has optional properties `width` and `padding`.

The following rules will apply to undefined properties:

* If `height` of `HorizontalLayout` was not defined,
it will depend on columns content.
* If `width` of `HorizontalLayoutColumn` was not defined,
it will be calculated from available space.
* If `padding` of `HorizontalLayoutColumn` was not defined,
it will equal Zero.

Order in which columns' width will be calculated.

1. Pixel-width columns and columns with undefined width have the highest priority.
Columns with undefined width depend on their content.
1. Percent-width columns take remaining space.
1. Space not taken by percent-width columns will be given to ratio-width columns.
