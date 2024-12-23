# Single cell profiling of Environmental Enteropathy

In an effort to demonstrate one of the core tenets of scientific inquiry: reproducibility, this project aims to reproduce the UMAP plot in Figure 1C of [this](https://pubmed.ncbi.nlm.nih.gov/36044598/) paper.

The data is open source, making the workflow detailed in our code easily reproducible. You can find .csvs of the raw counts and metadata hosted by the Broad Institute, [here](https://singlecell.broadinstitute.org/single_cell/study/SCP1307/single-cell-profiling-of-environmental-enteropathy-reveals-signatures-of-epithelial-remodeling-and-immune-activation-in-severe-disease#study-download).

Note: Since the individual files exceed the 2GB allotted by `git lfs` they won't be included in this repo.

We'll be working with ~25k cells, derived from scRNA-seq done on 33 small intestinal biopsies split between healthy and Environmental enteropathy-presenting individuals.