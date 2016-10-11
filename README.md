Test Sphinx
-------------------

To try sphinx for building more maintainable and deployable documents


## Build

make html

## Convert

refer to http://peintinger.com/?p=365 for converting docx to rst, this is sample cmd: pandoc.exe -f docx architecture.docx -t rst -o architecture.rst, and note that need to save doc file as docx at first, after conversion complete need embed images (all images can be get by unzipping the docx file).


## TODO

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