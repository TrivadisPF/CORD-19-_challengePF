# CORD19 challenge Code
This is the repository to store all infrastructure related items to the challenge team.


## Prerequisites
A working infrastructure like described in: https://github.com/TrivadisPF/CORD-19-_challengePF_infra

## importing the data
the read_json.ipynb reads in the data as provided by kaggle. Currently the configuration expects the data to be "two levels deep". This represents the data after unzipping it from kaggle. Also the partitioning of the data in the different folders (biorxiv_medrxiv,comm_use_subset, noncomm_use_subset, pmc_custom_license) has been kept
