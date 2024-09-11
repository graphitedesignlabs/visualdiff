vdiff
=====

Tool for comparing similar PDFs and highlighting differences. 
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

`./vdiff <file 1> <file 2> <output file> [--use-cache]`

The `--use-cache` file persists a folder of process output files that will be
reused on future runs with this flag.

