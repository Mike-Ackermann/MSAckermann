---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#submitted">Submitted Articles (2)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#journal">Journal Articles (3)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#proceedings">Proceedings (1)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#software">Software (4)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#theses">Theses (1)</a>
</p>


You can also find my publications on my
<a target="blank_" href="{{ author.googlescholar }}">Google Scholar</a>
and <a target="blank_" href="{{ author.orcid }}">ORCID</a> profiles.
A detailed list of citable code packages accompaning my publications can be
found at the end of my
<a href="{{ base_path }}/software/#codepackages">Software</a> page.

<style>
  p {
    word-wrap: break-word;
    overflow-wrap: break-word;
  }
</style>

---

## <a name="submitted"></a>Submitted Articles ##

1.  <strong>M. S. Ackermann</strong>, L. Balicki, S. Gugercin, and
    S. W. R. Werner.
    <a target="blank_"
    href="https://arxiv.org/abs/2601.19813">The NLAAA algorithm for rational
    approximation &ndash; applications to model order reduction</a>.
    Submitted to Research in the Mathematical Sciences.
    e-print 2601.19813, arXiv, 2026.<br />
    <a target="blank_" href="https://arxiv.org/abs/2601.19813">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.18317028">
    <button class="btn btn--inverse">Code & Data</button></a>

---

## <a name="journal"></a>Journal Articles ##

1.  <strong>M. S. Ackermann</strong>, S. W. R. Werner, I. V. Gosea, and
    S. Gugercin.
    <a target="blank_"
    href="https://doi.org/10.1007/s10444-026-10347-y">Second-order AAA algorithms for
    structured data-driven modeling</a>.
    <i>Advances in Computational Mathematics<i>, 52(5):76, 2026
    doi:<a target="blank_" href="https://doi.org/10.1007/s10444-026-10347-y">10.1007/s10444-026-10347-y</a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.19895043">
    <button class="btn btn--inverse">Code & Data</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

1.  <strong>M. S. Ackermann</strong>, S. Reiter, and L. N. Trefethen.
    <a target="blank_"
    href="https://doi.org/10.1007/s40687-026-00650-x">L<sup>2</sup> and
    L<sup>&infin;</sup> rational approximation on the unit disk</a>.
    <i>Research in the Mathematical Sciences</i>, 13(3), 2026.
    doi:<a target="blank_" href="https://doi.org/10.1007/s40687-026-00650-x">10.1007/s40687-026-00650-x</a><br />
    <a target="blank_" href="https://zenodo.org/records/18746402">
    <button class="btn btn--inverse">Code & Data</button></a>

1.  <strong>M. S. Ackermann</strong> and S. Gugercin.
    <a target="blank_"
    href="https://doi.org/10.1137/24M1678167">Time-domain iterative rational
    Krylov method</a>.
    <i>SIAM Journal on Scientific Computing</i>, 47(3):A1628&ndash;A1651, 2025.
    doi:<a target="blank_" href="https://doi.org/10.1137/24M1678167">10.1137/24M1678167</a><br />
    <a target="blank_" href="https://doi.org/10.5281/zenodo.12751391">
    <button class="btn btn--inverse">Code & Data</button></a>

1.  <strong>M. S. Ackermann</strong> and S. Gugercin.
    <a target="blank_"
    href="https://doi.org/10.1137/23M1624130">Frequency-based reduced models
    from purely time-domain data via data informativity</a>.
    <i>SIAM Journal on Scientific Computing</i>, 47(2):A1225&ndash;A1250, 2025.
    doi:<a target="blank_" href="https://doi.org/10.1137/23M1624130">10.1137/23M1624130</a><br />
    <a target="blank_" href="https://doi.org/10.5281/zenodo.10076325">
    <button class="btn btn--inverse">Code & Data</button></a>

---

## <a name="proceedings"></a>Proceedings ##

1.  <strong>M. S. Ackermann</strong>, P. Bochev, and D. Ridzal.
    <a target="blank_"
    href="https://www.sandia.gov/ccr/csri-summer-programs/computer-science-research-institute-summer-proceedings-2025/">
    Towards a reduced model for hyperbolic partial differential equations</a>.
    Technical report SAND2025-14267O, The Computer Science Research Institute
    at Sandia National Laboratories, Albuquerque, New Mexico,
    pages 3&ndash;16, 2025.
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

---

## <a name="software"></a>Software ##

1.  <strong>M. S. Ackermann</strong> and S. W. R. Werner.
    <a target="blank_"
    href="https://doi.org/10.5281/zenodo.19895043">Code, data and results
    for numerical experiments in "Second-order AAA algorithms for structured
    data-driven modeling" (version 1.1)</a>, May 2026.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.19895043">10.5281/zenodo.19895043</a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>M. S. Ackermann</strong>, S. W. R. Werner, and L. Balicki.
    <a target="blank_"
    href="https://doi.org/10.5281/zenodo.18317028">Code, data and results
    for numerical experiments in "A refined nonlinear least-squares method
    for the rational approximation problem"</a>, January 2026.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.18317028">10.5281/zenodo.18317028</a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>M. S. Ackermann</strong>.
    <a target="blank_"
    href="https://doi.org/10.5281/zenodo.12751391">Code and Data for the
    Numerical Experiments in "Time-Domain Iterative Rational Krylov
    Method"</a>, July 2024.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.12751391">10.5281/zenodo.12751391</a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>M. S. Ackermann</strong>.
    <a target="blank_"
    href="https://doi.org/10.5281/zenodo.10076325">Code and Data for the
    numerical experiments in "Frequency-Based Reduced Models from Purely
    Time-Domain Data via Data Informativity" (version 1.0)</a>, November 2023.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.10076325">10.5281/zenodo.10076325</a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

---

## <a name="theses"></a>Theses ##

1.  <strong>M. S. Ackermann</strong>. 
    <a target="blank_"
    href="http://hdl.handle.net/10919/110851">Frequency-domain learning of dynamical</a>
    systems from time-domain data. Thesis, Virginia Tech, 92 pages,
    June 2022.
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

<!-- Javascripts for Buttons and BibTeX content. -->


<div id="includedBibTeX"></div>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/magnific-popup.css"/>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/jquery.magnific-popup.min.js"></script>
<script> 
  $(function(){
    $("#includedBibTeX").load("{{ base_path }}/files/publications/bibtex.html"); 
  });
</script>