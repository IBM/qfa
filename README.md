# QFA
QFA, or quantile-frequency analysis, is a nonlinear spectral analysis method for time-series data. It is based on quantile periodograms computed from trigonometric quantile regressio (Li (2012): Quantile Periodograms, Journal of the American Statistical Association, 107:498, 765-776. http://dx.doi.org/10.1080/01621459.2012.682815)

This repo contains an R code (qfa_pfca_code.txt) to compute (a) quantile periodograms, (b) semiparametric estimates of quantile spectra, (c) functional principal component analysis (FPCA) of quantile periodograms, and (d) classification of time series using LDA/QDA/SVD classifiers based on the QFA-FPCA features. 
This repo contains a Python code (QFA-DL-code.zip) for classification of time series using QFA Deep Learning (MLP and CNN).

This repo contains pre-calculated quantile periodograms (bond_disbond_qper_for_cnn.zip) and short-time quantile periodogram (bond_disbond_stqfa_for_cnn_15x45x29.zip) for classification of a set of nondestructive evaluation (NDE) signals available at https://www.math.umd.edu/~bnk/DATA/.
