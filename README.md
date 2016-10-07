Test Sphinx
-------------------

To try sphinx for building more maintainable and deployable documents


## Build

make html


## TODO

- doc converted to rst with pandoc or something else
- more concise table
- footnote
- quick search function
- index
- theme
- deployment
- automation script


## Issues

- unable to make html due to HTMLParser: change sphinx.builders.linkcheck.py as follows:

```
#from six.moves.html_parser import HTMLParser
from HTMLParser import HTMLParser
```

- can not find rst files declared in index toc: caused by tab ahead of text which should be 3 spaces