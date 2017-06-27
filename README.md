# Galaxy_RAD-Seq

**This repo contains a `.yml` file and a `Dockerfile`.**

- `.yml`: This file have all the required tools, which would be downloaded from [Galaxy Project](github.com/galaxyproject/)
- `Dockerfile`: This docker file will install the `RAD-Seq` flavoured galaxy on your computer.

# Tools included for data analysis:

1. `Stacks_procrad` : the Stacks demultiplexing script.
2. `Stacks_ustacks` : align short reads into stacks.
3. `Stacks_pstacks` : find stacks from short reads mapped to a reference genome.
4. `Stacks_cstacks` : build a catalogue of loci.
5. `Stacks_sstacks` : match stacks to a catalog.
6. `Stacks_statistics` : on stacks found for multiple samples.
7. `Stacks_rxstacks` : make corrections to genotype and haplotype calls.
8. `Stacks_clonefilter` : Identify PCR clones.
9. `Stacks_populations` : analyze a population of individual samples ('populations' program).
10. `Stacks_genotypes` : analyse haplotypes or genotypes in a genetic cross ('genotypes' program).
11. `Stacks_de novo map` : the Stacks pipeline without a reference genome (denovo_map.pl).
12. `Stacks_reference map` : the Stacks pipeline with a reference genome (ref_map.pl).