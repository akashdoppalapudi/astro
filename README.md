# astro

> A Gemini web browser using shell script

![print](https://github.com/blmayer/astro/blob/main/astro.png?raw=true)


## Installing

Move the file *astro* to a folder in your PATH variable, or
run `make`, by default it will be installed into *~/.local/bin*.
Use *PREFIX* to override the install location.


## Using

Start browsing by running astro with an optional URL:

`astro gemini://rawtext.club:1965/~sloum/spacewalk.gmi`

you can omit the protocol and port:

`astro rawtext.club/~sloum/spacewalk.gmi`

no arguments takes you to *gemini.circumlunar.space*:

`astro`


### Key bindings

- `b` to go back one page
- `o` to open a new URL, you'll be prompted to type it
- `r` to reload the page
- `H` to go to the home page
- `g` to follow a link in the current page, a link will be displayed, and
- `s` to save the page to a file
- `m` to add the current page to bookmarks
- `M` to go to a bookmark
- `q` to quit

More coming.


### Configuration

You can setup a config file at `~/.config/astro/astro.conf` to configure *astro* the way you like.

The file uses a simple `key=value` style, see the complete example for the default values below. The `style-` keys must be ANSI style codes.

```
margin=8
homepage=gemini.circumlunar.space
style-header1=35;4;1
style-header2=35;1
style-header3=35;4
style-quote=2;3
style-link-bullet=33
style-link-text=36;3
style-list-bullet=35;1
style-list-text=0
```

## Meta

This software is a work in progress and may not work as it is intended to.


### Further works

- Better history
- Opening files
- Support input


### Inspired by

- [gmi](https://sr.ht/~chambln/gmi/)
- [bollux](https://sr.ht/~acdw/bollux/)

