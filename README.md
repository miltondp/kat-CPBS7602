# Readme for each assignment:
## Assignment 01 
To make the environment for CPBS7602, use the conda environment yaml file in CPBS7602/envs named "cpbs7602_environment_assignment01.yml"
```
conda env create -f "cpbs7602_environment_assignment01.yml" -n "cpbs7602_assignment01"
```
Then go to the folder assignments/01_assignment. 
You'll need to download the following files from GTEx into the 01_assignment folder prior to running 01_preprocessing.ipynb:
- GTEx_Analysis_v8_Annotations_SampleAttributesDS.txt
- GTEx_Analysis_2017-06-05_v8_RNASeQCv1.1.9_gene_tpm.gct.gz

Then run the following juypter notebooks: 
1. 01_preprocessing.ipynb: processing the metadata and data files from GTEx for clustering analyses.
2. 02_clustering.ipynb: generates the clustering results and analyses 
