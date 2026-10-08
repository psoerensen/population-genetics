# Population Genetics

Standalone Quarto- and R-based teaching materials for population genetics.

Published website: <https://psoerensen.github.io/population-genetics/>

Teaching-materials hub: <https://psoerensen.github.io/qgteach/>

## Repository Structure

```text
population-genetics/
  _quarto.yml
  index.qmd
  slides/
  notes/
  tutorials/
  exercises/
  apps/
  data/
  images/
  narration/
  scripts/
  R/
  tools/
  docs/
```

The active Quarto source files are:

```text
index.qmd
slides/introduction_population_genetics.qmd
slides/introduction_population_genetics_narrated.qmd
```

## Conservation practical

[Tutorial 10](tutorials/conservation_genetics.qmd) compares parental contributions, mating, expected inbreeding and marker heterozygosity under a hypothetical budget. It uses base R and requires no downloads.

## DNA-profile practical

[Tutorial 11](tutorials/dna_match_probabilities.qmd) uses hypothetical allele frequencies to explore profile probabilities, population structure and source likelihood ratios. It uses base R and requires no downloads.

## Molecular-clock practical

[Tutorial 12](tutorials/molecular_clock.qmd) explores sequence differences, Jukes–Cantor distance and clock calibration using hypothetical inputs and base R.

## Included Apps

The repository includes these R/Shiny app source files:

- `apps/drift_simulation.R`
- `apps/GenePool_HWE_Simulator.R`
- `apps/hwe_simulation.R`
- `apps/HWE_Test_Simulator.R`
- `apps/Migration_Admixture_Simulator.R`
- `apps/Selection_Simulator.R`
- `apps/Selective_Sweep_Simulator.R`

The apps are provided for local use and are not configured for deployment.

## Additional Unaudited Assets

These population-genetics image assets were copied for later review but are not currently referenced by the slides:

- `images/domestication.webp`
- `images/haplotypes.webp`
- `images/molecular_clock.png`
- `images/nucleotide_diversity.png`

## Requirements

Rendering and running the teaching materials requires:

- Quarto
- R

R package dependencies used by the slides, apps, or plotting helper include:

- `shiny`
- `ggplot2`
- `ape`
- `dplyr`
- `gganimate`
- `patchwork`
- `tidyr`
- `kinship2`
- `MCMCpack`

The narration tool additionally uses:

- `stringr`
- `fs`
- `jsonlite`

Generating narration requires `OPENAI_API_KEY`, `curl`, and network access. Obtain explicit approval before regenerating audio.

## Rendering

Render focused slide files:

```bash
quarto render slides/introduction_population_genetics.qmd
quarto render slides/introduction_population_genetics_narrated.qmd
```

Render the complete course website:

```bash
quarto render
```

Generated website files are written to `docs/`.
