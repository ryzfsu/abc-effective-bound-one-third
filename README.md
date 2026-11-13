# Improving the Stewart-Yu bound for all abc triples

Ruiyi Zhang

For coprime positive integers `a + b = c`, write `R = rad(abc)`. The manuscript proves

    log c < A R^(1/3) exp(-log R / (3000 log log R)),

with an absolute, effectively computable constant `A`. Equivalently,
`log c < A R^(1/3 - 1/(3000 log log R))`, where the exponent tends to `1/3` from below.
This improves the Stewart-Yu bound `log c << R^(1/3) (log R)^3` (Duke Math. J. 108 (2001)).
It is a sub-power saving: no fixed exponent below `1/3` is claimed.

The proof combines estimates at the maximal prime powers of `a`, `b` and `c` with a growing
number of auxiliary primes in a rational p-adic logarithmic form, following Stewart's
construction (Acta Math. 211 (2013)) and Yu's p-adic estimate (Acta Math. 211 (2013)).

## Contents

- `main.pdf` (8 pages)
- `source/` - LaTeX source: `manuscript.tex`, `references.bib` and the generated `manuscript.bbl`
- `LICENSE.md`, `LICENSES/`
- `SHA256SUMS`

## Build

    cd source
    xelatex manuscript.tex
    bibtex manuscript
    xelatex manuscript.tex
    xelatex manuscript.tex

With the supplied `manuscript.bbl`, two XeLaTeX runs suffice.

## License

Text: CC BY 4.0. See `LICENSE.md`.
