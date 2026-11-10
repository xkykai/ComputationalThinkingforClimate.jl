# ComputationalThinkingforClimate.jl
MIT 6.C25[J] Real World Computation with Julia: Climate Science

## Opening a notebook

Install [Julia](https://julialang.org/downloads/), then clone this repository and start Julia in it:

```
git clone https://github.com/xkykai/ComputationalThinkingforClimate.jl
cd ComputationalThinkingforClimate.jl
julia --project
```

In Julia, run:

```julia
using Pkg; Pkg.instantiate()  # first time only
using Pluto; Pluto.run()
```

Pluto opens in your browser. Enter the path of a notebook (for example `radiative_balance.jl`) and click **Open**. Each notebook installs its own packages the first time it runs, which can take several minutes.
