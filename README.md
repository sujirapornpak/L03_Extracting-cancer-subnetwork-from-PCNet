## Methods for extracting a cancer subnetwork from the PCNet

In this notebook, methods for extracting a cancer subnetwork from the [__PCNet__](http://www.ndexbio.org/#/network/f93f402c-86d4-11e7-a10d-0ac135e8bacf) [1] is derived from the original Jupyter notebook used in [__cancer subnetwork construction__](https://github.com/idekerlab/pyNBS/blob/master/Supplementary_Notebooks/Cancer%20Subnetwork%20Construction.ipynb), a pre-processing step of propagating network used for the [__pyNBS algorithm__](https://github.com/idekerlab/pyNBS) [2].  

__The following is a list of the four cancer-related gene sets used to filter PCNet (~ a baseline cancer gene set):__  

|File Name|Cancer Gene Set Description|Citation|
|:---|:---|:---|
|hallmarks.txt|Genes from hallmark cancer pathways|Hanahan D and Weinberg RA (2011) Hallmarks of Cancer: The Next Generation. Cell. 144(5), 646-674.|
|vogelstein.txt|List of tumor suppressor and oncogenes from Vogelstein et al.|Vogelstein B, et al. (2013) Cancer genome landscapes. Science. 339(6127), 1546-1558.|
|sanger_CL_genes.txt|Recurrently mutated cancer genes discovered from cancer cell lines (Sanger UK)|Iorio F, et al. (2016) A Landscape of Pharmacogenomic Interactions in Cancer. Cell. 166(3), 740-754.|
|cgc.txt|Genes from the Cancer Gene Census (COSMIC v81)|Forbes SA, et al. (2017) COSMIC: somatic cancer genetics at high-resolution. Nucleic Acids Res. 45(D1), D777-D783.|


- [1] Huang, J.K., et al., Systematic evaluation of molecular networks for discovery of disease genes. Cell systems, 2018. 6(4): p. 484-495. e5.
- [2] Huang, J.K., et al., pyNBS: a Python implementation for network-based stratification of tumor mutations. Bioinformatics, 2018. 34(16): p. 2859-2861.

