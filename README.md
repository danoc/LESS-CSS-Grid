# LESS CSS Grid

The LESS CSS Grid is a flexible 24-column fluid grid that uses [LESS](http://lesscss.org/) to make it easily customizable.

The grid's max-width, number of columns, and column width can each be adjusted by changing a variable in the `grid.less` file. The gutter width is automatically calculated so you don't have to worry about it!

## Quick start

Open grid.less and adjust the `@max-width`, `@numCols`, and `@colWidth` variables as desired. If adjusting the number of columns, make sure to add or remove from the `.spanXX` selectors. The width of the gutter will be automatically calculated, so make sure the column width is always smaller than (100/@numCols)%.

Since this grid uses LESS, be sure to include the following lines in your `<head>`:

	<link rel="stylesheet/less" type="text/css" href="grid.less">
	<script src="js/less.js" type="text/javascript"></script>

Adding rows and columns is easy and looks like this:

	<div class="container">
		<div class="row">
			<div class="span16">16</div>
			<div class="span8 last">8</div>
		</div>
		<div class="row">
			<div class="span24 last">24</div>
		</div>
	</div>

The last column in each row must include the `.last` selector and the width of the columns must not exceed the number of columns (24 by default). 

### Thanks to:

* [CSS Grid](http://cssgrid.net/)
* [LESS CSS](http://lesscss.org/)