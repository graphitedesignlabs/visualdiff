vdiff
=====

A command line bash script for comparing similar PDFs. Outputs a third file 
highlighting differences in blue (additions) and red (subtractions). 

Prerequisites
-------------

Requires imagemagick and ghostscript
On Mac, you can install it with:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install imagemagick ghostscript
```

Usage
-----

`./vdiff <file 1> <file 2> <output file>`


