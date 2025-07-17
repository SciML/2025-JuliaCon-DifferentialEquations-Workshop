# JuliaCon 2025 OrdinaryDiffEq deepdive


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
