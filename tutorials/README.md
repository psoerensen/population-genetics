# Tutorials

- [Understanding genotype data](genotype_data.qmd): Practical 1, allele coding, missing calls, identity alignment and haplotype phase.
- [Allele frequencies and Hardy–Weinberg expectations](allele_frequencies_hwe.qmd): Practical 2, observed summaries and a random-union model.

- [Population structure, mating and inbreeding](structure_mating_inbreeding.qmd): Practical 3, contrasting mating rules, IBD and population mixtures.

- [Measuring genetic diversity](genetic_diversity.qmd): Practical 4, heterozygosity, finite-sample correction and nucleotide diversity.

- [Mutation, migration and linkage disequilibrium](mutation_migration_ld.qmd): Practical 5, allele and haplotype recursions.

- [Genetic drift in finite populations](genetic_drift.qmd): Practical 6, neutral sampling and diversity loss.
- [Selection, fitness and dominance](selection_fitness.qmd): Practical 7, selection expectations and finite realizations.

- [Testing Hardy–Weinberg proportions](testing_hwe.qmd): Practical 8, fitted expectations, degrees of freedom and exact conditional testing.

- [Mutation, selection and drift at balance](mutation_balance.qmd): Practical 9, deterministic recursions and an exact small neutral transition model.

- [Conservation genetics and management choices](conservation_genetics.qmd): Practical 10, contributions, kinship, marker diversity and budgets.
- [DNA profiles and match probabilities](dna_match_probabilities.qmd): Practical 11, multi-allelic genotypes, population structure and evidence interpretation.
- [Sequence divergence and the molecular clock](molecular_clock.qmd): Practical 12, substitution distance, rate units and calibration.
- [Disease alleles, penetrance and population risk](disease_alleles_penetrance.qmd): Practical 13, genotype-specific phenotype probabilities and conditioning.

- [Selective sweeps and genetic hitchhiking](selective_sweeps.qmd): Practical 14, two-locus dynamics, recombination and interpretation.
- [Coalescent history and sampled variation](coalescent_history.qmd): Practical 15, genealogy simulation, branch mutations and demographic expectations.

All use base R and hypothetical data, with no required downloads or package installations. gpop links refer to its existing teaching examples, not proposed scientific APIs.

Render an individual page from the repository root:

```text
quarto render tutorials/genotype_data.qmd
quarto render tutorials/allele_frequencies_hwe.qmd
```
