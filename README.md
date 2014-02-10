searchReplace
=============

Search (and replace) in text files

Requirements: Python, Pyside/PyQt (configure this in searchReplace.py)

Features:
* Search
* Search & Replace
* Record the row(s) of the text file containing the search string - optionally disable this
* Designed to be easy on RAM, to be used on enormous projects containing a large number of text files
* In case of write error, a dump file will be created next to the original file with the original contents
* Binary file detection (and option to skip these files)
* Can run inside of Nuke, Maya as well as standalone
* Tested on OS X, Windows
