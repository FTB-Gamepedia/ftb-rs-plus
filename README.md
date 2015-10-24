# ftb-rs-plus
Fork of [ftb-rs](https://github.com/retep998/ftb-rs).

List of changes:
* This was forked off [this commit](https://github.com/retep998/ftb-rs/commit/c7a8aa69cd0de4f5a0eafea8bb97ca70f81ee552). Anything that happened after it is excluded (mostly version updates).
* A possible build fix or two.
* The bug that used "\" instead of "/" in file names was fixed.
* Raises an error when "[" or "]" is in a filename- the Tilesheet extension will error with those contained.