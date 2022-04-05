# QFA
QFA, or quantile-frequency analysis, is a nonlinear spectral analysis method for time-series data. It is based on quantile periodograms computed from trigonometric quantile regression [1][2].

This repo contains an R code (qfa_pfca_code.txt) for computing (a) quantile periodograms, (b) semiparametric estimates of quantile spectra [3][4], (c) functional principal component analysis (FPCA) of quantile periodograms, and (d) classification of time series using LDA, QDA, and SVM based on QFA-FPCA features [3]

This repo contains Python codes (QFA-DL-code.zip) for classification of time series using QFA Deep Learning (MLP and CNN) [5].

This repo contains pre-calculated quantile periodograms (bond_disbond_qper_for_cnn.zip) and short-time quantile periodogram (bond_disbond_stqfa_for_cnn_15x45x29.zip) for classification of a set of nondestructive evaluation (NDE) signals available at https://www.math.umd.edu/~bnk/DATA/. It also contains traditional periodograms (bond_disbond_per_for_cnn.zip) and spectrograms (bond_disbond_stft_for_cnn_15x29.zip) of the NDE signals. These data were used in recent experiments [5].

References

[1] T.-H. Li (2012), "Quantile periodograms", Journal of the American Statistical Association, 107:498, 765-776. http://dx.doi.org/10.1080/01621459.2012.682815

[2] T.-H. Li (2014), Time Series with Mixed Spectra, CRC Press. https://doi.org/10.1201/b15154

[3] T.-H. Li (2020), "From zero crossings to quantile-frequency analysis of time series with an application to nondestructive evaluation", Applied Stochastic Models for Business and Industry, 36:6, 1111-1130. https://doi.org/10.1002/asmb.2499

[4] T. Chen, Y. Sun, and T.-H. Li (2021), "A semi-parametric estimation method for the quantile spectrum with an application to earthquake classification using convolutional neural network", Computational Statistics and Data Analysis, 153, 107069. https://doi.org/10.1016/j.csda.2020.107069

[5] T.-H. Li (2022), "Quantile-frequency analysis and deep learning for signal classification," preprint. 


For further inqueries, please contact Ta-Hsin Li (thl@us.ibm.com)
