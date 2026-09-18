# Barfoot exercises

Solutions to the exercises from Timothy D. Barfoot, *State Estimation for Robotics* (Second Edition): https://asrl.utias.utoronto.ca/~tdb/

Notebooks in `notebooks/` go one per chapter. Each exercise has the problem statement, a derivation, and a numerical check in Julia.

## Run

```bash
julia --project=. -e 'using Pkg; Pkg.instantiate()'
```

Open the notebooks in Jupyter with the Julia kernel. CI runs every notebook top to bottom, and any failing `@assert` fails the build.
