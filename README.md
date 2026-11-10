# ComputationalThinkingforClimate.jl
MIT 6.C25[J] Real World Computation with Julia: Climate Science

## Opening a notebook

Install [Julia](https://julialang.org/downloads/), then run this from the repository folder:

```
julia --project -e 'using Pkg; Pkg.instantiate(); using Pluto; Pluto.run()'
```

Pluto opens in your browser. Enter the path of a notebook (for example `radiative_balance.jl`) and click **Open**. Each notebook installs its own packages the first time it runs, so the first run can take a few minutes.
