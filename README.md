# Gemini [![Build Status](https://github.com/anishathalye/gemini/workflows/CI/badge.svg)](https://github.com/anishathalye/gemini/actions?query=workflow%3ACI)

Gemini is a modern LaTeX [beamerposter] theme. This is a fork of the original Gemini theme specifically for use at Tulane University.


<p align="center">
<a href="https://github.com/outlawhayden/tulane-gemini/blob/master/assets/tulane-example.png?raw=true">
<img src="https://github.com/outlawhayden/tulane-gemini/blob/master/assets/tulane-example.png?raw=true">
</a>
</p>


## Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile` for rendering
    * For MacOS, try MacTeX - for Linux, try TeX Live - for Windows, try MiKTeX or TeX Live.
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License


### TEX

1. Copy the files in this repository (or clone the repository)

1. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking (optional, but
   highly recommended)

1. Run `make` to build your poster

### Overleaf

1. Copy the files in this repository directly to a new project in Overleaf

1.  In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking (optional, but
   highly recommended)

## Contributing

Contributions to Gemini such as bug reports, new themes, and new poster
components are greatly appreciated! Given the subjective nature of design,
you're encouraged to open an issue or pull request early to get feedback before
investing a lot of time in implementing a new feature.

## License

Copyright (c) Hayden Outlaw. Released under the MIT License. See
[LICENSE.md][license] for details.

Tulane University logo Copyright (c) Tulane University.

Not official communications material.

[beamerposter]: https://github.com/deselaers/latex-beamerposter
[Auriga]: https://github.com/anishathalye/auriga
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[license]: LICENSE.md
