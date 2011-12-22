# LESS CSS Grid

The LESS CSS Grid is a flexible 24-column fluid grid that uses [LESS](http://lesscss.org/) to make it easily customizable.

## Quick start

Open grid.less and adjust the `@max-width`, `@numCols`, and `@colWidth` variables as desired. If adjusting the number of columns, make sure to add or remove from the `.spanXX` selectors. The width of the gutter will be automatically calculated, so be sure to set a column width smaller than (100/@numCols)%.

### Thanks to:

* [CSS Grid](http://cssgrid.net/)
* [LESS CSS](http://lesscss.org/)