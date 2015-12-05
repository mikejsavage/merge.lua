[rssc]: https://github.com/mikejsavage/rssc-sendmail/blob/master/Makefile

merge.lua is a tool for merging Lua source trees into a single
executable.

Usage
=====

	merge.lua src main.lua 5.1 > a.out
	chmod +x a.out
	./a.out

has the same effect as:

	cd src
	lua5.1 main.lua

The version is optional, and the default is to just use `lua`.

You can find a real usage example in [this Makefile][rssc].
