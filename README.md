[rssc]: https://github.com/mikejsavage/rssc-sendmail/blob/master/Makefile

merge.lua is a tool for merging Lua source trees into a single
executable.

Usage
=====

	merge.lua [source directory] [entry point] > a.out
	chmod +x a.out
	./a.out

has the same effect as:

	cd [source directory]
	lua [entry point]

You can also find a real usage example in [this Makefile][rssc].
