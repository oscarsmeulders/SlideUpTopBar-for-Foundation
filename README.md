# SlideUpTopBar for Foundation
SlideUpTopBar is an extension for Zurb Foundation's top-bar component. It hides the top-bar when scrolling down a page & shows it when scrolling back up the page.

## Installation
Include jQuery (which you already have if you are using Foundations top-bar component)

Include the CSS file, or add it to your own styles

Include `sup-topbar.min.js` after your Foundation scripts:

```
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
    <script src="sup-topbar.min.js"></script>
    <link rel="stylesheet" href="css/sup-styles.css" />

```

## Usage
Wrap your top-bar in a div with the class "slideUp". You are not restricted to any particular height of your top-bar:

```
    <div class="slideUp">
    <nav class="top-bar" data-topbar>
    ...
    </nav>
    </div>
```

## Compatibility
Tested with:
- Foundation 5
- Foundation 6 [Standard Grid](http://foundation.zurb.com/sites/docs/grid.html)
- Foundation 6 [Flex Grid](http://foundation.zurb.com/sites/docs/flex-grid.html)

## Demo
View it in action here:
[SlideUpTopBar Demo](https://pixelspring.github.io/SlideUpTopBar-for-Foundation/)
