# Assignment_02_Genome_Exploration
Genome exploration and assembly analysis of _Canis lupus_ using Galaxy.

# Genome Exploration of _Canis lupus_

_Species and Genome Information_

Species: _Canis lupus_

NCBI Assembly accession: GCA_905319855.2

Assembly level: Chromosome

Genome source: NCBI

FASTA filename: Canis_lupus.fasta

Approximate file size: 2.45 GB

# Objective

The objective of this activity was to explore the Canis lupus genome assembly using Galaxy. The activity focused on examining basic assembly statistics, sequence lengths, the effect of filtering short sequences, and the presence of possible open reading frames (ORFs).

# Tools Used and Important Settings

**Part 2:** Fasta Statistics

The tool was used to obtain the total assembly length, number of sequences, minimum and maximum sequence length, mean sequence length, N50, L50, and GC content.

<img width="1763" height="916" alt="image" src="https://github.com/user-attachments/assets/bc2e49e2-271b-4df9-a7ac-6152e3026f00" />
Figure 2. Assembly Statistics of the Canis lupus genome generated using Fasta Statistics tool.


**Part 3:** Compute sequence length

This tool was used to determine the length of each FASTA sequence. The five longest sequences were identified and recorded.

<img width="1865" height="1116" alt="image" src="https://github.com/user-attachments/assets/0e0aa37e-13d8-44ee-9688-47f3cea0eb74" />
**Figure 2. **Results of the Compute Sequence Length tool showing the lengths of the Canis lupus genome sequences.

# Important Results

The genome had a total assembly length of approximately 2.45 Gb. The scaffold N50 was 65.78 Mb, with an L50 of 15, while the longest scaffold was approximately 124.67 Mb. The GC content was 41.49%.

Filtering sequences below 10 kb did not change the main assembly statistics because the shortest sequence in the original assembly was already 16,690 bp. Therefore, there were no sequences below the 10-kb filtering cutoff.

The ORF analysis found 206 ORFs, with the longest being 3,441 bp. This demonstrated that genome sequences can contain regions that could potentially code for proteins, but an ORF is not automatically a real gene and requires additional evidence for confirmation.

# Short Interpretation

The results suggest that the Canis lupus genome assembly contains many long sequences, including very long scaffolds. The N50 and L50 values indicate that a large part of the genome is contained in a relatively small number of long scaffolds. The filtering experiment showed that sequences shorter than 10 kb were not present in the assembly, so removing them did not affect the main statistics. The ORF analysis showed that the genome contains regions that may potentially code for proteins, but these regions cannot automatically be considered real genes without additional evidence.

# Galaxy History

A screenshot of the Galaxy History showing the analysis steps


