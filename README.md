# CONSTRUCTING-A-PHYLOGENETIC-TREE-of-INSULIN-CLUSTAL-OMEGA-TOOL
CONSTRUCTING-A-PHYLOGENETIC-TREE-of-INSULIN-CLUSTAL OMEGA-TOOL
💉 Insulin Chain Phylogenetic Analysis (Clustal Omega)

This repository contains the results of a multiple sequence alignment (MSA) and phylogenetic analysis for a set of Insulin A and B chains, generated using the EMBL-EBI Clustal Omega tool. The goal is to examine the sequence conservation and evolutionary relationships among these specific chains from different PDB structures.

📁 Repository Contents
Filename,Description,Source
clustalo-I20250718-072312-0155-59470595-p1m.fa,Input FASTA File containing 10 Insulin A and B chain sequences (identified by PDB ID and chain). ,Input
Clustal Omega _ EMBL-EBI TOOL OUPUT.pdf / Clustal Omega _ EMBL-EBI ALIGMENTS.pdf,"Multiple Sequence Alignment (MSA) output in CLUSTAL format, showing sequence similarity. ",Output
clustalo-I20250718-072312-0155-59470595-p1m.phylotree / clustalo-I20250718-072312-0155-59470595-p1m.tree,"Newick format of the Phylogenetic Tree (Guide Tree), detailing branch lengths. ",Output
GUIDE TREE PHYLOGRAM Insulin Clustal omega tool.png / Clustal Omega _ EMBL-EBI PHYLOGENETIC TREE.pdf,Graphical representations of the Phylogenetic Tree (Phylogram and Radial view). ,Output
clustalo-I20250718-072312-0155-59470595-p1m-submission.xml,"XML file detailing the Clustal Omega execution parameters (e.g., seqtype: protein, outfmt: clustal_num). ",Execution Details
🧬 Alignment and Conservation

The Multiple Sequence Alignment (MSA) clearly demonstrates the high conservation within the two main functional parts of the Insulin protein: the A chain and the B chain.

1. Insulin A Chains (PDB ID Chain 1)

    Sequences: 3I40_1, 1ZNI_1, 4INS_1, 4E7U_1, 5JYQ_1.

High Conservation: The first four A chains (3I40_1, 1ZNI_1, 4INS_1, 4E7U_1) show near-perfect identity, with the only variation being the substitution of Cysteine (C) to Serine (S) at position 10 in 4E7U_1 (CCTSICSLY→CCASVCSLY).

Divergence: Sequence 5JYQ_1 (GVVEHCCHRPCSNAEFKKYC) is the most divergent in this group, particularly lacking sequence similarity at the beginning and middle compared to the others.

2. Insulin B Chains (PDB ID Chain 2)

    Sequences: 3I40_2, 4E7U_2, 1ZNI_2, 4INS_2, 5JYQ_2.

High Conservation: The first four B chains (3I40_2, 4E7U_2, 1ZNI_2, 4INS_2) are identical or nearly identical (FVNQHLCGSHLVEAL-YLVCGERGFFYTPKA).

Divergence: Sequence 5JYQ_2 (TFDTPKHRCGSEITNSY-MDLCYR) is highly divergent from the other four B chains.

🌳 Phylogenetic Tree Analysis

The phylogenetic tree confirms the functional and structural grouping by clearly separating the sequences into two distinct clades (A and B chains), with the highly conserved sequences collapsing to nodes with zero branch length.

1. A Chain Clade (PDB ID Chain 1)

    Core Group: 3I40_1, 1ZNI_1, and 4INS_1 form an initial node with zero branch length.

Slightly Divergent: 4E7U_1 splits off with a short branch length (0.047619), consistent with the single amino acid substitution observed in the MSA.

Outlier: 5JYQ_1 is the most divergent sequence within the A chain clade (0.275 to the internal node), confirming its highly distinct sequence composition.

2. B Chain Clade (PDB ID Chain 2)

    Core Group: 3I40_2, 4E7U_2, 1ZNI_2, and 4INS_2 collapse to a single node with zero branch length, confirming their absolute sequence identity in the aligned region.

Divergent: 5JYQ_2 is the outlier in this clade, with a branch length of 0.391304.

Overall Topology

The tree structure demonstrates the strong evolutionary pressure to maintain the structure of the Insulin A and B chains, as evidenced by the groups of identical sequences. The divergence of the 5JYQ chains suggests they represent a significantly different Insulin type or species than the other four PDB structures.

💻 Methods and Citation

Tool Execution Details

    Program: Clustal Omega (Multiple Sequence Alignment).

Version: 1.2.4.

Output Format: CLUSTAL with residue numbering (clustal_num).

Sequence Type: Protein.

Citation

If you utilize this analysis in your work, please cite the Clustal Omega publication:

    Sievers F, et al. (2011). Fast, scalable generation of high-quality protein multiple sequence alignments using Clustal Omega. Molecular Systems Biology, 7(1): 539.
