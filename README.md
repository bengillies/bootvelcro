Bootvelcro
==========

Bootvelcro is a fork of Twitter [Bootstrap](http://twitter.github.com/bootstrap) with a few key differences.

Reduced Scope
-------------

Firstly, there is greatly reduced scope. Bootstrap is an excellent resource, but it's considerably more than just a CSS framework. Bootvelcro on the other hand aims to be just a CSS framework and nothing else. This helps it slot into other frameworks and libraries with minimal effort. Bootvelcro lacks the following fetures that are present in Bootstrap:


* JavaScript - Bootvelcro is a simple CSS only library.
* A CSS Grid - Bootvelcro makes HTML elements look nice and _that's it_.
* Media Queries - Bootvelcro has no custom media queries.
* Icons - Bootvelcro includes no icons.
* Accordions, Modals, Carousels, Pagination, Popovers, Thumbnails, and Tooltips

As you may have noticed, Bootvelcro is really simple. It doesn't include the kitchen sink, and it doesn't include it on purpose.

It holds the viewpoint that things like modals, accordions, and icons are best left to the developer building the site and that, in doing this, things will be a lot easier down the road.

As for grid systems and media queries, sites that need them can add one of the many that already exist. The purpose of bootvelcro is to make HTML elements look nice so that you can continue to build your siteand not have to worry about replacing bits or picking something that's already compatible. It just does look-nice. That's it.

px's vs. em's
-------------

Secondly, All the key measurements are in em's rather than px's. If you like sort of thing, this probably means a lot to you.

Simplicity
----------

__This section is currently not implemented.__

Bootstrap has a tendency to suffer from divitis and ugly HTML. Bootvelcro makes an effort to reduce this complexity. The navbar in Bootstrap, for example, looks like this:

	<div class="navbar">
		<div class="navbar-inner">
			<div class="container">
				...
			</div>
		</div>
	</div>

In Bootvelcro however, it looks like this:

	<div class="navbar">
		...
	</div>
