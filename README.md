# Code accompanying *Implications of TP53 Allelic State for Genome Stability, Clinical Presentation and Outcomes in Myelodysplastic Syndromes*

[Bernard E, Nannya Y, Hasserjian RP, et al., Nature Medicine, 26, 1549-1556, 2020.](https://www.nature.com/articles/s41591-020-1008-z)


![](./lolli.png)

## :open_file_folder: Repository Structure

- **`data/`**: the folder contains the clinical and molecular data necessary to reproduce the results of the study. See the [README](./data/README.md) in the **`data/`** folder for details about data structure.

- [MDS-TP53-state.ipynb](./MDS-TP53-state.ipynb): the jupyter notebook with R code to reproduce results and figures.

- [MDS-TP53-state.html](./MDS-TP53-state.html): an html version of the notebook.


## :rocket: Getting started with this repository

### Clone the repository

To clone this repository on your local computer please run:

```shell
$ git clone https://github.com/papaemmelab/MDS-TP53-state
```

### R packages you need to install:

```R
# run in an R console
install.packages('ggplot2',      repos = 'http://cran.us.r-project.org')
install.packages('reshape2',      repos = 'http://cran.us.r-project.org')
install.packages('survival',     repos = 'http://cran.us.r-project.org')
install.packages('survminer',    repos = 'http://cran.us.r-project.org')
install.packages('cmprsk',       repos = 'http://cran.us.r-project.org')
install.packages('stringr',      repos = 'http://cran.us.r-project.org')
```


## :question: Question

If any question on the repo, feel free to contact [Elsa](https://elsab.github.io/).
