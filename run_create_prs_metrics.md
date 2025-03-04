# Calculate PRS accuracy metrics


## Set variables
Before running please edit *run_create_prs_metrics.sh* with your biobank-specific parameters. Specifically:

 Options:

	--pop=POP
		Target ancestry

	--pheno=PHENO
		Phenotype in the phenotype file

	--K=K
		Disease prevalence

	--covs=COVS
		Covariates included in the prediction model

	--phenofile=PHENOFILE
		Full path to phenotype files (including FID, IID, phenotypes)

	--popfile=POPFILE
		Full path to a file of ids for target population (in the format of FID, IID)

	--prsfile=PRSFILE
		Full path to a *.profile generated by Plink, note using --sum to get the SCORESUM used in this script

	--covfile=COVFILE
		Full path to the file including covariates (with headers including FID, IID and covariates)

	--pcfile=PCFILE
		Full path to the file from PCA analyses (*.eigenvec in the format of FID, IID, PC1:PC10)

	--out=OUT
		Output file for the prs accuracy metrics

	-h, --help
		Show this help message and exit
		
## Run the script

After setting the variables, please run the script.

- bash run_create_prs_metrics.sh








