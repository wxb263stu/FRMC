# FRMC 

Python code for Wu and Wang et al. FRMC: A fast and robust method for the imputation of scRNA-seq data

* FRMC.py  
Last update: v1.0.0

This is a fast and robust imputation software based on matrix completion, 
called FRMC, for single cell RNA-Seq data.

* FRMC_LowMemoryVersion.py
Version LowMemoryVersion 2.0.0

This LowMemoryVersion is an upgrade to the previous version v1.0.0, which significantly 
reduces the memory requirements and can be used to handle large-scale single-cell datasets 
with 100k or even more cells.


## Requirements
* Python 3
* numpy
* scipy
* matplotlib
* sklearn
* pandas
* math


## Usage
```
python FRMC.py  <Normalized Matrix csv file(cell-by-gene) >  <out_prefix> 

python FRMC_LowMemoryVersion.py  <Normalized Matrix csv file(cell-by-gene) >   <out_prefix> 

```

