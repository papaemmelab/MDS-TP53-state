# Code accompanying *Implications of TP53 Allelic State for Genome Stability, Clinical Presentation and Outcomes in Myelodysplastic Syndromes*

Bernard E, Nannya Y, Hasserjian P.H, et al.


## Repository Structure

- **`data/`**: the folder contains the clinical and molecular dataframes necessary to reproduce all results of the paper.

- **`MDS-TP53-state.ipynb`**: [a relative link](other_file.md) the jupyter notebook with R code to reproduce results and figures.

- [MDS-TP53-state.ipynb](./MDS-TP53-state.ipynb) the jupyter notebook with R code to reproduce results and figures.

- **`MDS-TP53-state.html`**: an html version of the notebook that you can open in any web browser to have a look at results and figures.


## Working with this repository

### Clone the repository

To clone this repository on your local computer please run:
```shell
$ git clone https://github.com/papaemmelab/MDS-TP53-state
```

R packages you need to install:

```R
# run in an R console
install.packages('ggplot2',      repos = 'http://cran.us.r-project.org')
install.packages('gridExtra',    repos = 'http://cran.us.r-project.org')
install.packages('survival',     repos = 'http://cran.us.r-project.org')
install.packages('survminer',    repos = 'http://cran.us.r-project.org')
install.packages('cmprsk',       repos = 'http://cran.us.r-project.org')
install.packages('stringr',      repos = 'http://cran.us.r-project.org')
```
