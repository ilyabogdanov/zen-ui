# [Zen UI](../README.md) &#x25B8; Vertical Layout

Divides area into rows. Consists of the following components:

* `VerticalLayout` without properties; and
* `VerticalLayoutRow` with optional properties `height` and `padding`.

There are three kinds of rows:
* __Flexible row__, ie `VerticalLayoutRow` without `height` property,
which height depends on it's content;
* __Fixed row__, ie `VerticalLayoutRow` with definite `height`.
* __Stretch row__, `VerticalLayoutRow` which `height` equals 100%
so that it takes all remaining space;
