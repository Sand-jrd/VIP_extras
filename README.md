# VIP extras

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=binder%2Fwelcome.ipynb)


> additional material for [VIP](https://github.com/vortex-exoplanet/VIP)


## [Tutorials](./tutorials)

Tutorials in form of Jupyter notebooks can be found in the `tutorials/` folder. They can be visualized directly here on GitHub (by just clicking on them), or using the nbviewer service.

### 01. Main Tutorial (part I)

> [GitHub](./tutorials/01_adi_pre-postproc.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/01_adi_pre-postproc.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F01_adi_pre-postproc.ipynb)

This tutorial covers:

- loading datasets
- pre-processing, including image rotation
- S/N ratio, maps, significance, STIM maps
- post-processing with ADI algorithms (Median subtraction, PCA, LLSG, ...)

### 02. Main Tutorial (part II)

> [GitHub](./tutorials/02_adi_negfc_cc.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/02_adi_negfc_cc.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F02_adi_negfc_cc.ipynb)

This tutorial covers:

- fake planet injection
- flux and position estimation for companion candidates (NEGFC)
- throughput, contrast curves

### 03. Using HCIDataset objects

> [GitHub](./tutorials/03_hcidataset.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/vortex-exoplanet/VIP_extras/blob/master/tutorials/03_hcidataset.ipynb) / [binder](https://mybinder.org/v2/gh/vortex-exoplanet/VIP_extras/master?filepath=tutorials%2F03_hcidataset.ipynb)

This tutorial shows how VIP's `HCIDataset` can be used for simple object-oriented access to all dataset related operations. It covers:

- loading/saving datasets
- simple operations (plotting, pre-processing, injecting)




## [Datasets](./datasets)

The datasets in the `datasets/` folder are available in FITS format, and VIP's own HCIDataset format (as `.npz`).

### NACO betapic

Small ADI cube with 39 frames. `naco_betapic.npz` contains just the "raw" data (`cube`, `psf`, `angles`, `px_scale`), while `naco_betapic_preproc.npz` is slightly preprocessed (cropped, psf normalized).
