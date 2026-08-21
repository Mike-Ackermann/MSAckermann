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
  <a href="#submitted">Submitted Articles (4)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#journal">Journal Articles (23)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#bookchapters">Book Chapters (3)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#proceedings">Proceedings (11)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#software">Software (10)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#theses">Theses (3)</a>
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

1.  S. Reiter and <strong>S. W. R. Werner</strong>.
    <a target="blank_"
    href="https://doi.org/10.48550/arXiv.2606.00298">Symmetric Hermite
    quadrature-based balanced truncation for learning linear dynamical systems
    from derivative data</a>.
    e-print 2606.00298, arXiv, 2026. Numerical Analysis (math.NA).
    doi:<a target="blank_" href="https://doi.org/10.48550/arXiv.2606.00298">10.48550/arXiv.2606.00298</a><br />
    <button id="ReiW26-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2606.00298">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.20384015">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  M. S. Ackermann, L. Balicki, S. Gugercin, and <strong>S. W. R. Werner</strong>.
    <a target="blank_"
    href="https://doi.org/10.48550/arXiv.2601.19813">A refined nonlinear
    least-squares method for the rational approximation problem</a>.
    e-print 2601.19813, arXiv, 2026. Numerical Analysis (math.NA).
    doi:<a target="blank_" href="https://doi.org/10.48550/arXiv.2601.19813">10.48550/arXiv.2601.19813</a><br />
    <button id="AckBGetal26-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2601.19813">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.18317028">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  R. Smith and <strong>S. W. R. Werner</strong>.
    <a target="blank_"
    href="https://doi.org/10.48550/arXiv.2512.04983">A tangential low-rank ADI
    method for solving indefinite Lyapunov equations</a>.
    e-print 2512.04983, arXiv, 2025. Numerical Analysis (math.NA).
    doi:<a target="blank_" href="https://doi.org/10.48550/arXiv.2512.04983">10.48550/arXiv.2512.04983</a><br />
    <button id="SmiW25-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2512.04983">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.17632592">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  M. S. Ackermann, I. V. Gosea, S. Gugercin, and
    <strong>S. W. R. Werner</strong>.
    <a target="blank_"
    href="https://doi.org/10.48550/arXiv.2506.02241">Second-order AAA algorithms
    for structured data-driven modeling</a>.
    e-print 2506.02241, arXiv, 2025. Numerical Analysis (math.NA).
    doi:<a target="blank_" href="https://doi.org/10.48550/arXiv.2506.02241">10.48550/arXiv.2506.02241</a><br />
    <button id="AckGGetal25-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2506.02241">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.15389438">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

---

## <a name="journal"></a>Journal Articles ##

1.  <strong>S. W. R. Werner</strong> and B. Peherstorfer.
    <a target="blank_"
    href="https://doi.org/10.1137/25M176550X">An adaptive data sampling
    strategy for stabilizing dynamical systems via controller inference</a>.
    <i>SIAM J. Sci. Comput.</i>, 48(4):C736&ndash;C761, 2026.
    doi:<a target="blank_" href="https://doi.org/10.1137/25M176550X">10.1137/25M176550X</a><br />
    <button id="WerP26-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2506.01816">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.8183173">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  S. Reiter and <strong>S. W. R. Werner</strong>.
    <a target="blank_"
    href="https://doi.org/10.1137/25M1768217">Data-driven balanced
    truncation for second-order systems with generalized proportional damping</a>.
    <i>SIAM J. Sci. Comput.</i>, 48(3):C526&ndash;C552, 2026.
    doi:<a target="blank_" href="https://doi.org/10.1137/25M1768217">10.1137/25M1768217</a><br />
    <button id="ReiW26a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2506.10118">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.18148591">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  J. Heiland, Y. Kim, and <strong>S. W. R. Werner</strong>.
    <a target="blank_"
    href="https://doi.org/10.1007/s10444-025-10269-1">Deep polytopic
    autoencoders for low-dimensional linear parameter-varying approximations
    and nonlinear feedback design</a>.
    <i>Adv. Comput. Math.</i>, 51(6):55, 2025.
    doi:<a target="blank_" href="https://doi.org/10.1007/s10444-025-10269-1">10.1007/s10444-025-10269-1</a><br />
    <button id="HeiKW25-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2403.18044">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.10783695">
    <button class="btn btn--inverse">Code, Data & Results</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

1.  <strong>S. W. R. Werner</strong> and B. Peherstorfer. <a
    target="blank_"
    href="https://doi.org/10.1016/j.cma.2024.117483">System stabilization with
    policy optimization on unstable latent manifolds</a>.
    <i>Comput. Methods Appl. Mech. Eng.</i>, 433, Part A:117483, 2025.
    doi:<a target="blank_" href="https://doi.org/10.1016/j.cma.2024.117483">10.1016/j.cma.2024.117483</a><br />
    <button id="WerP25-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2407.06418">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.7897240">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  J. Saak and <strong>S. W. R. Werner</strong>. <a
    target="blank_"
    href="https://doi.org/10.1553/etna_vol62s95">Using \\(LDL^{T}\\)
    factorizations in Newton's method for solving general large-scale
    algebraic Riccati equations</a>.
    <i>Electron. Trans. Numer. Anal.</i>, 62:95&ndash;118, 2024.
    doi:<a target="blank_" href="https://doi.org/10.1553/etna_vol62s95">10.1553/etna_vol62s95</a><br />
    <button id="SaaW24-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2402.06844">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.11390499">
    <button class="btn btn--inverse">Code, Data & Results</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

1.  Q. Aumann and <strong>S. W. R. Werner</strong>. <a
    target="blank_"
    href="https://doi.org/10.1007/s10444-024-10166-z">Adaptive choice of
    near-optimal expansion points for interpolation-based structure-preserving
    model reduction</a>.
    <i>Adv. Comput. Math.</i>, 50(4):79, 2024.
    doi:<a target="blank_" href="https://doi.org/10.1007/s10444-024-10166-z">10.1007/s10444-024-10166-z</a><br />
    <button id="AumW24-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2305.10806">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.10945494">
    <button class="btn btn--inverse">Code, Data & Results</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

1.  <strong>S. W. R. Werner</strong> and B. Peherstorfer. <a
    target="blank_" href="https://doi.org/10.1007/s10208-023-09605-y">On the
    sample complexity of stabilizing linear dynamical systems from data</a>.
    <i>Found. Comput. Math.</i>, 24(3):955&ndash;987, 2024.
    doi:<a target="blank_" href="https://doi.org/10.1007/s10208-023-09605-y">10.1007/s10208-023-09605-y</a><br />
    <button id="WerP24-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2203.00474">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.5902997">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  I. V. Gosea, S. Gugercin, and <strong>S. W. R. Werner</strong>. <a
    target="blank_"
    href="https://doi.org/10.1007/s10444-024-10118-7">Structured barycentric
    forms for interpolation-based data-driven reduced modeling of second-order
    systems</a>.
    <i>Adv. Comput. Math.</i>, 50(2):26, 2024.
    doi:<a target="blank_" href="https://doi.org/10.1007/s10444-024-10118-7">10.1007/s10444-024-10118-7</a><br />
    <button id="GosGW24-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2303.12576">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.7358813">
    <button class="btn btn--inverse">Code, Data & Results</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

1.  P. Benner, S. Gugercin, and <strong>S. W. R. Werner</strong>. <a
    target="blank_"
    href="https://doi.org/10.1007/s10444-024-10109-8">Structured interpolation
    for multivariate transfer functions of quadratic-bilinear systems</a>.
    <i>Adv. Comput. Math.</i>, 50(2):18, 2024.
    doi:<a target="blank_" href="https://doi.org/10.1007/s10444-024-10109-8">10.1007/s10444-024-10109-8</a><br />
    <button id="BenGW24-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2304.14292">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.10116600">
    <button class="btn btn--inverse">Code, Data & Results</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

1.  P. Benner, S. Gugercin, and <strong>S. W. R. Werner</strong>. <a
    target="blank_"
    href="https://doi.org/10.1007/s00211-023-01380-w">A unifying framework for
    tangential interpolation of structured bilinear control systems</a>.
    <i>Numer. Math.</i>, 155(3&ndash;4):445&ndash;483, 2023.
    doi:<a target="blank_" href="https://doi.org/10.1007/s00211-023-01380-w">10.1007/s00211-023-01380-w</a><br />
    <button id="BenGW23a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2206.01657">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.5793356">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  J. Heiland and <strong>S. W. R. Werner</strong>. <a
    target="blank_"
    href="https://doi.org/10.1109/LCSYS.2023.3291231">Low-complexity linear
    parameter-varying approximations of incompressible Navier-Stokes equations
    for truncated state-dependent Riccati feedback</a>.
    <i>IEEE Control Syst. Lett.</i>, 7:3012&ndash;3017, 2023.
    doi:<a target="blank_" href="https://doi.org/10.1109/LCSYS.2023.3291231">10.1109/LCSYS.2023.3291231</a><br />
    <button id="HeiW23a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2303.11515">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.7977616">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  <strong>S. W. R. Werner</strong>, M. L. Overton, and B. Peherstorfer. <a
    target="blank_"
    href="https://doi.org/10.1137/22M1500137">Multifidelity robust
    controller design with gradient sampling</a>.
    <i>SIAM J. Sci. Comput.</i>, 45(2):A933&ndash;A957, 2023.
    doi:<a target="blank_" href="https://doi.org/10.1137/22M1500137">10.1137/22M1500137</a><br />
    <button id="WerOP23-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2205.15050">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.6403121">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  <strong>S. W. R. Werner</strong> and B. Peherstorfer. <a
    target="blank_"
    href="https://doi.org/10.1098/rspa.2022.0506">Context-aware controller
    inference for stabilizing dynamical systems from scarce data</a>.
    <i>Proc. R. Soc. A: Math. Phys. Eng. Sci.</i>, 479(2270):20220506, 2023.
    doi:<a target="blank_" href="https://doi.org/10.1098/rspa.2022.0506">10.1098/rspa.2022.0506</a><br />
    <button id="WerP23a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2207.11049">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.7530566">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  P. Benner, J. Heiland, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.1007/s11075-022-01331-w">A
    low-rank solution method for Riccati equations with indefinite quadratic
    terms</a>.
    <i>Numer. Algorithms</i>, 92(2):1083&ndash;1103, 2023.
    doi:<a target="blank_" href="https://doi.org/10.1007/s11075-022-01331-w">10.1007/s11075-022-01331-w</a><br />
    <button id="BenHW23-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2111.06516">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.6308400">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  Q. Aumann and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.1016/j.jsv.2022.117363">Structured
    model order reduction for vibro-acoustic problems using interpolation and
    balancing methods</a>.
    <i>J. Sound Vib.</i>, 543:117363, 2023.
    doi:<a target="blank_" href="https://doi.org/10.1016/j.jsv.2022.117363">10.1016/j.jsv.2022.117363</a><br />
    <button id="AumW23-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2201.06518">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.6806016">
    <button class="btn btn--inverse">Code, Data & Results</button></a>

1.  P. Benner, J. Heiland, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.1007/s10589-022-00359-x">Robust 
    output-feedback stabilization for incompressible flows using
    low-dimensional \\(\mathcal{H}_{\infty}\\)-controllers</a>.
    <i>Comput. Optim. Appl.</i>, 82(1):225&ndash;249, 2022.
    doi:<a target="blank_" href="https://doi.org/10.1007/s10589-022-00359-x">10.1007/s10589-022-00359-x</a><br />
    <button id="BenHW22-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2103.01608">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.4507758">
    <button class="btn btn--inverse">Code, Data & Results</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

1.  P. Benner, Y. Filanova, D. Karachalios, S. Monem Abdelhafez, J. Przybilla,
    and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.1515/dmvm-2021-0075">
    Mathematische Komplexitätsreduktion: Modellreduktion dynamischer
    Systeme</a>. <i>Mitteilungen der Deutschen Mathematiker-Vereinigung</i>,
    29(4):198&ndash;204, 2021.
    doi:<a target="blank_" href="https://doi.org/10.1515/dmvm-2021-0075">10.1515/dmvm-2021-0075</a><br />
    <button id="BenFKetal21-pop" class="btn btn--inverse">BibTeX</button>

1.  R. Jendersie and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.1515/auto-2021-0035">
    A comparison of numerical methods for model reduction of dense
    discrete-time systems</a>.
    <i>at-Automatisierungstechnik</i>, 69(8):683&ndash;694, 2021.
    doi:<a target="blank_" href="https://doi.org/10.1515/auto-2021-0035">10.1515/auto-2021-0035</a><br />
    <button id="JenW21-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.4745517">
    <button class="btn btn--inverse">Results</button></a>

1.  P. Benner, S. Gugercin, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.1016/j.automatica.2021.109799">
    Structure-preserving interpolation for model reduction of parametric 
    bilinear systems</a>. <i>Automatica</i>, 132:109799, 2021. 
    doi:<a target="blank_" href="https://doi.org/10.1016/j.automatica.2021.109799">10.1016/j.automatica.2021.109799</a><br />
    <button id="BenGW21-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2007.11269">
    <button class="btn btn--inverse">Preprint</button></a>

1.  P. Benner, S. Gugercin, and <strong>S. W. R. Werner</strong>. <a 
    target="blank_" 
    href="https://doi.org/10.1007/s10444-021-09863-w">Structure-preserving 
    interpolation of bilinear control systems</a>. <i>Adv. Comput. Math.</i>, 
    47(3):43, 2021. doi:<a target="blank_" href="https://doi.org/10.1007/s10444-021-09863-w">10.1007/s10444-021-09863-w</a><br />
    <button id="BenGW21a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2005.00795">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1016/j.laa.2020.06.024">Frequency- and time-limited
    balanced truncation for large-scale second-order systems</a>. <i>Linear
    Algebra Appl.</i>, 623:68–103, 2021. Special issue in honor of P. Van 
    Dooren, Edited by F. Dopico, D. Kressner, N. Mastronardi, V. Mehrmann, and 
    R. Vandebril. doi:<a target="blank_" href="https://doi.org/10.1016/j.laa.2020.06.024">10.1016/j.laa.2020.06.024</a><br />
    <button id="BenW21b-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2001.06185">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1007/s10444-020-09750-w">Hankel-norm approximation
    of large-scale descriptor systems</a>. <i>Adv. Comput. Math.</i>,
    46(3):40, 2020. doi:<a target="blank_" href="https://doi.org/10.1007/s10444-020-09750-w">10.1007/s10444-020-09750-w</a><br />
    <button id="BenW20d-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://arxiv.org/abs/1612.06205">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    
1.  J. Saak, D. Siebelts, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.1515/auto-2019-0027">A comparison
    of second-order model order reduction methods for an artificial
    fishtail</a>. <i>at-Automatisierungstechnik</i>, 67(8):648&ndash;667, 2019.
    doi:<a target="blank_" href="https://doi.org/10.1515/auto-2019-0027">10.1515/auto-2019-0027</a><br />
    <button id="SaaSW19-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.2563873">
    <button class="btn btn--inverse">Code</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.2558728">
    <button class="btn btn--inverse">Data</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.2564049">
    <button class="btn btn--inverse">Results</button></a>

---

## <a name="bookchapters"></a>Book Chapters ##

1.  R. S. Beddig, P. Benner, I. Dorschky, T. Reis, P. Schwerdtner, M. Voigt, and
    <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1007/978-3-031-36143-2_11">Structure-preserving model
    reduction for dissipative mechanical systems</a>.
    In P. Eberhard, editor,
    <i>Calm, Smooth and Smart</i>, volume 102 of
    <i>Lect. Notes Appl. Comput. Mech.</i>,
    pages 209&ndash;230.
    Springer, Cham, 2024.
    doi:<a target="blank_" href="https://doi.org/10.1007/978-3-031-36143-2_11">10.1007/978-3-031-36143-2_11</a><br />
    <button id="BedBDetal24-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2010.06331">
    <button class="btn btn--inverse">Preprint</button></a>

1. P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1007/978-3-030-72983-7_19">MORLAB&mdash;The Model 
    Order Reduction LABoratory</a>. In P. Benner, T. Breiten, H. Faßbender,
    M. Hinze, T. Stykel, and R. Zimmermann, editors,
    <i>Model Reduction of Complex Dynamical Systems</i>, volume 117 of
    <i>International Series of Numerical Mathematics</i>,
    pages 393&ndash;415. Birkhäuser, Cham, 2021.
    doi:<a target="blank_" href="https://doi.org/10.1007/978-3-030-72983-7_19">10.1007/978-3-030-72983-7_19</a><br />
    <button id="BenW21c-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2002.12682">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.3678212">
    <button class="btn btn--inverse">Code</button></a>

1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1007/978-3-030-52200-1_43">MORLAB &ndash; A model
    order reduction framework in MATLAB and Octave</a>. In A. M. Bigatti, J.
    Carette, J. H. Davenport, M. Joswig, and T. de Wolff, editors,
    <i>Mathematical Software &ndash; ICMS 2020</i>, volume 12097 of 
    <i>Lecture Notes in Comput. Sci.</i>, pages 432&ndash;441.
    Springer International Publishing, Cham, 2020.
    doi:<a target="blank_" href="https://doi.org/10.1007/978-3-030-52200-1_43">10.1007/978-3-030-52200-1_43</a><br />
    <button id="BenW20e-pop" class="btn btn--inverse">BibTeX</button>

---

## <a name="proceedings"></a>Proceedings ##

1.  S. Reiter and <strong>S. W. R. Werner</strong>. <a
    target="blank_"
    href="https://doi.org/10.1016/j.ifacol.2025.03.066">Interpolatory model
    reduction of dynamical systems with root mean squared error</a>.
    <i>IFAC-Pap.</i>, 59(1):385&ndash;390, 2025.
    11th Vienna International Conference on Mathematical Modelling MATHMOD
    2025.
    doi:<a target="blank_" href="https://doi.org/10.1016/j.ifacol.2025.03.066">10.1016/j.ifacol.2025.03.066</a><br />
    <button id="ReiW25-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2403.08894">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.11557038">
    <button class="btn btn--inverse">Code & Results</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

1.  P. Benner, S. Gugercin, and <strong>S. W. R. Werner</strong>. <a
    target="blank_"
    href="https://doi.org/10.1002/pamm.202400048">Structure-preserving
    interpolation of quadratic-bilinear systems via regular multivariate
    transfer functions</a>.
    <i>Proc. Appl. Math. Mech.</i>, 24(3):e202400048, 2024.
    doi:<a target="blank_" href="https://doi.org/10.1002/pamm.202400048">10.1002/pamm.202400048</a><br />
    <button id="BenGW24a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2110.09220">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.10946483">
    <button class="btn btn--inverse">Code, Data & Results</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

1.  <strong>S. W. R. Werner</strong>, I. V. Gosea, and S. Gugercin. <a
    target="blank_"
    href="https://doi.org/10.1016/j.ifacol.2022.09.089">Structured vector
    fitting framework for mechanical systems</a>.
    <i>IFAC-Pap.</i>, 55(20):163&ndash;168, 2022.
    10th Vienna International Conference on Mathematical Modelling MATHMOD
    2022.
    doi:<a target="blank_" href="https://doi.org/10.1016/j.ifacol.2022.09.089">10.1016/j.ifacol.2022.09.089</a><br />
    <button id="WerGG22-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2110.09220">
    <button class="btn btn--inverse">Preprint</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.5539944">
    <button class="btn btn--inverse">Code, Data & Results</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://www.control.tf.uni-kiel.de/en/gma-fa-1.40/archiv-1/workshop-2019-fa-1.30">
    Frequenz- und zeitbeschränktes balanciertes
    Abschneiden für Systeme zweiter Ordnung</a>. In T. Meurer and F.
    Woittennek, editors, <i>Tagungsband GMA-FA 1.30 'Modellbildung,
    Identifikation und Simulation in der Automatisierungstechnik' und
    GMA-FA 1.40 'Systemtheorie und Regelungstechnik', Workshops in Anif,
    Salzburg, 23.-27.09.2019</i>, pages 460&ndash;474, 2019.<br />
    <button id="BenW19d-pop" class="btn btn--inverse">BibTeX</button>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://www.control.tf.uni-kiel.de/en/gma-fa-1.40/archiv-1/workshop-2019-fa-1.30">
    MORLAB – Model Order Reduction LABoratory</a>. In T. Meurer and F.
    Woittennek, editors, <i>Tagungsband GMA-FA 1.30 'Modellbildung,
    Identifikation und Simulation in der Automatisierungstechnik' und
    GMA-FA 1.40 'Systemtheorie und Regelungstechnik', Workshops in Anif,
    Salzburg, 23.-27.09.2019</i>, pages 337&ndash;342, 2019.<br />
    <button id="BenW19c-pop" class="btn btn--inverse">BibTeX</button>
    
1.  R. S. Beddig, P. Benner, I. Dorschky, T. Reis, P. Schwerdtner, M. Voigt, and
    <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1002/pamm.201900224">Model reduction for
    second-order dynamical systems revisited</a>. <i>Proc. Appl. Math.
    Mech.</i>, 19(1):e201900224, 2019. doi:<a target="blank_" href="https://doi.org/10.1002/pamm.201900224">10.1002/pamm.201900224</a><br />
    <button id="BedBDetal19-pop" class="btn btn--inverse">BibTeX</button>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    
1.  P. Benner, J. Heiland, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.1016/j.ifacol.2019.08.005">Robust
    controller versus numerical model uncertainties for stabilization of
    Navier-Stokes equations</a>. <i>IFAC-Pap.</i>,
    52(2):25&ndash;29, 2019. 3rd IFAC/IEEE CSS Workshop on Control of Systems
    Governed by Partial Differential Equation CPDE 2019.
    doi:<a target="blank_" href="https://doi.org/10.1016/j.ifacol.2019.08.005">10.1016/j.ifacol.2019.08.005</a><br />
    <button id="BenHW19-pop" class="btn btn--inverse">BibTeX</button>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1002/pamm.201800083">Balancing related model
    reduction with the MORLAB toolbox</a>. <i>Proc. Appl. Math. Mech.</i>,
    18(1):e201800083, 2018. doi:<a target="blank_" href="https://doi.org/10.1002/pamm.201800083">10.1002/pamm.201800083</a><br />
    <button id="BenW18a-pop" class="btn btn--inverse">BibTeX</button>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1016/j.ifacol.2018.03.092">Model reduction of
    descriptor systems with the MORLAB toolbox</a>. <i>IFAC-Pap.</i>,
    51(2):547&ndash;552, 2018. 9th Vienna International Conference on
    Mathematical Modelling MATHMOD 2018.
    doi:<a target="blank_" href="https://doi.org/10.1016/j.ifacol.2018.03.092">10.1016/j.ifacol.2018.03.092</a><br />
    <button id="BenW18-pop" class="btn btn--inverse">BibTeX</button>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://www.control.tf.uni-kiel.de/en/gma-fa-1.40/archiv-1/workshop-2017-fa-1.30">
    MORLAB - Modellreduktion in MATLAB</a>. In T. Meurer and F. Woittennek,
    editors, <i>Tagungsband GMA-FA 1.30 'Modellierung, Identifikation und
    Simulation in der Automatisierungstechnik' und GMA-FA 1.40 'Theoretische
    Verfahren der Regelungstechnik', Workshop in Anif, Salzburg,
    18.-22.09.2017</i>, pages 508&ndash;517, 2017.<br />
    <button id="BenW17b-pop" class="btn btn--inverse">BibTeX</button>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1002/pamm.201710379">On the transformation formulas
    of the Hankel-norm approximation</a>. <i>Proc. Appl. Math. Mech.</i>,
    17(1):823&ndash;824, 2017. doi:<a target="blank_" href="https://doi.org/10.1002/pamm.201710379">10.1002/pamm.201710379</a><br />
    <button id="BenW17-pop" class="btn btn--inverse">BibTeX</button>

---

## <a name="software"></a>Software ##
1.  P. Benner, J. Saak, and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.7072831">MORLAB &ndash; Model Order
    Reduction LABoratory (version 6.0)</a>, September 2023.
    See also: <a target="blank_" href="https://www.mpi-magdeburg.mpg.de/projects/morlab">
    https://www.mpi-magdeburg.mpg.de/projects/morlab</a>.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.7072831">10.5281/zenodo.7072831</a><br />
    <button id="BenSW23-pop" class="btn btn--inverse">BibTeX</button>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.4600763">SOLBT &ndash; Limited balanced 
    truncation for large-scale sparse second-order systems (version 3.0)</a>, 
    April 2021. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.4600763">10.5281/zenodo.4600763</a><br />
    <button id="BenW21a-pop" class="btn btn--inverse">BibTeX</button>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.3997649">SOMDDPA &ndash; Second-Order
    Modally-Damped Dominant Pole Algorithm (version 2.0)</a>, April 2021.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.3997649">10.5281/zenodo.3997649</a><br />
    <button id="BenW21-pop" class="btn btn--inverse">BibTeX</button>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.3332706">SOMDDPA &ndash; Second-Order
    Modally-Damped Dominant Pole Algorithm (version 1.1)</a>, January 2020.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.3332706">10.5281/zenodo.3332706</a><br />
    <button id="BenW20a-pop" class="btn btn--inverse">BibTeX</button>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/gpl-3.0">
    <img src="https://img.shields.io/badge/License-GPLv3+-blue.svg"
    alt="License: GPLv3+" class="badge"></a>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.3331592">Limited balanced truncation
    for large-scale sparse second-order systems (version 2.0)</a>, January 2020.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.3331592">10.5281/zenodo.3331592</a><br />
    <button id="BenW20-pop" class="btn btn--inverse">BibTeX</button>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/gpl-3.0">
    <img src="https://img.shields.io/badge/License-GPLv3+-blue.svg"
    alt="License: GPLv3+" class="badge"></a>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.3332716">MORLAB &ndash; Model Order
    Reduction LABoratory (version 5.0)</a>, August 2019. see also:
    <a target="blank_" href="https://www.mpi-magdeburg.mpg.de/projects/morlab">
    https://www.mpi-magdeburg.mpg.de/projects/morlab</a>.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.3332716">10.5281/zenodo.3332716</a><br />
    <button id="BenW19b-pop" class="btn btn--inverse">BibTeX</button>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/badge/License-AGPLv3+-blue.svg"
    alt="License: AGPLv3+" class="badge"></a>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.2553926">Limited balanced truncation
    for large-scale sparse second-order systems (version 1.0)</a>, February 2019.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.2553926">10.5281/zenodo.2553926</a><br />
    <button id="BenW19a-pop" class="btn btn--inverse">BibTeX</button>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/gpl-3.0">
    <img src="https://img.shields.io/badge/License-GPLv3+-blue.svg"
    alt="License: GPLv3+" class="badge"></a>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.2553902">SOMDDPA &ndash; Second-Order
    Modally Damped Dominant Pole Algorithm (version 1.0)</a>, February 2019.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.2553902">10.5281/zenodo.2553902</a><br />
    <button id="BenW19-pop" class="btn btn--inverse">BibTeX</button>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/gpl-3.0">
    <img src="https://img.shields.io/badge/License-GPLv3+-blue.svg"
    alt="License: GPLv3+" class="badge"></a>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.1574083">MORLAB – Model Order Reduction
    LABoratory (version 4.0)</a>, December 2018. see also:
    <a target="blank_" href="https://www.mpi-magdeburg.mpg.de/projects/morlab">
    https://www.mpi-magdeburg.mpg.de/projects/morlab</a>.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.1574083">10.5281/zenodo.1574083</a><br />
    <button id="BenW18b-pop" class="btn btn--inverse">BibTeX</button>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/badge/License-AGPLv3+-blue.svg"
    alt="License: AGPLv3+" class="badge"></a>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.842659">MORLAB-3.0 &ndash; model order
    reduction laboratory</a>, September 2017. see also:
    <a target="blank_" href="https://www.mpi-magdeburg.mpg.de/projects/morlab">
    https://www.mpi-magdeburg.mpg.de/projects/morlab</a>.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.842659">10.5281/zenodo.842659</a><br />
    <button id="BenW17a-pop" class="btn btn--inverse">BibTeX</button>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/badge/License-AGPLv3+-blue.svg"
    alt="License: AGPLv3+" class="badge"></a>

---

## <a name="theses"></a>Theses ##
1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.25673/38617">Structure-Preserving Model Reduction
    for Mechanical Systems</a>. Dissertation, Otto-von-Guericke-Universität,
    Magdeburg, Germany, 2021.
    doi:<a target="blank_" href="https://doi.org/10.25673/38617">10.25673/38617</a><br /> 
    <button id="Wer21-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.4650402">
    <button class="btn btn--inverse">Code & Data</button></a>
    <a target="blank_" href="https://doi.org/10.5281/zenodo.4650422">
    <button class="btn btn--inverse">Results</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>

1.  <strong>S. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.25673/4507">Hankel-norm approximation of descriptor
    systems</a>. Master's thesis, Otto-von-Guericke-Universität,
    Magdeburg, Germany, 2016. doi:<a target="blank_" href="https://doi.org/10.25673/4507">10.25673/4507</a><br /> 
    <button id="Wer16-pop" class="btn btn--inverse">BibTeX</button>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    
1.  <strong>S. Werner</strong>. Numerische Berechnung der Eigenwerte großer
    Hamiltonisch-positiver Matrizen. Bachelor's thesis,
    Otto-von-Guericke-Universität, Magdeburg, Germany, 2014.  
    <button id="Wer14-pop" class="btn btn--inverse">BibTeX</button>


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
