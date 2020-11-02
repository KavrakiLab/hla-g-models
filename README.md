# Structural modeling and molecular dynamics of the immune checkpoint molecule HLA-G

Authors: Thais Arns<sup>1</sup>, Dinler Antunes<sup>2</sup>, Jayvee R. Abella<sup>2</sup>, Maurício Menegatti Rigo<sup>2</sup>, Lydia Kavraki<sup>2</sup>, Silvana Giuliatti<sup>3</sup>, Eduardo Antônio Donadi<sup>1</sup>.

<sup>1</sup> Department of Basic and Applied Immunology, Ribeirão Preto Medical School, University of São Paulo, Brazil.\
<sup>2</sup> Department of Computer Science, Rice University, Houston, TX 77005 USA. \
<sup>3</sup> Department of Genetics, Ribeirão Preto Medical School, University of São Paulo, Brazil.\
\* Corresponding Author: eadonadi@usp.br

This work was submitted to Frontiers in Immunology and the following structural models were included as supplementary material.

## Stable structural models

* HLA-G1_membrane-bound-monomer.pdb
* HLA-G1_membrane-bound-monomer_bilayer.pdb
* HLA-G1_soluble-dimer.pdb    
* HLA-G5_monomer_pep_b2m.pdb

## Unstable structural models

* HLA-G5_monomer.pdb
* HLA-G5_monomer_pep.pdb

## Protein-Protein docking models (ClusPro)

* ClusPro_ILT4-HLA-G1_monomer.pdb
* ClusPro_ILT4-HLA-G1_soluble-dimer.pdb

## Peptide-docking models (APE-Gen)

* ApeGen_RIIPRHLQL-HLAG1_openmm-em.pdb
* ApeGen_RLPKDFRIL-HLAG1_openmm-em.pdb

## Molecular Dynamics Simulation Videos

* HLA-G5 Monomer Simulation Video (file G5_monomer_r1.mpg).
* HLA-G5 Monomer and nonapeptide Simulation Video (file G5_pep_r1.mpg).
* HLA-G5 Monomer, nonapeptide and coupled β2-microglobulin Simulation Video (file G5_pep_beta_r1.mpg).

### Visualizing structures with NGLview

First, clone this repo using one of the following commands:

    git clone git@github.com:KavrakiLab/hla-g-models.git
    https://github.com/KavrakiLab/hla-g-models.git
    
Second, install Jupyter and NGLview using conda

    conda create --name nglview python=3.7
    conda activate nglview
    conda install -c conda-forge jupyter nglview
    jupyter-nbextension enable --py --sys-prefix widgetsnbextension
    jupyter-nbextension enable nglview --py --sys-prefix
    conda install -c conda-forge lxml
    
Third, enter the folder, open and run the notebook

    cd hla-g-models
    jupyter notebook Visualizing_HLA-G_structures.ipynb
