Shonit Nair Sharma
20.440 PSET 4

20.440 Project Team: Daniel Gray Pascal, Shonit Nair Sharma

This file describes documentation sufficient to understand and reproduce the analysis conducted and generate one figure from the 20.440 project.

-----

OVERVIEW
The repository contains code that generates a figure from a dataset. Specifically, the the code takes the data file containing the E. coli Nissle genome and creates a histogram of the percentage breakdown of nucleotide bases (A, T, C, G) from it. The code was written by the project team. The analysis methods are standard and the code is well explained by comments.

-----

DATA
The 'E. coli Nissle Genome.gbff' file in the Data folder is the Celera assembled RefSeq E. coli Nissle 1917 Annotated Genome. The dataset was acquired from a public source (https://www.ncbi.nlm.nih.gov/assembly/GCF_000714595.1). The annotations were added by the NCBI Prokaryotic Genome Annotation Pipeline.

-----

FOLDER STRUCTURE
The folder structure of the repository is the following:

     20.440-pset4                                    # The repository.
     ├── Code                                        # Folder containing code.
     │   └── sharma_shonit_pset4.ipynb               # Code to conduct the analysis and generate the figure.
     │  
     ├── Data                                        # Folder containing data.
     │   └── E. coli Nissle Genome.gbff              # Dataset described above in DATA.
     │  
     ├── Figures                                     # Folder containing figures.
     │   └── Distribution of Nucleotide Bases.png    # Figure generated from the code.
     │  
     ├── .gitattributes                              # Gives attributes to pathnames.
     │  
     ├── .gitignore                                  # Specifies intentionally untracked files.
     │  
     └── README.md                                   # This documentation.

-----

INSTALLATION
The code can be run in the Visual Studio Code program (downloaded here: https://code.visualstudio.com/). The code was run successfully on Python 3.7.9.