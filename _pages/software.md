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


## Supplementary code packages and data ##

1.  <strong>M. S. Ackermann</strong> and S. W. R. Werner.
    <a target="blank_"
    href="https://doi.org/10.5281/zenodo.19895043">Code, data and results
    for numerical experiments in "Second-order AAA algorithms for structured
    data-driven modeling" (version 1.1)</a>, May 2026.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.19895043">10.5281/zenodo.19895043</a><br />
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  S. Reiter, <strong>M. S. Ackermann</strong> and L. N. Trefethen.
    <a target="blank_"
    href="https://doi.org/10.5281/zenodo.18746402">Code and Results for Numerical Experiments in "L<sup>2</sup> and
    L<sup>&infin;</sup> rational approximation on the unit disk" (version 1.0)</a>, February 2026.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.18746402">10.5281/zenodo.18746402</a><br />
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
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.18317028">10.5281/zenodo.18317028</a><br />
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
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.12751391">10.5281/zenodo.12751391</a><br />
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
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.10076325">10.5281/zenodo.10076325</a><br />
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

<!-- Javascripts for Buttons and BibTeX content. -->

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
</script>
