# Combine 3 parameters for describe jitter in 2D, each parameter has two posible levels.

Combine 3 parameters for describe jitter in 2D, each parameter has two
posible levels.

## Usage

``` r
compute_jitter2D(
  data,
  noise = "quasi",
  dir = "global",
  weight = NULL,
  bw = 0.5,
  seed = NA
)
```

## Arguments

- noise::

  Random or Quasirandom

- dir::

  Global or Local

- Voronoi::

  True or False (not implemented yet)

- weight::

  spread factor (copied from ggplot2::geom_jitter, not used)

- bw::

  bandwidth for kernel in local correlation

- seed::

  simulation seed (copied from ggplot2::geom_jitter, not used)
