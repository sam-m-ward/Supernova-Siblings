# Supernova-Siblings
A single-galaxy hierarchical Bayesian model for Type Ia Supernovae that exploded in the same host galaxy: 'SN Siblings'. 

This repo summarises work done to adapt a hierarchical Bayesian model, *BayeSN*, to fit light curves of supernova siblings simultaneously. I present the new Stan code, and key conclusions, which are:  

1. Estimates of siblings parameters improve by fitting all the siblings' data simultaneously, as compared to constraints from fitting each sibling individually.

2. The parameter estimates in the joint fit are affected by the intrinsic scatter assumptions, with distance posteriors widening with a lower level of correlation, and vice versa for all remaining parameters; therefore, the relative intrinsic scatter, $\sigma_{\rm{Rel}}$, must be marginalised over in any siblings analysis to robustly estimate parameters of interest.

3. We demonstrate how to estimate cosmological parameters, e.g. the Hubble constant, using these hierarchical methods for Type Ia supernova siblings.

See jupyter notebook, [**SingleGalaxySiblingsAnalysis.ipynb**](https://github.com/sam-m-ward/Supernova-Siblings/blob/main/SingleGalaxySiblingsAnalysis.ipynb) for summary and plots.

Full work published in *The Astrophysical Journal* ([**Ward et al. 2023**](https://iopscience.iop.org/article/10.3847/1538-4357/acf7bb)).
