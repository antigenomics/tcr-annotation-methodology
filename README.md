## **T-cell repertoire annotation and motif discovery** tutorial

### Prerequisites

The following software is required to run the tutorial:

* **Java v1.10** Can be downloaded from [Java SE Runtime Environment 10 Downloads](https://www.oracle.com/technetwork/java/javase/downloads/jre10-downloads-4417026.html) or installed by other means.

* **RStudio** Can be installed from [rstudio.com](https://www.rstudio.com).

* **R packeges** Run the following command in RStudio:

```R
install.packages(c(
	"dplyr", "data.table", "ggplot2",
	"forcats", "parallel", "stringr",
	"reshape2", "igraph", "msa",
	"stringdist", "broom", "GGally",
	"ggseqlogo", "network", "gridExtra",
	"cowplot"
	)
)
```

or install these packages manually.

Download the tutorial by clicking the ``Clone or download`` button or execute

```bash
git clone https://github.com/antigenomics/sciar-tutorial-2018.git
```

### Materials

The slides can be found in ``slides/slides.pdf``. For the interactive part open the ``tutorial.Rmd`` file in RStudio.