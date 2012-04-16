# CSS Format

A package for formatting CSS files.

Currently it only supports toggling between inline and block style
formats of a CSS code block.

# Installation

To install it, put this file in your load-path and add the following
line to your init file (usually `$HOME/.emacs`).

```lisp
(require 'css-format)
```

# Usage

From inside a CSS block you can call `css-format-inline` or
`css-format-block` to format that specific block.

