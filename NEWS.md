# barmixR 0.99.3

## Bug fixes

- Updated Stan models to the new array syntax (`array[] int` etc.),
  fixing build and install failures with recent Stan compilers.
- Renamed the internal Dirichlet-multinomial functions in the barcode
  model to `barmix_dm_lpmf()`/`barmix_dm_rng()` to avoid a name clash
  with the built-in `dirichlet_multinomial` added in Stan 2.34. Results
  are unchanged.

# barmixR 0.99.0

## New features

- Initial Bioconductor submission.
- Bayesian framework for barcode mixture modeling.
- Joint modeling of barcode composition and population size.
- Posterior predictive diagnostics for barcode composition and population size.
- Estimation of quantitative treatment resistance (QTR).
