SublimeYammy
============

Yammy syntax highlighting for Sublime Text 2

Installation
------------

Clone this repository into the Packages directory. If you don't know where it is, enter the following command in the console:

		print sublime.packages_path()

To access the console press CTRL + `

Known bugs
----------

Add a single line starting with the '#' character below the 'style' and 'script' to "close" the embedded syntax block.

		head
			script
				$(function(){});
		#
		body
			div
