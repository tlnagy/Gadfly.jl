# Guide.xrug

Draw a rug plot along the x-axis of a plot.

## Aesthetics
  * `x`: X positions of notches.

## Examples

```@example 1
using Compose # hide
using Gadfly # hide
Gadfly.set_default_plot_size(14cm, 8cm) # hide
```

```@example 1
plot(x=rand(20), y=rand(20), Guide.xrug)
```
