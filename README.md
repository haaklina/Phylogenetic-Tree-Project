Title: Morphological and genetic characterization of outer coast ascidians in central California (CA).
Abstract
Ascidians play an important role in the invertebrate ecology of California aquatic ecosystems. In addition, they have a great contribution in medical science. Bays are full of nonindigenous and some native ascidians that are under investigation to learn their existence. The central coast of California remains understudied since it has been dominated by native species, although the problematic invasive didemnid is threatening to escape from San Francisco Bay to the outer coast at this time. It is significant to identify in this region which species are present on the outer coast, and to update taxonomic analyses with additional reproductive characters, habitat and distributional characters, and molecular information.

Problem statement
The ascidians species have a similar colony and zooid outlook, which is why it can be challenging to distinguish them by using identification keys which nearly provided an ambiguous result.
Main points
• Zooids outlook similar
• Molecular and morphological context
• Evolution of major native and non-native species.
Research Questions
The present proposal describes the project that I wish to undertake in order to contribute to finding a solution to these questions/problems: what are the morphological and reproductive patterns of ascidian species? Why are the characteristics influenced by distribution of outer bay species? What species are located on outer coast and which morphological characteristics are used to define them as well as what is currently reported as being on coast?
Research Objectives
The main objective is to reassess tunicate species diversity in central CA by combining varied kinds of data, including molecular, morphological, ecological, and historic information. All these investigations will specify what species are, where and when they were recently present, and assist
in defining accurate species identification.
Scope of Research
Exploring ascidians is instrumental in identifying its role in the invertebrate ecology of California aquatic ecosystems. They are recognized as an important model organism in innate immunity studies. Ascidian species have played a significant part as a natural source for curing cancer diseases in the modern medicine pavilion.

Phylogenetic-Tree-Project

> Data
> Sequences.fasta (Gene sequences from NCBI)
> Tree_data.nexus  (Nexus file for tree generation)

> Output           (Analysis output (trees, plots)

> Scripts                     (Analysis scripts)
> Phylo_analysis.Rmd       (R Markdown for loading and analysis)

> Dataset_card.md              (Dataset card for context)
> README.md                    (Project overview and instructions)

I am getting started
Prerequisites
•	R or RStudio (for analysis scripts)
•	Required R packages: ape, phangorn, seqinr
Installation
1.	Clone the repository:
2.	git clone https://github.com/yourusername/Phylogenetic-Tree-Project.git
cd Phylogenetic-Tree-Project
3.	Install necessary R packages (if not already installed):
4.	install.packages("ape")
5.	install.packages("phangorn")
install.packages("seqinr")
Usage
Running the Analysis
1.	Load the data and scripts:
2.	# Load packages
3.	library(ape)
4.	library(phangorn)
5.	library(seqinr)
6.	
7.	# Read data
8.	fasta_data <- read.fasta("data/sequences.fasta")
nexus_data <- read.nexus("data/tree_data.nexus")
9.	Perform phylogenetic tree construction and visualization.
Output
•	The /output directory will contain generated phylogenetic trees, sequence alignments, and plots.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with proposed changes.
License
This project adheres to open-access policies. Refer to NCBI's data usage policy for licensing and attribution requirements.
Contact
For questions or collaboration opportunities, please contact haaklina or Hasna Akther.
![image](https://github.com/user-attachments/assets/0fcacd56-73e2-4880-8599-0eeaf245cf1c)
