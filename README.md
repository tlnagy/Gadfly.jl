<div align="center">
<img src="docs/src/assets/logo.svg" alt="Gadfly Logo" width="210"></img>
</div>

| **Documentation**                                                               | **PackageEvaluator**                                            | **Build Status**                                                                                |
|:------------------------:|:-------------------------------------------------------------------------------------:|:------------------------------------------------:|
| [![][docs-stable-img]][docs-stable-url] | [![][pkg-0.4-img]][pkg-0.4-url] [![][pkg-0.5-img]][pkg-0.5-url] | [![][travis-img]][travis-url] [![][codecov-img]][codecov-url] |

**Gadfly** is a plotting and data visualization system written in
[Julia](http://julialang.org/).

It's influenced heavily by Leland Wilkinson's book [The Grammar of Graphics][gog-book]
and Hadley Wickham's refinement of that grammar in [ggplot2](http://ggplot2.org/).

If you use **Gadfly** in a publication please consider citing it: [![DOI][citation-img]][citation-url]

## Package features

- Renders publication quality graphics to SVG, PNG, Postscript, and PDF
- Intuitive and consistent plotting interface
- Works with [IJulia](https://github.com/JuliaLang/IJulia.jl) out of the box
- Tight integration with [DataFrames.jl](https://github.com/JuliaStats/DataFrames.jl)
- Interactivity like panning, zooming, toggling powered by [Snap.svg](http://snapsvg.io/)
- Supports a large number of common plot types

## Installation

**Gadfly** is registered on `METADATA.jl` and so can be installed using `Pkg.add`.

```julia
Pkg.add("Gadfly")
```

## Documentation

- [**STABLE**][docs-stable-url] &mdash; **most recently tagged version of the documentation.**
- [**LATEST**][docs-latest-url] &mdash; *in-development version of the documentation.*

## Contributing and Questions

This is a new and fairly complex piece of software. [File an
issue](https://github.com/dcjones/Gadfly.jl/issues/new) to report a bug,
counterintuitive behavior, or even requesting a feature is extremely valuable in
helping us prioritize what to work on, so don't hestitate.

If you have a question then you can ask for help in the [Gitter chat room][gitter-url].




[docs-latest-img]: https://img.shields.io/badge/docs-latest-blue.svg
[docs-latest-url]: https://dcjones.github.io/Gadfly.jl/latest

[docs-stable-img]: https://img.shields.io/badge/docs-stable-blue.svg
[docs-stable-url]: https://dcjones.github.io/Gadfly.jl/stable

[pkg-0.4-img]: http://pkg.julialang.org/badges/Gadfly_0.4.svg
[pkg-0.4-url]: http://pkg.julialang.org/?pkg=Gadfly
[pkg-0.5-img]: http://pkg.julialang.org/badges/Gadfly_0.5.svg
[pkg-0.5-url]: http://pkg.julialang.org/?pkg=Gadfly

[travis-img]: http://img.shields.io/travis/dcjones/Gadfly.jl.svg
[travis-url]: https://travis-ci.org/dcjones/Gadfly.jl
[codecov-img]: http://img.shields.io/coveralls/dcjones/Gadfly.jl.svg
[codecov-url]: https://coveralls.io/r/dcjones/Gadfly.jl

[citation-img]: https://zenodo.org/badge/6322/dcjones/Gadfly.jl.png
[citation-url]: http://dx.doi.org/10.5281/zenodo.11876

[gog-book]: http://www.cs.uic.edu/~wilkinson/TheGrammarOfGraphics/GOG.html

[gitter-url]: https://gitter.im/dcjones/Gadfly.jl
