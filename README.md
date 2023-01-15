# Supernova-Siblings
A single-galaxy hierarchical model for Type Ia Supernovae that exploded in the same host galaxy: 'SN Siblings'

In this repo I summarise work adapting a hierarchical Bayesian model, *BayeSN*, to fit light curves of supernova siblings simultaneously. I present here my Stan code, and key conclusions, which are:  

1. Parameter estimates of siblings parameters improve by fitting all the siblings simultaneously, as compared to constraints from fitting each siblings individually.

2. The parameter estimates in the joint fit are affected by the intrinsic scatter assumptions, with distance posteriors widening with a lower level of correlation, and vice versa for all remaining parameters; therefore, $\sigma_{\rm{Rel}}$, the relative intrinsic scatter must be marginalised over in any siblings analysis to robusly estimate parameters of interest.

3. We demonstrate how to estimate cosmological parameters, e.g. the Hubble constant, using Type Ia supernova siblings.

See jupyter notebook for summary and plots.
