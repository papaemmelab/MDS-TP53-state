# Get the data


## Structure

* :page_with_curl: **`dd_clinical_cyto_chr17.tsv`**: clinical dataframe in tab seperated text format.

Each row is a patient and each column a descriptor.

Details about descriptor are as follows:

	:memo: LEUKID the unique ID of each patient/sample
	:memo: SEX, AGE demographics
	:memo: Mds type
	:memo: WHO 2016 classification
	:memo: Blood counts and Blast counts
	:memo: Cytogenetics
	:memo: NGS derived deletions, gains and regions copy-neutral loss of heterozygosity
	:memo: Annotation of complex karyotype
	:memo: Status of chr.17 at the TP53 locus
	:memo: Treatment status regarding HMA, Lenalidomid, HSCT
	:memo: overall survival and AML transformation information

* :clipboard: **`dd_matrix_binary_cyto.tsv`**: binary matrix of chromosomal alterations per patient from the integration of conventional cytogenetics and NGS-derived copy-number analysis. The file is a tab seperated text file.

Each row is a patient and each column a given chromosomal alteration, eg. del5q, del7 ....
Each entry is binary.

* :bar_chart: **`dd_matrix_binary_cyto.tsv`**: TP53 mutation file.

Each row corresponds to a given mutation in a given patient.

Details about mutation fields  are as follows:

	* TARGET_NAME the unique ID of each patient/sample
	* CHR START END variant.key for the genomic position of the mutation
	* GENE 
	* cDNA_CHANGE
	* PROTEIN_CHANGE 
	* VT variant type (substitution, indels)
	* EFFECT classification of mutation consequence, ie missense nonsense frameshift ...
	* VAF variant allele frequency 

