SCSS Column Equation
====================

Generate variables for creating CSS column definition, the [Sass](http://sass-lang.com/)y way.


USAGE
-----

  1. Define basic variables: `$column` and `$gutter`
  2. Import `sce.scss` via `@import`
  3. Create column definition with generated variables


### Variables

  * `$column`:                  column width (configurable)
  * `$gutter`:                  space between columns (configurable)
  * `$gap`:                     an half size of `$gutter` and very outer space of column 
  * `$colspan1`...`$colspan16`: width of `n` columns
  * `$colspan`:                 list contains `$colspan1`...`$colspan16`
  * `$colwrap1`...`$colwrap16`: wrapper width of `n` columns 
  * `$colwrap`:                 list contains `$colwrap1`...`$colwrap16`

*Note*: `$colspan` and `$colwrap` are lists. These values can be accessed with `nth()` function.


EXAPMLES
--------


### Default

This example generates default 12-column with `px` (similar to [960.gs](http://960.gs)).

### EM

This example generates fixed 12-column with `em`. 

### Percentage

This example generates completely fluid 16-column with `%`.


LICENSE
-------

MIT: http://hail2u.mit-license.org/2012
