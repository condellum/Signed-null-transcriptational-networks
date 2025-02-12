# Signed-null-transcriptional-networks
**Master project for the Systems Biology course (Master in Physics of Complex Systems at IFISC-UIB): Exploring Signed Null Models in Transcriptional Networks through Motif Analysis.**

Transcriptional regulation networks are a type of biological network that describes the interactions between regulators and their target genes. These networks are essential for understanding the regulation of gene expression and the control of cellular processes. In this project, we analyze the transcriptional regulation network of Escherichia coli (E. coli) K-12, a model organism widely used in microbiological research.

The network comprises three types of interactions: regulators and genes, regulators and transcriptional units, and regulators and other regulators. Regulators are proteins that control the expression of genes by binding to specific DNA sequences. Genes are DNA sequences that encode proteins, and transcriptional units are groups of genes transcribed together. The interactions between regulators and genes/transcriptional units can be positive (activator), negative (repressor), dual (both activator and repressor), or unknown. The interactions are also classified by their confidence level, which can be confirmed as strong, weak, or unknown.

The network study is done by analysing motifs, which are small subgraphs that appear more frequently in the network than expected by chance. Motifs are important because they can provide insight into the function of the network and the regulatory circuits that are present. In this project, we focus on 3-node motifs, which are connected subgraphs of three nodes. We analyze the motif occurrences in the network and compare them to different null models to assess their significance, highlighting the importance of choosing appropriate models for accurate interpretation and how this is linked to the signed nature of transcription networks.

<p align="center">
  <img src="https://github.com/user-attachments/assets/bca12c4d-d520-46c8-9cba-1f07585fdd19" alt="image" width="550"/>
</p>

## Repository Structure

```plaintext
Protein-configurations/
├── data/
│   └── NetworkRegulatorGene.csv  # regulatory network interactions between regulators and their regulated genes
│   └── NetworkRegulatorRegulator.csv  # regulatory network interactions between regulators and other regulators
│   └── NetworkRegulatorTU.csv  # regulatory network interactions between regulators and their regulated transcriptional units      
├── notebooks/
│   └── main_notebook_syst_bio.ipynb  # Code for obtaining the results
└── results/
    └── report_sist_bio.pdf  # Detailed explanation of methodology and results

