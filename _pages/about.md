---
permalink: /
title: "Hui Yang"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
:root {
  --ink: #1b1d20;
  --body-ink: #2b2e33;
  --muted: #565c66;
  --soft: #8a9099;
  --line: #e4e7ea;
  --rule: #d2d5d9;
  --accent: #1f3a5f;
  --accent-dark: #152a46;
  --paper: #ffffff;
  --serif: 'Source Serif 4', Georgia, 'Times New Roman', serif;
  --sans: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
}

body {
  background: var(--paper);
}

#main {
  margin-top: 1.1em;
}

/* ---------- masthead ---------- */
.masthead {
  border-bottom: 1px solid var(--line);
  box-shadow: none;
}
.masthead__inner-wrap {
  padding: 0.85em 1em;
}
.greedy-nav {
  background: transparent;
}
.masthead__menu-item--lg a {
  font-family: var(--serif);
  font-size: 1.06rem;
  font-weight: 700;
  color: var(--ink);
  letter-spacing: 0.01em;
}
.greedy-nav .masthead__menu-item:not(.masthead__menu-item--lg) a {
  font-size: 0.82rem;
  color: #4a505a;
  letter-spacing: 0.02em;
  transition: color 0.15s ease;
}
.greedy-nav .masthead__menu-item:not(.masthead__menu-item--lg) a:hover {
  color: var(--accent);
  text-decoration: underline;
  text-underline-offset: 5px;
}

/* ---------- author sidebar ---------- */
.sidebar {
  color: var(--muted);
}

@media (min-width: 925px) {
  .sidebar.sticky {
    padding-top: 0.25rem;
  }
}

.author__avatar img {
  width: 150px;
  max-width: 150px;
  padding: 0;
  border: 1px solid var(--line);
  border-radius: 3px;
  box-shadow: none;
}

.sidebar .author__name {
  font-family: var(--serif);
  font-size: 1.18rem;
  font-weight: 700;
  color: var(--ink);
  letter-spacing: 0.005em;
}

.author__bio {
  color: var(--muted);
  font-size: 0.85rem;
  line-height: 1.6;
}

.author__urls li,
.author__urls a {
  font-size: 0.82rem;
  line-height: 1.55;
  color: var(--muted);
}
.author__urls li i {
  color: var(--soft);
}
.author__urls a {
  transition: color 0.15s ease;
}
.author__urls a:hover {
  color: var(--accent);
  text-decoration: underline;
  text-underline-offset: 3px;
}

@media (min-width: 64em) {
  .author__urls {
    margin-top: 1.1rem;
    padding-top: 1rem;
    border-top: 1px solid var(--line);
  }
  .author__urls li {
    margin-bottom: 0.1rem;
  }
}

/* ---------- page title & content ---------- */
.page__content {
  color: var(--body-ink);
}

.page__title {
  font-family: var(--serif);
  font-size: 2rem;
  font-weight: 700;
  color: var(--ink);
  letter-spacing: -0.005em;
  line-height: 1.15;
  margin: 0.2rem 0 1.6rem;
  padding-bottom: 0.8rem;
  border-bottom: 2px solid var(--ink);
}

.page__title::after {
  display: none;
}

.about-section {
  font-family: var(--serif);
  font-size: 0.97rem;
  line-height: 1.78;
  color: var(--body-ink);
  max-width: 740px;
}

.about-section [id] { scroll-margin-top: 0.85rem; }
.about-section p { margin-bottom: 0.9rem; }
.about-section strong { color: var(--ink); font-weight: 600; }
.about-section em { color: inherit; font-style: italic; }
.about-section a {
  color: var(--accent);
  text-decoration: underline;
  text-decoration-color: rgba(31, 58, 95, 0.3);
  text-decoration-thickness: 1px;
  text-underline-offset: 2.5px;
  transition: color 0.15s ease, text-decoration-color 0.15s ease;
}
.about-section a:hover {
  color: var(--accent-dark);
  text-decoration-color: currentColor;
}

/* ---------- sections: paper rules, no cards ---------- */
.content-block {
  background: transparent;
  border: none;
  border-radius: 0;
  box-shadow: none;
  margin: 2.5rem 0 0;
  padding: 0;
}
.content-block:first-of-type {
  margin-top: 2.1rem;
}

.about-section h2 {
  font-family: var(--serif);
  font-size: 1.28rem;
  font-weight: 700;
  color: var(--ink);
  letter-spacing: 0;
  margin: 0 0 1rem;
  padding-bottom: 0.5rem;
  border-bottom: 1px solid var(--rule);
}
.about-section h3 {
  font-family: var(--sans);
  font-size: 0.68rem;
  font-weight: 700;
  color: var(--soft);
  letter-spacing: 0.1em;
  text-transform: uppercase;
  margin: 1.6rem 0 0.55rem;
}
.about-section h3:first-of-type { margin-top: 0.65rem; }

.intro-lead {
  font-family: var(--serif);
  font-size: 1.04rem;
  line-height: 1.82;
  color: #31353c;
  margin: 0.2rem 0 1.35rem;
  padding: 0;
  border-left: none;
}

/* ---------- news ---------- */
.news-list {
  display: grid;
  gap: 0;
  list-style: none;
  padding-left: 0;
  margin: 0.2rem 0 0;
  font-family: var(--serif);
  font-size: 0.93rem;
  line-height: 1.62;
  border-top: none;
}
.news-list li {
  display: grid;
  grid-template-columns: 5.4rem 1fr;
  gap: 1rem;
  align-items: baseline;
  padding: 0.55rem 0;
  border-bottom: none;
  color: #34383f;
}
.news-list li + li {
  border-top: 1px solid var(--line);
}
.news-list li:first-child {
  padding-left: 0;
  border-left: none;
  background: transparent;
}
.news-list li > strong:first-child {
  font-family: var(--sans);
  color: var(--soft);
  font-weight: 700;
  font-size: 0.7rem;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  padding-top: 0.12rem;
}

/* ---------- experience / education ---------- */
.exp-entry {
  margin-bottom: 0;
  padding: 0.78rem 0;
  border-bottom: none;
}
.exp-entry + .exp-entry {
  border-top: 1px solid var(--line);
}
.exp-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  flex-wrap: wrap;
  gap: 0.9rem;
  margin-bottom: 0.18rem;
}
.exp-title {
  font-family: var(--serif);
  font-weight: 600;
  font-size: 1.02rem;
  color: var(--ink);
  letter-spacing: 0;
}
.exp-date {
  font-family: var(--sans);
  color: var(--soft);
  font-size: 0.68rem;
  font-weight: 700;
  font-variant-numeric: tabular-nums;
  white-space: nowrap;
  letter-spacing: 0.06em;
  text-transform: uppercase;
}
.exp-sub {
  color: #484d55;
  font-size: 0.9rem;
  margin: 0.05rem 0 0.2rem;
  line-height: 1.55;
}
.exp-desc {
  color: #63696f;
  font-size: 0.9rem;
  margin: 0;
  line-height: 1.62;
}

/* ---------- publications ---------- */
.pub-grid {
  display: grid;
  gap: 0;
  margin: 0.35rem 0 0.6rem;
}
.pub-entry {
  display: grid;
  grid-template-columns: 6rem 1fr;
  column-gap: 1.2rem;
  margin-bottom: 0;
  padding: 0.62rem 0;
  border-bottom: none;
  line-height: 1.68;
  font-size: 0.93rem;
  color: #34383f;
}
.pub-entry:first-child { padding-top: 0.3rem; }
.pub-entry + .pub-entry {
  border-top: 1px solid var(--line);
}
.pub-tag {
  font-family: var(--sans);
  font-weight: 700;
  color: #5d626b;
  background: transparent;
  border: none;
  border-radius: 0;
  padding: 0;
  font-size: 0.66rem;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  text-align: left;
  height: fit-content;
  margin-top: 0.34em;
}
.pub-content { min-width: 0; }
.pub-title {
  font-family: var(--serif);
  color: var(--ink);
  font-style: normal;
  font-weight: 600;
}
.pub-title a {
  color: var(--ink);
  border-bottom: none;
}
.pub-title a:hover {
  color: var(--accent);
  text-decoration: underline;
}
.pub-content strong { color: var(--ink); font-weight: 600; }
.pub-content em { color: #3c4046; }
.pub-badge {
  font-family: var(--sans);
  display: inline-block;
  background: transparent;
  color: #2e6b46;
  border: 1px solid #cfe3d6;
  border-radius: 2px;
  padding: 0.12em 0.5em;
  font-size: 0.6rem;
  font-weight: 700;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  margin-left: 0.4em;
  vertical-align: 0.18em;
}
.pub-links {
  font-family: var(--sans);
  font-size: 0.76rem;
  margin-left: 0.25rem;
  color: var(--soft);
}
.pub-links a { color: var(--muted); border-bottom: none; }
.pub-links a:hover { color: var(--accent); text-decoration: none; }

.scholar-note {
  font-family: var(--sans);
  font-size: 0.82rem;
  color: var(--muted);
  margin: 0.1rem 0 0.1rem;
}

/* ---------- responsive ---------- */
@media (max-width: 600px) {
  #main { margin-top: 1em; }
  .about-section { font-size: 0.95rem; max-width: 100%; }
  .page__title { font-size: 1.62rem; }
  .intro-lead { padding-left: 0; }
  .content-block { margin-top: 2rem; }
  .news-list li { grid-template-columns: 1fr; gap: 0.15rem; }
  .news-list li > strong:first-child { padding-top: 0; }
  .pub-entry { grid-template-columns: 1fr; row-gap: 0.2rem; }
  .pub-tag { justify-self: start; margin-top: 0; }
  .exp-entry { padding: 0.72rem 0; }
}
</style>

<div class="about-section">

<p class="intro-lead">I am a Research Associate at the <a href="https://www.manchester.ac.uk/">University of Manchester</a>, working with <a href="https://chenjiaoyan.github.io/">Dr. Jiaoyan Chen</a> on the <a href="https://research.manchester.ac.uk/en/projects/ontoem-semantic-embedding-for-ontologies/">OntoEm</a> project (Semantic Embedding for Ontologies). My research focuses on <strong>ontology reasoning, modularization, and embedding</strong>, combining symbolic and neural approaches to knowledge representation.</p>

<section class="content-block">
<h2 id="news">Recent News</h2>

<ul class="news-list">
  <li><strong>Jul 2026</strong> <span>An <strong>ISWC 2026</strong> tutorial has been accepted. [<a href="https://huiyang1997.github.io/OntoLM/">Tutorial webpage</a>]</span></li>
  <li><strong>Apr 2026</strong> <span>A paper accepted at <strong>KR 2026</strong> (ML Track). [<a href="https://arxiv.org/abs/2501.17518">arXiv</a>]</span></li>
  <li><strong>Jan 2026</strong> <span>A paper published at <strong>WWW 2026</strong>. [<a href="https://arxiv.org/abs/2601.12444">arXiv</a>]</span></li>
</ul>
</section>

<section class="content-block">
<h2 id="experience">Research Experience</h2>

<div class="exp-entry">
  <div class="exp-header">
    <span class="exp-title">University of Manchester</span>
    <span class="exp-date">Jun 2024 – Present</span>
  </div>
  <div class="exp-sub">Research Associate · supervised by Dr. Jiaoyan Chen · Manchester, UK</div>
  <div class="exp-desc">Neural-symbolic Knowledge Representation; supported by EPSRC project <em>OntoEm: Semantic Embedding for Ontologies</em>.</div>
</div>

<div class="exp-entry">
  <div class="exp-header">
    <span class="exp-title">IRT SystemX &amp; LISN, Université Paris-Saclay</span>
    <span class="exp-date">Apr 2023 – Mar 2024</span>
  </div>
  <div class="exp-sub">Postdoctoral Researcher · supervised by Prof. Nacéra Seghouani, Dr. Yue Ma, Dr. Mostepha Khouadjia · Gif-sur-Yvette, France</div>
  <div class="exp-desc">Neural network models for detection and semantic interpretation of abnormal events in videos; supported by the SMD project.</div>
</div>

<div class="exp-entry">
  <div class="exp-header">
    <span class="exp-title">LISN, Université Paris-Saclay</span>
    <span class="exp-date">Feb 2020 – May 2023</span>
  </div>
  <div class="exp-sub">Ph.D. Student · supervised by Prof. Nicole Bidoit and Dr. Yue Ma · Gif-sur-Yvette, France</div>
  <div class="exp-desc">Thesis: <em>Knowledge Extraction from Large Ontologies</em>. Supported by the AIDA project (BPI-France).</div>
</div>

<div class="exp-entry">
  <div class="exp-header">
    <span class="exp-title">CPEC, TU Dresden</span>
    <span class="exp-date">Jul 2022</span>
  </div>
  <div class="exp-sub">Visiting Student · supervised by Dr. Patrick Koopmann · Dresden, Germany</div>
  <div class="exp-desc">Ontology modularization via uniform interpolation for expressive ontologies.</div>
</div>
</section>

<section class="content-block">
<h2 id="education">Education</h2>

<div class="exp-entry">
  <div class="exp-header">
    <span class="exp-title">Université Paris-Saclay</span>
    <span class="exp-date">2020 – 2023</span>
  </div>
  <div class="exp-sub">Ph.D., Computer Science</div>
</div>
<div class="exp-entry">
  <div class="exp-header">
    <span class="exp-title">IMPA (Instituto de Matemática Pura e Aplicada)</span>
    <span class="exp-date">2017 – 2019</span>
  </div>
  <div class="exp-sub">Master of Mathematics · Rio de Janeiro, Brazil</div>
</div>
<div class="exp-entry">
  <div class="exp-header">
    <span class="exp-title">Nankai University</span>
    <span class="exp-date">2013 – 2017</span>
  </div>
  <div class="exp-sub">Bachelor of Mathematics · Tianjin, China</div>
</div>
</section>

<section class="content-block">
<h2 id="publications">Publications</h2>

<p class="scholar-note">A complete list is also available on <a href="https://scholar.google.com/citations?user=HqVFCscAAAAJ&hl=en">Google Scholar</a>.</p>

<h3>Accepted / In Press</h3>

<div class="pub-grid">

<div class="pub-entry">
  <span class="pub-tag">KR 2026</span>
  <span class="pub-content"><span class="pub-title">RegD: Hierarchical Embeddings via Dissimilarity between Arbitrary Euclidean Regions.</span> <strong>Hui Yang</strong>, Jiaoyan Chen. <em>KR 2026 (ML Track)</em>.<span class="pub-badge">Accepted</span> <span class="pub-links">[<a href="https://arxiv.org/abs/2501.17518">arXiv</a>]</span></span>
</div>

</div>

<h3>Conference Papers</h3>

<div class="pub-grid">

<div class="pub-entry">
  <span class="pub-tag">WWW 2026</span>
  <span class="pub-content"><span class="pub-title">Large Language Model for OWL Proofs.</span> <strong>Hui Yang</strong>, Jiaoyan Chen, Uli Sattler. In <em>Proceedings of the ACM Web Conference 2026</em>. <span class="pub-links">[<a href="https://arxiv.org/abs/2601.12444">arXiv</a>]</span></span>
</div>

<div class="pub-entry">
  <span class="pub-tag">ISWC 2025</span>
  <span class="pub-content"><span class="pub-title"><a href="https://doi.org/10.1007/978-3-032-09527-5_24">Language Models as Ontology Encoders.</a></span> <strong>Hui Yang</strong>, Jiaoyan Chen, Yuan He, Yongsheng Gao, Ian Horrocks. In <em>International Semantic Web Conference</em>, pp. 443–461. <span class="pub-links">[<a href="https://arxiv.org/abs/2507.14334">arXiv</a>]</span></span>
</div>

<div class="pub-entry">
  <span class="pub-tag">WWW 2025</span>
  <span class="pub-content"><span class="pub-title"><a href="https://doi.org/10.1145/3696410.3714672">TransBox: EL<sup>++</sup>-closed Ontology Embedding.</a></span> <strong>Hui Yang</strong>, Jiaoyan Chen, Uli Sattler. In <em>Proceedings of the ACM on Web Conference 2025</em>, pp. 22–34. <span class="pub-links">[<a href="https://arxiv.org/abs/2410.14571">arXiv</a>]</span></span>
</div>

<div class="pub-entry">
  <span class="pub-tag">PAKDD 2024</span>
  <span class="pub-content"><span class="pub-title"><a href="https://doi.org/10.1007/978-981-97-2253-2_31">Alleviating Over-Smoothing via Aggregation over Compact Manifolds.</a></span> Dongzhuoran Zhou, <strong>Hui Yang</strong>, Bo Xiong, Yue Ma, Evgeny Kharlamov. In <em>Pacific-Asia Conference on Knowledge Discovery and Data Mining</em>, pp. 390–404. <span class="pub-links">[<a href="https://arxiv.org/abs/2407.19231">arXiv</a>]</span></span>
</div>

<div class="pub-entry">
  <span class="pub-tag">ESWC 2024</span>
  <span class="pub-content"><span class="pub-title"><a href="https://doi.org/10.1007/978-3-031-60626-7_6">Low-Dimensional Hyperbolic Knowledge Graph Embedding for Better Extrapolation to Under-Represented Data.</a></span> Zhuoxun Zheng, Baifan Zhou, <strong>Hui Yang</strong>, Zhipeng Tan, Arild Waaler, Evgeny Kharlamov, Ahmet Soylu. In <em>European Semantic Web Conference</em>, pp. 100–120.</span>
</div>

<div class="pub-entry">
  <span class="pub-tag">IJCAI 2023</span>
  <span class="pub-content"><span class="pub-title"><a href="https://doi.org/10.24963/ijcai.2023/374">Efficient Computation of General Modules for ALC Ontologies.</a></span> <strong>Hui Yang</strong>, Patrick Koopmann, Yue Ma, Nicole Bidoit. In <em>International Joint Conference on Artificial Intelligence</em>, pp. 3356–3364.</span>
</div>

<div class="pub-entry">
  <span class="pub-tag">AAAI 2023</span>
  <span class="pub-content"><span class="pub-title"><a href="https://doi.org/10.1609/aaai.v37i5.25808">Efficient Extraction of EL-Ontology Deductive Modules.</a></span> <strong>Hui Yang</strong>, Yue Ma, Nicole Bidoit. In <em>AAAI Conference on Artificial Intelligence</em>, pp. 6575–6582.</span>
</div>

<div class="pub-entry">
  <span class="pub-tag">IJCAR 2022</span>
  <span class="pub-content"><span class="pub-title"><a href="https://doi.org/10.1007/978-3-031-10769-6_19">Hypergraph-Based Inference Rules for Computing EL<sup>+</sup>-Ontology Justifications.</a></span> <strong>Hui Yang</strong>, Yue Ma, Nicole Bidoit. In <em>International Joint Conference on Automated Reasoning</em>, pp. 310–328.</span>
</div>

<div class="pub-entry">
  <span class="pub-tag">ESWC 2022</span>
  <span class="pub-content"><span class="pub-title"><a href="https://doi.org/10.1007/978-3-031-06981-9_4">Union and Intersection of All Justifications.</a></span> Jieying Chen, Yue Ma, Rafael Peñaloza, <strong>Hui Yang</strong>. In <em>European Semantic Web Conference</em>, pp. 56–73.</span>
</div>

</div>

<h3>Journal Articles</h3>

<div class="pub-grid">

<div class="pub-entry">
  <span class="pub-tag">JDSA 2025</span>
  <span class="pub-content"><span class="pub-title"><a href="https://doi.org/10.1007/s41060-025-00875-z">Alleviating Over-Smoothing via Aggregation over Compact Manifolds (Extended Version).</a></span> Dongzhuoran Zhou, <strong>Hui Yang</strong>, Bo Xiong, Yue Ma, Evgeny Kharlamov. <em>International Journal of Data Science and Analytics</em>, 20(8): 7055–7069.</span>
</div>

<div class="pub-entry">
  <span class="pub-tag">DMKD 2024</span>
  <span class="pub-content"><span class="pub-title"><a href="https://doi.org/10.1007/s10618-024-01050-x">Knowledge Graph Embedding Closed under Composition.</a></span> Zhuoxun Zheng, Baifan Zhou, <strong>Hui Yang</strong>, Zhipeng Tan, Zequn Sun, Chunnong Li, Arild Waaler, Evgeny Kharlamov, Ahmet Soylu. <em>Data Mining and Knowledge Discovery</em>, 38(6).</span>
</div>

<div class="pub-entry">
  <span class="pub-tag">IMRN 2021</span>
  <span class="pub-content"><span class="pub-title"><a href="https://doi.org/10.1093/imrn/rnz231">A Question of Norton-Sullivan in the Analytic Case.</a></span> Jian Wang, <strong>Hui Yang</strong>. <em>International Mathematics Research Notices</em>, 2021(21): 17201–17219.</span>
</div>

</div>
</section>

</div>
