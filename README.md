# Supplementary information

Supplementary information with the article 'Large-scale genomic characterisation of Bacteroides fragilis reveals multiple functionally divergent lineages and a distinct species.'

## Supplementary Data

### Supplementary Table 1: [Genome metadata](Supplementary_data/Genome_metadata/metadata.tsv)

Overview of the metadata of the filtered 562 _B. fragilis_ genomes used in this study. The metadata includes the following columns:

<details>
<summary>Supplementary Table 1: column names</summary>
    * genome: Genome name <br>
    * organism: Organism name <br>
    * contigs: Number of contigs (Prokka) <br>
    * bases: Number of bases (Prokka) <br>
    * tRNA: Number of tRNA (Prokka) <br>
    * rRNA: Number of rRNA (Prokka) <br>
    * CDS: Number of CDS (Prokka) <br>
    * tmRNA: Number of tmRNA (Prokka) <br>
    * repeat_region: Number of repeat regions (Prokka) <br>
    * OriginalName: Original name of the genome (NCBI) <br>
    * Study_set: Study set of the genome - UHGG| Genbank| RCC <br>
    * GenomeType: Genome type - MAG| Isolate <br>
    * Sample_accession: Sample accession number (NCBI) <br>
    * Country: Country of origin <br>
    * Continent: Continent of origin <br>
    * Host : Host of the sample <br>
    * Source: Source of the sample <br>
    * Disease: Disease associated with patient (if any) <br>
    * SamplingDate: Date of sampling <br>
    * Latitude: Latitude of origin <br>
    * Longtitude: Longtitude of origin <br>
    * contigs_0_bp: Number of contigs with more then 0 bp (Quast) <br>
    * contigs_1000_bp: Number of contigs with more then 1000 bp (Quast) <br>
    * contigs_5000_bp: Number of contigs with more then 5000 bp (Quast) <br>
    * contigs_10000_bp: Number of contigs with more then 10000 bp (Quast) <br>
    * contigs_25000_bp: Number of contigs with more then 25000 bp (Quast) <br>
    * contigs_50000_bp: Number of contigs with more then 50000 bp (Quast) <br>
    * Total_length_0_bp: Total number of bases in contigs with more then 0 bp (Quast) <br>
    * Total_length_1000_bp: Total number of bases in contigs with more then 1000 bp (Quast) <br>
    * Total_length_5000_bp: Total number of bases in contigs with more then 5000 bp (Quast) <br>
    * Total_length_10000_bp: Total number of bases in contigs with more then 10000 bp (Quast) <br>
    * Total_length_25000_bp: Total number of bases in contigs with more then 25000 bp (Quast) <br>
    * Total_length_50000_bp: Total number of bases in contigs with more then 50000 bp (Quast) <br>
    * N_contigs: Number of contigs (Quast) <br>
    * Largestcontig: Length of the largest contig (Quast) <br>
    * Total_length: Total number of bases of the assembly (Quast) <br>
    * GC: GC % of the assembly (Quast) <br>
    * N50: N50 of the assembly (Quast) <br>
    * N75: N75 of the assembly (Quast) <br>
    * L50: L50 of the assembly (Quast) <br>
    * L75: L75 of the assembly (Quast) <br>
    * Ns_per_100_kbp: Number of N's per 100 kbp (Quast) <br>
    * Marker_lineage: Used marker lineage (CheckM) <br>
    * Completeness: Completeness of the assembly (CheckM) <br>
    * Contamination: Contamination of the assembly (CheckM) <br>
    * Strain_heterogeneity: Strain heterogeneity of the assembly (CheckM) <br>
    * subdivision: Subdivision of genome, 1 represents _B. fragilis sensu stricto_, 2 represents _B. fragilis A_ <br>
    * lineages: Assigned lineage of the genome, only for subdivision 1 (fastbaps) <br>
    * letter: Assigned letter of the lineag, only for subdivision 1 (fastbaps) <br>
    * color: Lineage color, only for subdivision 1 <br>
</details>

### Supplementary Table 2: Multi locus sequence typing

-   The [standard output](Supplementary_data/Multi_locus_sequence_typing/mlst.stdout) of (MLST)[https://github.com/tseemann/mlst] using the B. fragilis scheme.
-   The [novel alleles](Supplementary_data/Multi_locus_sequence_typing/mlst_novel_alleles.fasta) identified in the MLST analysis.
-   The [lineage associated Sequencing Types](Supplementary_data/Multi_locus_sequence_typing/lineage_ST.tsv).

### Supplementary Table 3: [Lineage specific genes](Supplementary_data/Lineage_specific_genes/lineage_specific_genes.tsv)

An overview table of the lineage specific genes identified in the B. fragilis pangenome. Genes were tested for enrichment using Fisher exact test, q-values are Benjamini & Hochberg corrected and further selected based on the following conditions:

-   Precision (PPV) ≥ 85%: At least 85% of genomes with the gene belong to a single lineage.
-   Sensitivity ≥ 95%: At least 95% of genomes from the designated lineage possess the gene.

Gene annotation columns were identified based on homology search with eggnogDB v5.0.2

### Supplementary Table 4: [Co-occuring Mobile genes](Supplementary_data/Mobile_genes/coinfinder_anno_mobile.tsv)

An overview table of the mobile genes identified in the _B. fragilis_ pangenome. Based on the following conditions:

-   Co-occuring genes were identified with [Coinfinder V.1.0.8](https://github.com/fwhelan/coinfinder)
-   Genomic proximity: at least one genome exhibits inter-gene locus standard deviation ≤ 15 units
-   Lineage distribution: at least one assembly of a lineage harbors ≥ 80% of gene group, but no more than 16 out of 17 lineages contain a assembly with 80% of the gene group.

### Supplementary Table 5: [Drug resistance](Supplementary_data/Drug_resistance/abricate_summary.tsv)

An overview table of the drug resistance genes identified in the _B. fragilis_ strains using [Abricate](https://github.com/tseemann/abricate) and [NCBI AMRFinderPlus v3.10](https://doi.org/10.1128%2FAAC.00483-19).

### Supplementary Table 6: [Distribution pattern _bft_ PAI](Supplementary_data/BFT_PAI/bft_pai_distribution.tsv)

An overview table of the different observed patterns of the mobile genes and fragilysin proteins and ORF IS200 based on blast results. Occurrence patterns are annotated as they were originally defined by [Franco et al. 1999](https://doi.org/10.1128/jb.181.21.6623-6633.1999).

## Supplementary Figures

### Supplementary figure 1

![B fragilis data acquisition](Supplementary_figures/supp_fig_1/Bfragilis_data_acquisition.png)

_**Supplementary Figure 1:** Overview of data preprocessing steps. †Quality control measures are: contamination ≦ 5%, completeness ≧ 90%, 4.25Mbp ≦ genome size ≦ 5.75Mbp, # contigs ≦ 600, N’s per 100kbp ≦ 100. <sup>\*</sup>Final dataset used in downstream analysis, 498 of B. fragilis sensu stricto genomes and 68 B. fragilis A genomes._

### Supplementary figure 2

_**Supplementary Figure 2:**Genome synteny plot visualised within [MAUVE (v2.4.0)](https://darlinglab.org/mauve/mauve.html) using Progressive Mauve with default parameters. B. fragilis sensu stricto genomes GCF_000965785.1 (BOB25) and GCA_000210835.1 (638R), brown box were compared against B. fragilis A genomes GCA_000724815.2 (DCMOUH0085B) and GCA_016864615.1 (DK1985), green box. Homology regions are represented by the same color, the height of the similarity profile represents the average level of conservation between genomes._

### Supplementary figure 3

### Supplementary figure 4

Contribution of recombination over mutation to the sequence divergence in each lineage

### Supplementary figure 5

### Supplementary figure 6

_**Supplementary Figure 5: Two examples of significantly associated gene cluster to lineages.** (**A**)Significantly associated gene cluster of lineage J containing the genes: bshA, bshB_, dxs, tilS, ispD, rmlB, rpiB, strE, tarF and 6 hypothetical proteins. Genes were highlighted within assembly GCF*00856913.1. (**B**) Significantly associated gene cluster of lineage Q containing the genes: tuaB, gmhB, epsM and arnB. Genes are highlighted within GCA_016623685.1 using SnapGene software (www.snapgene.com).*

### Supplementary figure 7

_**Supplementary Figure 6: Comparison of the functional categories across and within lineages.** (**A**) A proportional bar chart for each lineage representing the fraction of COG’s functional categories within the core and accessory genome. (**B**) A Heatmap result of enrichment analysis for comparing the core genome’s COG functional categories with the accessory genome’s COG functional categories coloured by the Benjamini-Hochberg corrected p-value._

### Supplementary figure 8

_**Supplementary Figure 7:** Distribution of significantly associated drug resistance genes to specific lineages (chisq-test), colored by lineage._

### Supplementary figure 9

_**Supplementary Figure 8:** Distribution of all drug resistant genes across the entire B. fragilis sensu stricto population based on the core genome tree._
