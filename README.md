vdiff
=====

A tool for comparing similar PDFs and highlighting differences. 
Renders an output PDF with unchanged details in grey-black, 
additions in blue and subtractions in red. 

Prerequisites
-------------

Requires imagemagick, ghostscript, and poppler. On macOS, you can install it with:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install imagemagick ghostscript poppler
```

Usage
-----

`./vdiff <pdf 1> <pdf 2> <output pdf> [--use-cache]`

The `--use-cache` flag speeds up subsequent runs by reusing previously rendered process files. Delete the `cache` folder or remove the flag to rerender from scratch.

