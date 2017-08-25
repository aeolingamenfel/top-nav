# top-nav
An HTML custom element implementing the `<top-nav>` element.

![top-nav in action](https://github.com/Kiricon/top-nav/raw/master/screencapture.gif)

## Setup

### Installation
```
npm i top-nav
```

---

```Html
<script src="node_modules/top-nav/top-nav.js"></script>
```
or if you're bundling
```Javascript
import "top-nav";
// or
require("top-nav");
```


## Usage
```HTML
<top-nav>
    <!-- Your content here -->
</top-nav>
```


## Customization
You can customize the color of the `top-nav` by assigning values to css elements. 

The who css elements that affect `top-nav` are `--top-nav-color` and `--primary-color`.

You can set there values like so

```CSS
    :root {
        --top-nav-color: red; /* if both are set --top-nav-color takes precedence */
        --primary-color: red; 
    }
```
