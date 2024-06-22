# Gemini [![Build Status](https://github.com/anishathalye/gemini/workflows/CI/badge.svg)](https://github.com/anishathalye/gemini/actions?query=workflow%3ACI)

Gemini is a modern LaTeX [beamerposter] theme.

<p align="center">
<a href="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-gemini.pdf">
<img src="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-gemini-small.png">
</a>
</p>

If you're looking for a beamer presentation theme, take a look at [Auriga].

## Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License

## Usage

1. Copy the files in this repository (or clone the repository)

1. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking (optional, but
   highly recommended)

1. Run `make` to build your poster

## FAQ

See the [FAQ] in the Wiki for answers to frequently asked questions such as how
to add an institution logo to the poster.

## Themes

Gemini currently includes three color themes:

* `gemini` (default)
* `mit`
* `labsix`

The alternative themes are intended to be inspiration for you to make your own
color theme. You're highly recommended to make your own color theme (it's
really easy!) or use the default Gemini theme.

### MIT theme

<p align="center">
<a href="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-mit.pdf">
<img src="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-mit-small.png">
</a>
</p>

### LabSix theme

<p align="center">
<a href="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-labsix.pdf">
<img src="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-labsix-small.png">
</a>
</p>

## Design goals

* **Minimal**: clean and easy to read, so that the emphasis is on the content
* **Batteries included**: works and looks good out of the box
* **Easy theming**: easy to create and use a new color theme

## Contributing

Contributions to Gemini such as bug reports, new themes, and new poster
components are greatly appreciated! Given the subjective nature of design,
you're encouraged to open an issue or pull request early to get feedback before
investing a lot of time in implementing a new feature.

## License

Copyright (c) Anish Athalye. Released under the MIT License. See
[LICENSE.md][license] for details.

[beamerposter]: https://github.com/deselaers/latex-beamerposter
[Auriga]: https://github.com/anishathalye/auriga
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[license]: LICENSE.md
[FAQ]: https://github.com/anishathalye/gemini/wiki/FAQ


Dear David,

There will be about 80 posters at this conference. We need to plan two poster sessions to show them all.

I understand that this is important for you, and I would suggest that you include information on the activities of your new group within the poster you bring. The stands we use for the poster session have the width of A0 (about 84cm) but a height of about 180cm (i.e. larger than the standard A0 -119 cm). You might manage to fit some more information there.
 
@article{Dumerval2014,
author = {Dumerval, Marie and Perrin, St{\'{e}}phane and Marchetti, Lo{\"{i}}c and Tabarant, Michel and Jomard, Fran{\c{c}}ois and Wouters, Yves},
doi = {10.1016/j.corsci.2014.04.025},
issn = {0010-938X},
journal = {Corrosion Science},
pages = {251--257},
publisher = {Elsevier Ltd},
title = {{Hydrogen absorption associated with the corrosion mechanism of 316L stainless steels in primary medium of Pressurized Water Reactor ( PWR )}},
volume = {85},
year = {2014}
}