# VM_Flex_Strap

Vehicle Media's FlexboxGrid / Bootstrap 4 hybrid Grid System

v.3.2

In 3.2 VM_Flex_Strap is now fully compatible with IE 11

Note: .col-xs, .col-sm, etc. In IE, a "too big" image will not wrap properly. The image width will be allowed to overflow the item.

[Demo Page](http://frontend.vehicle44.com/VM_Flex_Strap/)

## Summary

* Grid system built using Flexbox layout
* This is a great resource if you are unfamiliar with it. https://css-tricks.com/snippets/css/a-guide-to-flexbox/
* Mimics Bootstrap's .col-** syntax and breakpoints.
* Mimics and augments FlexboxGrid's helper class syntax.
* Styles are declared initially for mobile and overwritten as screen size increases.
* The grid classes are written in a manner to reduce the number of neccessary class assignments per element. Eliminating duplicate declarations, and less typing for the developer.



## Breakpoints


* .col-xs All screen sizes
* @media (min-width: 568px) { .col-sm Mobile Landscape screen sizes } iphone5 dimensions
* @media (min-width: 768px) { .col-md Tablet Portrait screen sizes } iPad dimensions
* @media (min-width: 992px) { .col-lg Tablet Landscape screen sizes }
* @media (min-width: 1200px) { .col-xl Desktop screen sizes }


## Grid Structure

The grid structure follows: .container --> .row --> .col-??-??

```

<div class="container">
	<div class="row">
		<div class="col-sm-6">
			...Some content here...
		</div>
		<div class="col-sm-6">
			...More content here...
		</div>
	</div>
</div>

```

.row's are the flex containers

.col's are the flex items

## Author

* **Dave Carney** - *Github Profile* - [davecarney](https://github.com/davecarney)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

