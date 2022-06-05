# BIMM143project2

Hi! This is the first draft of Hillary's Project 2 for BIMM143.  

Files in this repository:  
1. Project 2 R Notebook - this file contains the code to run the experiment
2. Project 2 HTML - this contains the R Markdown and code when run on Hillary's laptop  
3. vaginolysin_AA.txt - these are amino acid sequences for the vaginolysin proteins from *Gardnerella vaginalis* strains ATCC14018, ATCC14019, and 409-05 
4. 14018vly_fromily.pdb - pdb files of *Gardnerella vaginalis* strain ATCC14018 vaginolysin protein inferred from intermedilysin 1S3R using SWISS-MODEL
5. 14019vly_fromily.pdb - pdb files of *Gardnerella vaginalis* strain ATCC14019 vaginolysin protein inferred from intermedilysin 1S3R using SWISS-MODEL
6. 409_05vly_fromily.pdb - pdb files of *Gardnerella vaginalis* strain 409-05 vaginolysin protein inferred from intermedilysin 1S3R using SWISS-MODEL

## Data for the analysis was downloaded from the following links:  
*Gardnerella vaginalis* strain ATCC14018   
[ATCC14018 amino acids](https://www.ncbi.nlm.nih.gov/protein/ACD39459.1?report=fasta)  

*Gardnerella vaginalis* strain ATCC14019     
[ATCC14019 amino acids](https://www.ncbi.nlm.nih.gov/protein/ACD39460.1?report=fasta)  

*Gardnerella vaginalis* strain 409-05  
Can’t find a link for the 409-05 vaginolysin gene on NCBI  
[409-05 DNA and amino acids](https://www.genome.jp/entry/gva:HMPREF0424_0103)  

**Scientific Question:** Are there structural/functional differences in the vaginolysin protein in Gardnerella strains ATCC14018 and ATCC14019 from women with symptomatic bacterial vaginosis (BV) and strain 409-05 from women with asymptomatic BV that impact the outcome of disease pathogenesis?  

**Scientific Hypothesis:** If the vaginolysin protein sequence between strains ATCC14018 and ATCC14019 in comparison to strain 409-05 shares less than a 80% sequence identity, then there are structural/functional differences in the vaginolysin protein in Gardnerella strains from women with symptomatic bacterial vaginosis and from women with asymptomatic bacterial vaginosis.

---
Here, multiple sequence alignment is used to compare sequences of the vaginolysin proteins for strains ATCC14018, ATCC14019, and 409-05. The multiple sequence alignment is visualized with a sequence logo. Protein homology modeling is used to infer the structure of the vaginolysin proteins, and normal modes analysis(NMA) is used to identify differences in the functional motions and structures between the proteins.
