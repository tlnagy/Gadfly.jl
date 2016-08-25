# Geom.violin

Draw violin plots.

## Aesthetics

Aesthetics used directly:

  * `x`: Group categorically on the X-axis
  * `y`: Y-axis position.
  * `width`: Density at a given `y` value.

With the default statistic [Stat.violin](@ref), only the following need be defined:

  * `x` (optional): Group categorically on the X-axis.
  * `y`: Sample from which to draw the density plot.


## Examples

```@example 1
using RDatasets # hide
using Gadfly # hide
Gadfly.set_default_plot_size(14cm, 8cm) # hide
```

```@example 1
plot(dataset("lattice", "singer"), x="VoicePart", y="Height", Geom.violin)
```
