Title

Probe-Ratio Blur-Scale Estimation Using Extremal Image Statistics

Abstract

Purpose: Blind deblurring needs the spatial scale of the blur kernel before its shape can be recovered, yet existing scale estimators are spectral heuristics or supervised regressors. We ask whether the scale can be read from one image with a closed-form statistic that needs no labelled blur pairs.

Methods: The effective radius adds in quadrature under convolution of normalized, nonnegative kernels (an exact identity). If we blur the observed image with a known probe and take the ratio of two dark-channel-depth measurements, the image-dependent amplitude cancels, and under an empirical tail-contraction law the ratio has a closed-form inverse. Two constants are fitted once on 25 sharp images.

Results: On 6432 synthetic instances from 134 images, the estimator cuts the error of its uncalibrated form by 67% (MAE 2.64 px) but is not detectably better than a fixed radius, and it is 0.8 to 1.0 px worse than tuned supervised regressors. A constant tuned on labelled radii reaches 2.50 px, and shrinkage toward it with a few labelled images reaches 1.98 px. At matched effective radius the kernel shape changes the probe ratio, so radius alone is not sufficient. With a known kernel family, the true radius improves Richardson–Lucy restoration by 2 dB, but estimated radii, ours included, do not beat the blurry input at fixed settings.

Conclusion: The estimator needs no labelled blur pairs, but it is only moderately accurate, and we say where it fails.

Keywords

Blind deconvolution, Blur kernel estimation, Extreme value theory, Dark channel prior, Image restoration
