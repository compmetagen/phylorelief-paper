Scripts and data for "Explaining Diversity in Metagenomic Datasets by Phylogenetic-Based Feature Weighting"
===========================================================================================================

Data folder
-----------
Each (sub)folder contains the following files:
 * otu_table.txt: the OTU table (rarefied) file
 * sample_data.txt: the file containing the sample metadata
 * taxonomy.txt: the file containing the taxonomy information for each OTU
 * tree.tre: the phylogenetic tree in newick format

Script folder
-------------

The script folder contains the machine learning pipelines used in the paper.
The scripts require Python >= 2.7, the NumPy, SciPy, Pandas, DendroPy, 
scikit-learn libraries and the PhyloRelief software. `ml_lefse` requires the 
LEfSe software (https://bitbucket.org/nsegata/lefse). Moreover, you neeed to 
set the variable `lefse_path` inside the script. `ml_metaphyl` requires the 
MetaPhyl software (http://www.cs.ucr.edu/~tanaseio/metaphyl.htm). Moreover, 
you neeed to set the variable `metaphyl_path` inside the script.
Run `script_name --help` for additional information.
