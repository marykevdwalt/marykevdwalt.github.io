+++
abstract = "The empirical mode decomposition (EMD) algorithm, introduced by N.E. Huang et al in 1998, is arguably the most popular mathematical scheme for non-stationary signal decomposition and analysis. The objective of EMD is to separate a given signal into a number of components, called intrinsic mode functions (IMF's), after which the instantaneous frequency (IF) and amplitude of each IMF are computed through Hilbert spectral analysis (HSA). On the other hand, the synchrosqueezed wavelet transform (SST), introduced by I. Daubechies and S. Maes in 1996 and further developed by I. Daubechies, J. Lu and H.-T. Wu in 2011, is applied to estimate the IF's of all signal components of the given signal, based on one single reference ``IF function'', under the assumption that the signal components satisfy certain strict properties of a so-called adaptive harmonic model (AHM), before the signal components of the model are recovered. The objective of our paper is to develop a hybrid EMD-SST computational scheme by applying a ``modified SST'' to each IMF of the EMD, as an alternative approach to the original EMD-HSA method. While our modified SST assures non-negative instantaneous frequencies of the IMF's, application of the EMD scheme eliminates the dependence on a single reference IF value as well as the guessing work of the number of signal components in the original SST approach. Our modification of the SST consists of applying vanishing moment wavelets (introduced in a recent paper by C.K. Chui, Y.-T. Lin and H.-T. Wu) with stacked knots to process signals on bounded or half-infinite time intervals, and spline curve fitting with optimal smoothing parameter selection through generalized cross-validation. In addition, we formulate a local cubic spline interpolation scheme for real-time realization of the EMD sifting process that improves over the standard global cubic spline interpolation, both in quality and computational cost, particularly when applied to bounded and half-infinite time intervals."
abstract_short = ""
authors = ["C.K. Chui", "M.D. van der Walt"]
date = "April 2015"
image = ""
image_preview = ""
math = true
publication = "In *GEM - International Journal on Geomathematics.*"
publication_short = "In *Int J Geomath*"
selected = false
title = "Signal analysis via instantaneous frequency estimation of signal components"
url_code = ""
url_dataset = ""
url_pdf = ""
url_project = ""
url_slides = ""
url_video = ""

[[url_custom]]
name = "Link"
url = "http://link.springer.com/article/10.1007/s13137-015-0070-z"



+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
