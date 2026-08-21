---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
--- 

{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

<p class="text-block">
UNDER CONSTRUCTION
</p>

<!--

## Software Packages ##

* **MORLAB (Model Order Reduction LABoratory)**<br/>
  <a target ="_blank"
  href="https://en.wikipedia.org/wiki/Open-source_software">
  <img src="../images/open_source_symbol.png" alt="Open Source Software"
  class="opensource"></a>
  <a href="https://opensource.org/licenses/BSD-2-Clause">
  <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
  alt="License: BSD 2-Clause" class="badge"></a>
  &nbsp;*Latest Version: 6.0*<br/>
  This toolbox is a collection of MATLAB and Octave routines for model order
  reduction of dynamical systems. The implementation is based on spectral
  projection methods, like the matrix sign function and the matrix disk
  function, and on iterative low-rank solvers for large-scale sparse systems.
  For details and references see the official <a target="_blank" 
  href="https://www.mpi-magdeburg.mpg.de/projects/morlab">project website</a>, 
  the <a target="_blank" 
  href="https://morwiki.mpi-magdeburg.mpg.de/morwiki/index.php/MORLAB">MORwiki 
  entry</a> and the latest <a target="_blank" 
  href="https://doi.org/10.5281/zenodo.7072831">Zenodo upload</a>.<br/>
  <a target="blank_" href="https://doi.org/10.5281/zenodo.7072831">
  <button class="btn btn--inverse">Download</button></a>
  <a target="blank_" href="https://doi.org/10.1007/978-3-030-72983-7_19">
  <button class="btn btn--inverse">Documentation</button></a>
  <button id="citationMORLAB-pop" class="btn btn--inverse">Citation</button>

* **SOMDDPA (Second-Order Modally-Damped Dominant Pole Algorithm)**<br/>
  <a target ="_blank"
  href="https://en.wikipedia.org/wiki/Open-source_software">
  <img src="../images/open_source_symbol.png" alt="Open Source Software"
  class="opensource"></a>
  <a href="https://opensource.org/licenses/BSD-2-Clause">
  <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
  alt="License: BSD 2-Clause" class="badge"></a>
  &nbsp;*Latest Version: 2.0*<br/>
  For model order reduction via modal truncation, dominant poles have been 
  proven to be an efficient and accurate approach.
  In case of modally-damped second-order systems, it is possible to extend the 
  idea of dominant poles in a structure-preserving fashion to the mechanical 
  system case.
  This package contains a structure-preserving implementation in MATLAB and 
  Octave of the dominant pole algorithm for modally-damped second-order systems.
  Find the latest upload on <a target="_blank" 
  href="https://doi.org/10.5281/zenodo.2553901">Zenodo</a> and checkout my
  <a target="_blank" href="https://doi.org/10.25673/38617">dissertation</a>
  for the theoretical background.<br/>
  <a target="blank_" href="https://doi.org/10.5281/zenodo.2553901">
  <button class="btn btn--inverse">Download</button></a>
  <a target="blank_" href="https://doi.org/10.25673/38617">
  <button class="btn btn--inverse">Documentation</button></a>
  <button id="citationSOMDDPA-pop" class="btn btn--inverse">Citation</button>

* **SOLBT (Limited Balanced Truncation for Large-Scale Sparse Second-Order 
  Systems)**<br/>
  <a target ="_blank"
  href="https://en.wikipedia.org/wiki/Open-source_software">
  <img src="../images/open_source_symbol.png" alt="Open Source Software"
  class="opensource"></a>
  <a href="https://opensource.org/licenses/BSD-2-Clause">
  <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
  alt="License: BSD 2-Clause" class="badge"></a>
  &nbsp;*Latest Version: 3.0*<br/>
  In practical applications, only local approximations of system's behavior in 
  frequency or time domain are needed.
  This package extends the idea of frequency- and time-limited balanced 
  truncation to large-scale sparse mechanical systems of second-order type with 
  an implementation in MATLAB and Octave.
  Find the latest upload on <a target="_blank" 
  href="https://doi.org/10.5281/zenodo.2553925">Zenodo</a>.
  Check out the corresponding <a target="_blank" 
  href="https://doi.org/10.1016/j.laa.2020.06.024">paper</a> for the
  theoretical background.<br/>
  <a target="blank_" href="https://doi.org/10.5281/zenodo.2553925">
  <button class="btn btn--inverse">Download</button></a>
  <a target="blank_" href="https://doi.org/10.1016/j.laa.2020.06.024">
  <button class="btn btn--inverse">Documentation</button></a>
  <button id="citationSOLBT-pop" class="btn btn--inverse">Citation</button>

---

## Contributions to other Projects ##

* **M-M.E.S.S. (Matrix Equation Sparse Solvers Library)**:
  <a target ="_blank"
  href="https://en.wikipedia.org/wiki/Open-source_software">
  <img src="../images/open_source_symbol.png" alt="Open Source Software"
  class="opensource"></a>
  <a href="https://opensource.org/licenses/BSD-2-Clause">
  <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
  alt="License: BSD 2-Clause" class="badge"></a><br/>
  From version 1.0.1 up to version 3.1, I made continuously updates in the 
  MATLAB version of the <a target="_blank" 
  href="https://www.mpi-magdeburg.mpg.de/projects/mess">M.E.S.S. library</a>
  involving among other an implementation of the Riccati iteration, the RADI
  method and several bug fixes.
  For more details on my contributions see the <a target="_blank"
  href="https://gitlab.mpi-magdeburg.mpg.de/mess/mmess-releases/-/blob/master/CONTRIBUTORS.md">contributors file</a>
  and checkout the latest version on
  <a target="_blank" href="https://doi.org/10.5281/zenodo.14929081">Zenodo</a>.

---

## <a name="codepackages"></a>Supplementary code packages and data ##

1.  S. Reiter and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.20384015">Code, data and results for
    numerical experiments in &ldquo;Symmetric Hermite quadrature-based balanced 
    truncation for learning linear dynamical systems from derivative data&rdquo;
    (version 1.0)</a>,
    May 2026. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.20384015">10.5281/zenodo.20384015</a><br />
    <button id="supReiW26-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2606.00298"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  M. S. Ackermann and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.19895043">Code, data and results for
    numerical experiments in &ldquo;Second-order AAA algorithms for structured
    data-driven modeling&rdquo; (version 1.1)</a>,
    May 2026. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.19895043">10.5281/zenodo.19895043</a><br />
    <button id="supAckW26-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2506.02241"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  R. Smith and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.19582087">Code, data and results for
    numerical experiments in &ldquo;A tangential ADI method for the efficient
    solution of large-scale indefinite Lyapunov equations&rdquo;
    (version 1.1)</a>,
    April 2026. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.19582087">10.5281/zenodo.19582087</a><br />
    <button id="supSmiW26-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2512.04983"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  S. Reiter and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.18148591">Code, data and results for
    numerical experiments in &ldquo;Data-driven balanced truncation for
    second-order systems with generalized proportional damping&rdquo;
    (version 1.1)</a>,
    January 2026. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.18148591">10.5281/zenodo.18148591</a><br />
    <button id="supReiW26-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1137/25M1768217"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  M. S. Ackermann, L. Balicki, and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.18317028">Code, data and results for
    numerical experiments in &ldquo;A refined nonlinear least-squares method for
    the rational approximation problem&rdquo;
    (version 1.0)</a>,
    January 2026. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.18317028">10.5281/zenodo.18317028</a><br />
    <button id="supAckBW26-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2601.19813"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  R. Smith and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.17632592">Code, data and results for
    numerical experiments in &ldquo;A tangential ADI method for the efficient
    solution of large-scale indefinite Lyapunov equations&rdquo;
    (version 1.0)</a>,
    December 2025. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.17632592">10.5281/zenodo.17632592</a><br />
    <button id="supSmiW25-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2512.04983"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  S. Reiter and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.15642589">Code, data and results for
    numerical experiments in &ldquo;Data-driven balanced truncation for
    second-order systems with generalized proportional damping&rdquo;
    (version 1.0)</a>,
    June 2025. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.15642589">10.5281/zenodo.15642589</a><br />
    <button id="supReiW25-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1137/25M1768217"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  M. S. Ackermann and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.15389438">Code, data and results for
    numerical experiments in &ldquo;Second-order AAA algorithms for structured
    data-driven modeling&rdquo; (version 1.0)</a>,
    June 2025. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.15389438">10.5281/zenodo.15389438</a><br />
    <button id="supAckW25-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2506.02241"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.8183173">Code, data and results for
    numerical experiments in &ldquo;An adaptive data sampling strategy for
    stabilizing dynamical systems via controller inference&rdquo;
    (version 1.0)</a>,
    June 2025. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.8183173">10.5281/zenodo.8183173</a><br />
    <button id="supWer25-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1137/25M176550X"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  S. Reiter and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.11557038">Code and results for
    numerical experiments in &ldquo;Interpolatory model order reduction of
    large-scale dynamical systems with root mean squared error measures&rdquo;
    (version 1.1)</a>,
    June 2024. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.11557038">10.5281/zenodo.11557038</a><br />
    <button id="supReiW24a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1016/j.ifacol.2025.03.066"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  J. Saak and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.11390499">Code, data and results for
    numerical experiments in &ldquo;Using \\(LDL^{T}\\) factorizations in
    Newton's method for solving general large-scale algebraic Riccati
    equations&rdquo;
    (version 1.1)</a>,
    June 2024. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.11390499">10.5281/zenodo.11390499</a><br />
    <button id="supSaaW24a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1553/etna_vol62s95"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.10946483">Code, data and results for
    numerical experiments in &ldquo;Structure-preserving interpolation of
    quadratic-bilinear systems via regular multivariate transfer functions&rdquo;
    (version 1.0)</a>,
    May 2024. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.10946483">10.5281/zenodo.10946483</a><br />
    <button id="supWer24a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1002/pamm.202400048"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.7897240">Code, data and results for
    numerical experiments in &ldquo;System stabilization with policy
    optimization on unstable latent manifolds&rdquo;
    (version 1.0)</a>,
    April 2024. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.7897240">10.5281/zenodo.7897240</a><br />
    <button id="supWer24-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1016/j.cma.2024.117483"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  Q. Aumann and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.10945494">Code, data and results for
    numerical experiments in &ldquo;Adaptive choice of near-optimal expansion
    points for interpolation-based structure-preserving model reduction&rdquo;
    (version 1.2)</a>,
    April 2024. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.10945494">10.5281/zenodo.10945494</a><br />
    <button id="supAumW24-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s10444-024-10166-z"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  J. Heiland, Y. Kim, and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.10783695">Code, data and results for
    numerical experiments in &ldquo;Deep polytopic autoencoders for
    low-dimensional linear parameter-varying approximations and nonlinear
    feedback design&rdquo; (version 1.0)</a>,
    March 2024. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.10783695">10.5281/zenodo.10783695</a><br />
    <button id="supHeiKW24-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s10444-025-10269-1"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-green.svg"
    alt="License: MIT" class="badge"></a>

1.  S. Reiter and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.10729524">Code and results for
    numerical experiments in &ldquo;Interpolatory model order reduction of
    large-scale dynamical systems with root mean squared error measures&rdquo;
    (version 1.0)</a>,
    March 2024. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.10729524">10.5281/zenodo.10729524</a><br />
    <button id="supReiW24-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2403.08894"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  J. Saak and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.10619037">Code, data and results for
    numerical experiments in &ldquo;Using \\(LDL^{T}\\) factorizations in
    Newton's method for solving general large-scale algebraic Riccati
    equations&rdquo;
    (version 1.0)</a>,
    February 2024. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.10619037">10.5281/zenodo.10619037</a><br />
    <button id="supSaaW24-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1553/etna_vol62s95"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  Q. Aumann and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.10435758">Code, data and results for
    numerical experiments in &ldquo;Adaptive choice of near-optimal expansion
    points for interpolation-based structure-preserving model reduction&rdquo;
    (version 1.1)</a>,
    December 2023. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.10435758">10.5281/zenodo.10435758</a><br />
    <button id="supAumW23a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s10444-024-10166-z"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.10116600">Code, data and results for
    numerical experiments in &ldquo;Structured interpolation for multivariate
    transfer functions of quadratic-bilinear systems&rdquo;
    (version 2.0)</a>,
    November 2023. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.10116600">10.5281/zenodo.10116600</a><br />
    <button id="supWer23c-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s10444-024-10109-8"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  J. Heiland and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.7977616">Code, data and results for
    numerical experiments in &ldquo;Low-complexity linear
    parameter-varying approximations of incompressible Navier-Stokes equations
    for truncated state-dependent Riccati feedback&rdquo; (version 2.0)</a>,
    May 2023. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.7977616">10.5281/zenodo.7977616</a><br />
    <button id="supHeiW23-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1109/LCSYS.2023.3291231"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-green.svg"
    alt="License: MIT" class="badge"></a>

1.  Q. Aumann and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.7845175">Code, data and results for
    numerical experiments in &ldquo;Adaptive choice of near-optimal expansion
    points for interpolation-based structure-preserving model reduction&rdquo;
    (version 1.0)</a>,
    April 2023. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.7845175">10.5281/zenodo.7845175</a><br />
    <button id="supAumW23-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s10444-024-10166-z"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.7397069">Code, data and results for
    numerical experiments in &ldquo;Structured interpolation for multivariate
    transfer functions of quadratic-bilinear systems&rdquo;
    (version 1.0)</a>,
    April 2023. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.7397069">10.5281/zenodo.7397069</a><br />
    <button id="supWer23b-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s10444-024-10109-8"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.7358813">Code, data and results for
    numerical experiments in &ldquo;Structured barycentric forms for
    interpolation-based data-driven reduced modeling of second-order
    systems&rdquo;
    (version 1.0)</a>,
    March 2023. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.7358813">10.5281/zenodo.7358813</a><br />
    <button id="supWer23a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s10444-024-10118-7"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  J. Heiland and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.7742469">Code, data and results for
    numerical experiments in &ldquo;Low-complexity linear
    parameter-varying approximations of incompressible Navier-Stokes equations
    for truncated state-dependent Riccati feedback&rdquo; (version 1.0)</a>,
    March 2023. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.7742469">10.5281/zenodo.7742469</a><br />
    <button id="supHeiW23-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1109/LCSYS.2023.3291231"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-green.svg"
    alt="License: MIT" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.7530566">Code, data and results for
    numerical experiments in &ldquo;Context-aware controller inference for
    stabilizing dynamical systems from scarce data&rdquo;
    (version 1.1)</a>,
    January 2023. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.7530566">10.5281/zenodo.7530566</a><br />
    <button id="supWer23-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1098/rspa.2022.0506"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  Q. Aumann and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.6806016">Code, data and results for
    numerical experiments in &ldquo;Structured model order reduction for
    vibro-acoustic problems using interpolation and balancing methods&rdquo;
    (version 1.1)</a>,
    August 2022. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.6806016">10.5281/zenodo.6806016</a><br />
    <button id="supAumW22a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1016/j.jsv.2022.117363"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.6567552">Code, data and results for
    numerical experiments in &ldquo;Context-aware controller inference for
    stabilizing dynamical systems from scarce data&rdquo;
    (version 1.0)</a>,
    July 2022. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.6567552">10.5281/zenodo.6567552</a><br />
    <button id="supWer22c-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1098/rspa.2022.0506"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.5793356">Code, data and results for
    numerical experiments in &ldquo;A unifying framework for tangential
    interpolation of structured bilinear control systems&rdquo;
    (version 1.0)</a>,
    June 2022. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.5793356">10.5281/zenodo.5793356</a><br />
    <button id="supWer22c-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s00211-023-01380-w"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.6403121">Code, data and results for
    numerical experiments in &ldquo;Multifidelity robust controller design
    with gradient sampling&rdquo;
    (version 1.0)</a>,
    May 2022. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.6403121">10.5281/zenodo.6403121</a><br />
    <button id="supWer22b-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1137/22M1500137"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/badge/License-GPLv3-blue.svg"
    alt="License: GPLv3" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.6308400">Code, data and results for
    numerical experiments in &ldquo;A low-rank solution method for Riccati
    equations with indefinite quadratic terms&rdquo;
    (version 2.0)</a>,
    March 2022. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.6308400">10.5281/zenodo.6308400</a><br />
    <button id="supWer22a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s11075-022-01331-w"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.5902997">Code, data and results for
    numerical experiments in &ldquo;On the sample complexity of stabilizing
    linear dynamical systems from data&rdquo;
    (version 1.0)</a>,
    February 2022. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.5902997">10.5281/zenodo.5902997</a><br />
    <button id="supWer22-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s10208-023-09605-y"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  Q. Aumann and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.5836047">Code, data and results for
    numerical experiments in &ldquo;Structured model order reduction for
    vibro-acoustic problems using interpolation and balancing methods&rdquo;
    (version 1.0)</a>,
    January 2022. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.5836047">10.5281/zenodo.5836047</a><br />
    <button id="supAumW22-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1016/j.jsv.2022.117363"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.5155993">Code, data and results for
    numerical experiments in &ldquo;A low-rank solution method for riccati
    equations with indefinite quadratic terms&rdquo; (version 1.0)</a>,
    November 2021. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.5155993">10.5281/zenodo.5155993</a><br />
    <button id="supWer21c-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s11075-022-01331-w"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.5539944">Code, data and results for
    numerical experiments in &ldquo;Structured vector fitting framework for
    mechanical systems&rdquo; (version 1.0)</a>, October 2021. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.5539944">10.5281/zenodo.5539944</a><br />
    <button id="supWer21b-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1016/j.ifacol.2022.09.089"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  J. Heiland and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.5532539">Code, data and results for
    numerical experiments in &ldquo;Robust output-feedback stabilization for
    incompressible flows using low-dimensional
    \\(\mathcal{H}_{\infty}\\)-controllers&rdquo; (version 2.0)</a>,
    October 2021. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.5532539">10.5281/zenodo.5532539</a><br />
    <button id="supHeiW21a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s10589-022-00359-x"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-green.svg"
    alt="License: MIT" class="badge"></a>
    
1.  R. Jendersie and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.4745518">Results of numerical
    experiments in &ldquo;A comparison
    of numerical methods for model reduction of dense discrete-time
    systems&rdquo; (version 1.0)</a>, May 2021. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.4745518">10.5281/zenodo.4745518</a><br />
    <button id="supJenW21-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1515/auto-2021-0035"><button
    class="btn btn--inverse">Paper</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    <a href="https://creativecommons.org/licenses/by/4.0">
    <img src="https://licensebuttons.net/l/by/3.0/88x31.png"
    alt="License: CC BY 4.0" class="badge"></a>
    
1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.4650422">Results of numerical
    experiments in &ldquo;Structure-Preserving Model Reduction for Mechanical
    Systems&rdquo; (version 1.0)</a>, April 2021. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.4650422">10.5281/zenodo.4650422</a><br />
    <button id="supWer21a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.25673/38617"><button
    class="btn btn--inverse">Paper</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    <a href="https://creativecommons.org/licenses/by/4.0">
    <img src="https://licensebuttons.net/l/by/3.0/88x31.png"
    alt="License: CC BY 4.0" class="badge"></a>
    
1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.4650402">Code and data for numerical
    experiments in &ldquo;Structure-Preserving Model Reduction for Mechanical
    Systems&rdquo; (version 1.0)</a>, April 2021. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.4650402">10.5281/zenodo.4650402</a><br />
    <button id="supWer21-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.25673/38617"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>
    
1.  J. Heiland and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.4507759">Code, data and results for
    numerical experiments in &ldquo;Robust output-feedback stabilization for
    incompressible flows using low-dimensional
    \\(\mathcal{H}_{\infty}\\)-controllers&rdquo; (version 1.0)</a>,
    March 2021. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.4507759">10.5281/zenodo.4507759</a><br />
    <button id="supHeiW21-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s10589-022-00359-x"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-green.svg"
    alt="License: MIT" class="badge"></a>
    
1.  J. Saak and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.3865495">Parametric and two-step model
    reduction using M-M.E.S.S. and MORLAB (version 1.1)</a>, June 2020. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.3865495">10.5281/zenodo.3865495</a><br />
    <button id="supSaaW20a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/978-3-030-72983-7_19"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/badge/License-AGPLv3+-blue.svg"
    alt="License: AGPLv3+" class="badge"></a>
    
1.  J. Saak and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.3678213">Parametric and two-step model
    reduction using M-M.E.S.S. and MORLAB (version 1.0)</a>, February 2020.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.3678213">10.5281/zenodo.3678213</a><br />
    <button id="supSaaW20-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/978-3-030-72983-7_19"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/badge/License-AGPLv3+-blue.svg"
    alt="License: AGPLv3+" class="badge"></a>
    
1.  J. Saak, D. Siebelts, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.5281/zenodo.2564050">Reduction
    results for an artificial fish tail (version 19-02-14)</a>, February 2019.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.2564050">10.5281/zenodo.2564050</a><br />
    <button id="supSaaSW19a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1515/auto-2019-0027"><button
    class="btn btn--inverse">Paper</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    <a href="https://creativecommons.org/licenses/by/4.0">
    <img src="https://licensebuttons.net/l/by/3.0/88x31.png"
    alt="License: CC BY 4.0" class="badge"></a>
    
1.  J. Saak, D. Siebelts, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.5281/zenodo.2563874">Second order
    reduction comparison for the fishtail model (version 1.0)</a>, February 2019.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.2563874">10.5281/zenodo.2563874</a><br />
    <button id="supSaaSW19-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1515/auto-2019-0027"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/badge/License-GPLv3-blue.svg"
    alt="License: GPLv3" class="badge"></a>
-->

<!-- Javascripts for Buttons and BibTeX content. -->
<!-->
<div id="includedBibTeX"></div>
<div id="includedCitation"></div>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/magnific-popup.css"/>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/jquery.magnific-popup.min.js"></script>
<script> 
  $(function(){
    $("#includedBibTeX").load("{{ base_path }}/files/software/bibtex.html");
    $("#includedCitation").load("{{ base_path }}/files/software/citation.html");
  });
</script> -->
