# combinatorial-auction
Comb-auction paper (ACM EC format).

- `main.tex` — the paper: model, deterministic bound without IIG, randomized mechanism (greedy with a random reserve on randomly surviving goods).
- `archive/main-single-proof.tex` — snapshot: first version of the randomized section, one theorem with one long proof (11 pages).
- `archive/main-certificate-proof.tex` — snapshot: same mechanism as main.tex, false-name proof via a quadratic payment certificate instead of the cover inequality.
- `archive/main-abstract-theorems.tex` — snapshot: Section 5 built on general theorems (thinning, admissible reserve laws), 16 pages.
- `archive/old-randomized-priority-sampler.tex` — the previous randomized mechanism (ℓ_q load program + priority sampler), kept verbatim; compiles standalone.
- `acmart.cls`, `acm-ec-26.sty`, `ACM-Reference-Format.bst` — EC template files.
