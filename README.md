# Overview

This project was forked from the [bootstrap3-wysihtml5-bower](https://github.com/Waxolunist/bootstrap3-wysihtml5-bower) project

See its README.md for full documentation.

This fork offers a css with an RTL version of the bootstrap3-wysihtml5 control - these css files comes in addition to the original LTR css files.
the changes in the RTL css files are very minor and generally its align the wysihtml5 toolbar and the textarea cursor to the right.

## Usage

See the [original](https://github.com/Waxolunist/bootstrap3-wysihtml5-bower#files-to-reference) documentation for the exact files to reference, however:

instead of **bootstrap3-wysihtml5.min.css** use **bootstrap3-wysihtml5.min-rtl.css**

This will align the wyshtml5 toolbar to the right

In order to align the textarea cursor to the right use the **stylesheet-rtl.css** stylesheet as shown in this example (based on [this](https://github.com/Waxolunist/bootstrap3-wysihtml5-bower#stylesheets) capability):

```javascript
$('#some-textarea').wysihtml5({
	"stylesheets": ["/path/to/dist/stylesheet-rtl.css"]
});
```

# Enjoy!
