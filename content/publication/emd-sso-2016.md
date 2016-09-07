+++
abstract = "Decomposition of functions in terms of their primary building blocks is one of the most fundamental problems in mathematical analysis and its applications. Indeed, atomic decomposition of functions in the Hardy space $H^p$ for $0<p \\le 1$ as infinite series of ``atoms'' that have the property of vanishing moments with order at least up to $1/p $ has significant impacts, not only to the advances of harmonic and functional analyses, but also to the birth of wavelet analysis, which in turn allows the construction of sufficiently large dictionaries of wavelet-like basis functions for the success of atomic decomposition of  more general functions or signals, by such mathematical tools as ``basis pursuit'' and ``nonlinear basis pursuit''. However, such dictionaries are necessarily huge for atomic decomposition of real-world signals. The spirit of the present paper is to construct the atoms directly from the data, without relying on a large dictionary. Following Gabor, the starting point of this line of thought is to observe that ``any'' signal $a$ can be written as $a(t) = A(t) \\cos\\phi(t)$ via complex extension using the Hilbert transform. Hence, if a given signal $f$ has been decomposed by whatever available methods or schemes, as the sum of sub-signals $f_k$, then each sub-signal can be written as $f_k(t) = A_k(t) \\cos\\phi_k(t)$. Whether or not $f_k$ is an atom of the given signal $f$ depends on whether any of the sub-signals $f_k$ can be further decomposed in a meaningful way. In this regard, the most popular decomposition scheme in the current literature is the sifting process of the empirical mode decomposition (EMD), where the sub-signals $f_k$ are called intrinsic mode functions (IMF’s). The main contribution of our present paper is firstly to demonstrate that IMF’s may not be atoms, and secondly to give a computational scheme for decomposing such IMF’s into finer and meaningful signal building blocks. Our innovation is to apply the signal separation operator (SSO), introduced by the first two authors, with a clever choice of parameters, first to extract the instantaneous frequencies (IF’s) of each IMF obtained from the sifting process, and then (by using the same parameters for the SSO, with the IF’s as input) to construct finer signal building blocks of the IMF. In other words, we replace the Hilbert transform of the EMD scheme by the SSO in this present paper, first for frequency extraction, and then for constructing finer signal building blocks. As an example, we consider the problem in super-resolution of separating two Dirac delta functions that are arbitrarily close to each other. This problem is equivalent to finding the two cosine building blocks of a two-tone signal with frequencies that are arbitrarily close. While the sifting process can only yield one IMF when the frequencies are too close together, the SSO applied to this IMF extracts the two frequencies and recover the two cosine building blocks (or atoms). For this reason, we coin our scheme of sifting+SSO as ``superEMD'', where ``super'' is used as an abbreviation of super-resolution."
abstract_short = ""
authors = ["C.K. Chui", "H.N. Mhaskar", "M.D. van der Walt"]
date = "2016-01-01"
image = ""
image_preview = ""
math = true
publication = "In *GEM - International Journal on Geomathematics.*"
publication_short = "In *Int J Geomath*"
selected = false
title = "Data-driven atomic decomposition via frequency extraction of intrinsic mode functions"
url_code = ""
url_dataset = ""
url_pdf = ""
url_project = ""
url_slides = ""
url_video = ""

[[url_custom]]
name = "Link"
url = "http://link.springer.com/article/10.1007/s13137-015-0079-3"



+++
