## CSS UI - Modal box

Simple modal box.

## Installation

```
npm install --save css-ui-modal-box
```

## Demo

- https://css-ui.github.io/modal.box/

## Quick start

CSS dependencies.

```html
<link rel="stylesheet" href="path/to/normalize.css">
<link rel="stylesheet" href="path/to/font-awesome.css">
<link rel="stylesheet" href="path/to/open-sans.css">
<link rel="stylesheet" href="path/to/cssui.css">
```

CSS modal.

```html
<link rel="stylesheet" href="path/to/style.modal.box.css">
```

Use Open Sans fotns.

```css
font-family: 'Open Sans', sans-serif;
```

Modal html.

```html
<div class="wrapper align center">
	<a href="#modal">Open</a>
	<div id="modal" class="modal-box">
		<div>
			<a href="#close" title="Close" class="modal-close align center">
				<i class="fa fa-times" aria-hidden="true"></i>
			</a>
			<h2>Modal Box</h2>
			<p>This is an example of modal box.</p>
		</div>
	</div>
</div>
```

Enjoy modal box.
