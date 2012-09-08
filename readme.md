About
-----
This is a Sublime Text 2 syntax highlighting package for a toy language 
called ParselTongue that is used in Brown CS's course on programming
languages. If you aren't taking that class, this will not be
useful to you.

Installing
----------
If you have Package Control installed, then run Package Control: Add
Repository and enter http://github.com/dbp/sublime-parsel; then you can
Package Control: Install Package and enter sublime-parsel.

Alternatively, you can either copy or symlink ParselTongue.tmLanguage 
in the User packages folder (accessible via a menu, varies by platform). 
It will then recognize .psl files as ParselTongue and highlight accordingly.

Improvements
------------
There may be mistakes or things it doesn't highlight - feel free
to make changes, but make changes to the .JSON-tmLanguage file,
and use the sublime package AAAPackageDev to convert that to
the propertylist file. Pull requests welcome, but if you have
only changes the .tmLanguage file, they will be rejected.
