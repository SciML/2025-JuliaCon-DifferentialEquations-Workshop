# JuliaCon 2025: A Deep Dive Into DifferentialEquations.jl

[See the built version of the workshop notes!](https://sciml.github.io/2025-JuliaCon-DifferentialEquations-Workshop/)

## Rendering

Install dependencies with

```julia
import Pkg
Pkg.instantiate()
```

Make sure Quarto is installed correctly with

```julia
using quarto_jll
run(`$(quarto()) check install`)
```

Then, if all is good you can render the presentation locally with

```julia
run(`$(quarto()) render index.qmd`)
```
