Title

Effective Radius Is Insufficient for Blur Scale Estimation from Dark Channel Statistics under Probe Blurring

Abstract

Purpose: Blind deblurring needs the spatial scale of the blur kernel, and the effective radius (the root second moment) is the one scale measure that composes exactly under convolution. We ask whether the effective radius is enough to determine what a dark-channel statistic reports about blur.

Methods: Because effective radii add in quadrature, blurring an image with a known probe and taking the ratio of two dark-channel-depth measurements cancels the image-dependent amplitude of an empirical tail-contraction law, and the ratio has a closed-form inverse. We use this construction as a measuring instrument. Two constants are fitted once on 25 sharp images, and we test the ratio with ten kernel shapes at matched effective radius.

Results: The radius alone is not sufficient: at the same effective radius the probe ratio changes with kernel shape, and a covariance-based surrogate does not explain the change. The calibrated estimator built on the ratio cuts the error of its uncalibrated form by 67% (MAE 2.64 px) on 6432 synthetic instances from 134 images, but it is not detectably better than a fixed radius and is 0.8 to 1.0 px worse than tuned supervised regressors. A constant tuned on labelled radii reaches 2.50 px. With a known kernel family, the true radius improves Richardson–Lucy restoration by 2 dB, but estimated radii do not beat the blurry input at fixed settings.

Conclusion: We offer the identity, the conditioning analysis and the sufficiency test as the findings, and the estimator as a baseline with stated limits.

Keywords

Blur scale estimation, Effective radius, Blind deconvolution, Dark channel prior, Extreme value theory
