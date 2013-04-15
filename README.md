# Make html that doesn't suck from Pandoc

Pandoc is great, but sometimes,
you simply want a complete html page from one source file.

And in this case, most of the time the result sucks, simply because the default rendering in any browser is just hideous.

This utility just create a directory containing a
complete local website with a nice CSS from any list of sources file.
It is particularly useful for literate Haskell files.
But also a bunch of markdown.

It is not as fine grained as hakyll but it is good enough.


## Usage

To compile all lhs files of the current tree directory:

```
spt **/*.lhs
```

This will create a `static-pandoc` directory.
For each lhs file there will be an `html` file.

