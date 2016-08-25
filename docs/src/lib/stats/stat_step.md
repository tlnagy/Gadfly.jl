# Stat.step

Perform stepwise interpolation between points. If `x` and `y` define a a series
of points, a new point in inserted between each. Between `(x[i], y[i])` and
`(x[i+1], y[i+1])`, either `(x[i+1], y[i])` or `(x[i], y[i+1])` is inserted,
depending on the `direction` argument.

## Aesthetics

  * `x`: Point x-coordinate.
  * `y`: Point y-coordinate.

## Arguments

  * `direction`: Either `:hv` for horizontal then vertical, or `:vh` for
    vertical then horizontal.


```@example 1
using Gadfly # hide
Gadfly.set_default_plot_size(12cm, 8cm) # hide
srand(1234) # hide
nothing # hide
```

```@example 1
plot(x=rand(25), y=rand(25), Stat.step, Geom.line)
```
