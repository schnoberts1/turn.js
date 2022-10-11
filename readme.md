Fork changes
=========

- Removed the timeout message as ....
- added support for canvases so ....
- I can use PDF.js with it
- Added logging
- Increased default corner size
- Disable all the swipe handling and handle that myself to work around an issue that I am sure I have introduced with the addition of async canvas rendering.
- Really only works with a PDF page flip component I wrap around it.

Note: Changed not tested with HTML display mode but I don't see why it won't work.

vvvv Original README below vvvv

turn.js 3rd release
=========

### Make a flip book with HTML5

Turn.js is a plugin for jQuery that adds a beautiful transition similar to real pages in a book or magazine. It works in all modern browsers including touch devices.

### What's new?

- New `addPage` for creating pages dynamically.

- New `display` for single and double pages.

- Gradients for non-webkit browsers.

#### Usage

**CSS code:**
```css
#magazine{
	width: 800px;
	height: 400px;
}
#magazine .turn-page{
	background-color:#ccc;
}
```

**HTML code:**
```html
<div id="magazine">
	<div><span class="text">Page 1</span></div>
	<div><span class="text">Page 2</span></div>
	<div><span class="text">Page 3</span></div>
</div>
```

**JavaScript code:**
```javascript
$('#magazine').turn({gradients: true, acceleration: true});
```

#### Requirements

jQuery 1.7 or later

#### Browser support
* Chrome 12, Safari 5, Firefox 10, IE 9

#### License
Released under a non-commercial BSD license

[Full documentation](https://github.com/blasten/turn.js/wiki/Reference)

* * *

[turnjs.com](http://www.turnjs.com/)
