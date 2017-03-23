# Spacing - Bootstrap 3
Spacing SASS backwards port from Bootstrap 4 to 3

Make use of Bootstrap 4's [spacing utilities](https://v4-alpha.getbootstrap.com/utilities/spacing/)

## Instal (any of:)
	yarn add spacing-bootstrap-3
	npm install --save spacing-bootstrap-3
	bower install --save spacing-bootstrap-3

## Integrate (as appropriate:)
	@import 'node_modules/spacing-bootstrap-3/spacing';
	@import 'bower_components/spacing-bootstrap-3/spacing';
	
## Use

You can now use any [spacing utility](https://v4-alpha.getbootstrap.com/utilities/spacing/) classes like:
	<div class="py-1 py-sm-2 mb-md-3"></div>
	
## Configure

It actually uses linear increments for the spacings, based on the $grid-gutter-width by default, rather than bootstrap 4's bonkers built in one (which I've [whinged about](https://github.com/twbs/bootstrap/issues/21702), but Mark Otto isn't having any of it).

Howsoever, you can easily override the defaults by setting a $spacers map variable.
