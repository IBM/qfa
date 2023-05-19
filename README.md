# QFA
QFA, or quantile-frequency analysis, is a nonlinear spectral analysis method for time-series data [1][2]. Based on quantile periodograms computed from trigonometric quantile regression, QFA, together with its extension called short-time QFA (STQFA), is able to provide a richer view of time-series data than traditional power spectra and spectrograms. 

This repo contains an installable R package qfa_x.x.tar.gz and the associated manual qfa_x.x.pdf.

This repo contains an R code (qfa_fpca_code.txt) for functional principal component analysis (FPCA) of quantile periodograms, and classification of time series using LDA, QDA, and SVM based on QFA-FPCA features [3]

This repo contains a Python code (QFA-DL-code.zip) for classification of time series using QFA and STQFA combined with Deep Learning (MLP and CNN) [5].

This repo contains pre-calculated quantile periodograms (bond_disbond_qper_for_cnn.zip) and short-time quantile periodogram (bond_disbond_stqfa_for_cnn_15x45x29.zip) for classification of a set of nondestructive evaluation (NDE) signals available at https://www.math.umd.edu/~bnk/DATA/. It also contains traditional periodograms (bond_disbond_per_for_cnn.zip) and spectrograms (bond_disbond_stft_for_cnn_15x29.zip) of the NDE signals. These data were used in recent experiments [5].

References

[1] T.-H. Li (2012), "Quantile periodograms", Journal of the American Statistical Association, 107:498, 765-776. http://dx.doi.org/10.1080/01621459.2012.682815

[2] T.-H. Li (2014), Time Series with Mixed Spectra, CRC Press. https://doi.org/10.1201/b15154

[3] T.-H. Li (2020), "From zero crossings to quantile-frequency analysis of time series with an application to nondestructive evaluation", Applied Stochastic Models for Business and Industry, 36:6, 1111-1130. https://doi.org/10.1002/asmb.2499

[4] T. Chen, Y. Sun, and T.-H. Li (2021), "A semi-parametric estimation method for the quantile spectrum with an application to earthquake classification using convolutional neural network", Computational Statistics and Data Analysis, 153, 107069. https://doi.org/10.1016/j.csda.2020.107069

[5] T.-H. Li (2023), "Quantile-frequency analysis and deep learning for signal classification," Journal of Nondestructvie Evaluation, 42, 40. https://doi.org/10.1007/s10921-023-00952-y


For further inqueries, please contact Ta-Hsin Li (thl@us.ibm.com)
