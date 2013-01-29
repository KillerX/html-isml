html-isml
=========

Building on [https://github.com/aearly/isml-tmlanguage](https://github.com/aearly/isml-tmlanguage) this version of the language definition is a replacement for the builtin HTML lang, but therefore retains all its cool features

Install (OS x)
==============

	cd ~/Library/Application Support/Sublime Text 2/Packages/
	git clone git://github.com/KillerX/html-isml.git

Add "HTML" to list of ignored packages:

	"ignored_packages":
	[
		"Vintage",
		"HTML"
	],

This should after reloading the packages give you a fully
functional HTML highlighting etc, with the added bonus of
ISML support, including completion for the most commonly used tags
