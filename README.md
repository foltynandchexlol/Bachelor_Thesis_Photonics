# Thesis Title: Simulating Multiphoton State Engineering with Photon Number Resolving Detectors

## Abstract

Photon number manipulation of TMSV states is being simulated using QuTiP on the basis
of implementing the experimental set-up featured in the research projects OSM and
TJB. _Subtraction_ from both signal and idler mode (main modes) is achieved through
conditional measurement with photon number resolving detectors (PNDs) on each coupled
ancilla mode. The set-up is extended by the injection of _added_ photons through the
ancilla modes. Given the output state of this four-mode system the Agarwal parameter
$I(z)$, logarithmic negativity $E_{N}(z, T)$ and its _difference_ $\Delta E_{N}(z, T)$, the joint photon
number distributions (JPDs) for both ideal $P(m, n)$ and lossy detection $P'(m, n, \eta, \nu)$,
as well as the resulting determinants of the matrix of moments (DMMs) $det(M)(z)$ and
$det(M')(z, \eta, \nu)$ are being computed in partial dependence of squeezing parameter $z$ and
beam splitter transmissivity $T$ (otherwise assumed $T = 0.9$) for various combinations of
up to three photons subtracted, added or replaced. Efficiency $\eta = 0.3$ and dark count
$\nu = 0.4$ are approximated as parameters for lossy detection by reproducing the lossy JPDs
in OSM.<br>
Overall the non-classicality of the output states and their change in correlation with symmetrical
number of photons subtracted could be confirmed as predicated in OSM, although
with significant differences in magnitude for $det(M)(z)$. Increases in the degree of entanglement
for all single photon operations in certain regimes of $(z, T)$ with respect to the
initial TMSVS could be roughly reproduced as predicated in TJB, although with noticeable
deviations in values. Expanding on OSM, $I(z)$, $P(m, n)$, $P'(m, n, \eta, \nu)$, $det(M)(z)$
and $det(M')(z, \eta, \nu)$ are also being computed for symmetrical photon addition and replacement,
with remarkable alterations being observed especially for replacement. Expanding
on TJB, $\Delta E_{N}(z, T)$ and $E_{N}(z, T = 0.9)$ are being computed for higher numbers of photon
operations, indicating an increase in entanglement with the number of photons manipulated
and an expansion of $(z, T)$-regimes for which entanglement increases.<br>
The foundation of this simulation lends itself to examine further combinations of operations
with larger numbers of photons manipulated and for computing other measures of
interest, generally yielding more accurate and valid results with a higher number $N$ of
Hilbert space dimensions. However, processing requirements expand very rapidly with $N$.

---

## List of Abbreviations

__BS__ beam splitter

__DMM__ determinant of the matrix of moments

__JPD__ joint photon number distribution

__OSM__ Omar S. Magana-Loaiza et al.: Multiphoton Quantum-State Engineering using Conditional Measurements; https://arxiv.org/abs/1901.00122

__PBS__ polarising beam splitter

__PND__ photon number resolving detector

__ppKTP WG__ potassium titanyl phosphate waveguide

__QuTiP__ Quantum Toolbox in Python

__SMF__ single mode fibre

__SPDC__ spontaneous parametric down-conversion

__TES__ transition edge sensor

__TJB__ Tim J. Bartley and Ian A. Walmsley: Directly comparing entanglement-enhancing non-Gaussian operations; https://iopscience.iop.org/article/10.1088/1367-2630/17/2/023038

__TMSV__ two-mode squeezed vacuum

__TMSVS__ two-mode squeezed vacuum state
