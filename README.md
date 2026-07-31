Title:

Extremal Statistics of Natural Images Reveal Blur Kernel Scale: A Self-Calibrating, Training-Free Theory for Blind Deconvolution

Abstract:

Blind deblurring pipelines — from dark-channel priors to learned kernel-size regressors — all require an estimate of blur-kernel scale before kernel shape can be recovered, yet no method derives this scale from a formal statistical theory. We show a natural image's dark-channel depth — the gap between mean intensity and the mean of local-window minima — contracts under blur following a closed-form power law derived from Fisher–Tippett–Gnedenko extreme value theory. Because a blur kernel's effective radius (root second moment) is exactly additive in quadrature under convolution for any kernel shape — proved here and verified numerically — we eliminate the theory's one content-dependent parameter by probing an image with a second, known blur and reading radius off the ratio of two dark-channel-depth measurements. The resulting closed-form, training-free (calibration-only) estimator needs no labelled corpus, only two universal constants fitted once on five held-out images. Across four real benchmarks (Set14, BSD100, Urban100, CBSD68; 6432 upstream and 216 downstream instances), self-calibration cuts error by 63.9% versus a naive population-calibrated variant (p<10⁻³⁰⁰), and the estimator matches or beats every training-free baseline on accuracy and rank correlation (0.603, best overall), trailing only a supervised regressor. In downstream Richardson–Lucy deconvolution, our estimate yields significantly higher PSNR/SSIM than classical heuristics and the supervised regressor in most comparisons (p<10⁻³), even where its own radius error is not smallest — showing estimator value depends on error structure, not only magnitude. We report this honestly, including conditions where naive baselines win, and discuss the resulting implications.

Keywords:

blind deconvolution, blur kernel estimation, extreme value theory, dark channel prior, image restoration, training-free estimation

Google Drive link (For code and results): https://drive.google.com/file/d/1nchZoK4nf6siOJO2_G6CI6jAGYd6gex2/view?usp=sharing
