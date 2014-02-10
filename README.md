searchReplace
=============

Search (and replace) in text files

Requirements: Python, Pyside/PyQt (configure this in searchReplace.py)

Features:
* Search
* Search & Replace
* Records the row(s) of the text file containing the search string - optionally disable this
* Designed to be easy on RAM, to be used on enormous projects containing a large number of text files
* In case of write error, a dump file will be created next to the original file with the original contents
* Binary file detection (and option to skip these files)
* Can run inside of Nuke, Maya as well as standalone
* Tested on OS X, Windows


Important notice: Use this application on your own risk!
This application does NOT store the contents of all text files matching the search criteria locally or in the RAM. Instead, it opens the files and re-writes them. If there is a write error and plan b (writing a dump file with a other name than the original file) won't work - all data is lost. Be VERY careful when running this application.
