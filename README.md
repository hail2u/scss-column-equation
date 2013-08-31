SCSS Column Equation
====================

Generate variables for CSS column layout, the [Sass][1]y way.


INSTALLATION
------------

Three options are available:

  1. [Download package][2]
  2. Clone with Git: `$ git clone https://github.com/hail2u/scss-column-equation.git`
  3. Install with [Bower][3]: `$ bower install --save-dev scss-column-equation`


USAGE
-----

  1. Define basic variables: `$sce_column` and `$sce_gutter`
  2. Import `sce.scss` via `@import`
  3. Create column definition with generated variables


### Variables

  * `$sce_column`:                      column width (configurable)
  * `$sce_gutter`:                      space between columns (configurable)
  * `$sce_gap`:                         an half size of `$gutter` and very outer space of column
  * `$sce_colspan1`...`$sce_colspan16`: width of `n` columns
  * `$sce_colspan`:                     list contains `$colspan1`...`$colspan16`
  * `$sce_colwrap1`...`$sce_colwrap16`: wrapper width of `n` columns
  * `$sce_colwrap`:                     list contains `$colwrap1`...`$colwrap16`

*Note*: `$sce_colspan` and `$sce_colwrap` are lists. Their elements can be accessed with `nth()` function.


EXAMPLE
-------

Preview these examples at once: http://hail2u.github.com/scss-column-equation/


### Default

This example generates default 12-column with `px` (similar to [960.gs][4]).

### EM

This example generates fixed 12-column with `em`.

### Percentage

This example generates completely fluid 16-column with `%`.


LICENSE
-------

MIT: http://hail2u.mit-license.org/2012


[1]: http://sass-lang.com/
[2]: https://github.com/hail2u/scss-column-equation/archive/master.zip
[3]: http://bower.io/
[4]: http://960.gs
