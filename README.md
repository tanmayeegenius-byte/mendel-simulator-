# Mendel simulator

Interactive Mendelian genetics simulator: build monohybrid and dihybrid crosses, view Punnett squares, and compare random offspring against expected ratios.

**Live demo:** https://YOUR-USERNAME.github.io/mendel-simulator/

## What it does

- Pick a genotype for each parent (RR, Rr or rr) for seed shape.
- Optionally add seed color (YY, Yy or yy) to run a two-trait (dihybrid) cross.
- See the Punnett square update live, with expected phenotype ratios.
- Breed any number of random offspring (up to 100,000) and compare observed counts with the expected percentages.
- Check the result with a chi-square test against the expected ratio.

## Traits

| Trait | Dominant | Recessive |
|-------|----------|-----------|
| Seed shape | Round (R) | Wrinkled (r) |
| Seed color | Yellow (Y) | Green (y) |

## Run it locally

No build step or dependencies. Download `index.html` and open it in a browser.

The page loads the Fraunces and Inter fonts from Google Fonts. Offline, it falls back to system fonts and still works.

## Ideas for later

- Incomplete dominance and codominance
- Sex-linked traits
- Multi-generation crosses (F1 to F2)
- Custom traits and allele names

## License

MIT
