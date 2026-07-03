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
  --home-ink: #172033;
  --home-muted: #5c667a;
  --home-soft: #eef3f8;
  --home-line: #d9e2ec;
  --home-blue: #2456a6;
  --home-teal: #20766f;
  --home-gold: #b7791f;
  --home-paper: #ffffff;
}

body {
  background:
    linear-gradient(180deg, #fbfcff 0%, #f6f8fb 44%, #ffffff 100%);
}

#main {
  margin-top: 1.4em;
}

.sidebar {
  color: var(--home-muted);
}

@media (min-width: 925px) {
  .sidebar.sticky {
    padding: 1rem 0.95rem;
    border: 1px solid rgba(217, 226, 236, 0.86);
    border-radius: 8px;
    background: rgba(255, 255, 255, 0.82);
    box-shadow: 0 10px 28px rgba(23, 32, 51, 0.045);
  }
}

.author__avatar img {
  border: 1px solid rgba(36, 86, 166, 0.14);
  box-shadow: 0 10px 24px rgba(23, 32, 51, 0.08);
}

.author__name {
  color: var(--home-ink);
}

.author__bio {
  color: var(--home-muted);
}

.masthead {
  border-bottom: 1px solid rgba(36, 86, 166, 0.12);
  box-shadow: 0 8px 30px rgba(23, 32, 51, 0.04);
}

.greedy-nav {
  background: rgba(255, 255, 255, 0.96);
}

.page__content {
  color: var(--home-ink);
}

.about-section {
  font-size: 1rem;
  line-height: 1.78;
  color: var(--home-ink);
  max-width: 860px;
  margin: 0 auto;
}

.about-section [id] { scroll-margin-top: 1rem; }
.about-section p { margin-bottom: 0.9rem; }
.about-section strong { color: #111827; font-weight: 650; }
.about-section em { color: #1f2937; font-style: italic; }
.about-section a {
  color: var(--home-blue);
  text-decoration: none;
  border-bottom: 1px solid rgba(36, 86, 166, 0.24);
  transition: border-color 0.16s ease, color 0.16s ease, background-color 0.16s ease;
}
.about-section a:hover {
  color: #163f7f;
  border-bottom-color: var(--home-blue);
  background-color: rgba(36, 86, 166, 0.05);
}

.page__title {
  font-size: 2.45rem;
  font-weight: 750;
  color: var(--home-ink);
  letter-spacing: 0;
  margin: 0.25rem 0 0.75rem;
  line-height: 1.15;
}

.page__title::after {
  content: "";
  display: block;
  width: 3.2rem;
  height: 3px;
  margin-top: 0.75rem;
  background: linear-gradient(90deg, var(--home-teal), var(--home-blue));
  border-radius: 999px;
}

.about-section h2 {
  display: flex;
  align-items: center;
  gap: 0.7rem;
  font-size: 1.16rem;
  font-weight: 750;
  color: #173d73;
  letter-spacing: 0;
  margin: 2.35rem 0 1rem;
  padding-bottom: 0.55rem;
  border-bottom: 1px solid var(--home-line);
  position: relative;
}
.about-section h2::before {
  content: "";
  width: 0.6rem;
  height: 0.6rem;
  border-radius: 999px;
  background: var(--home-teal);
  box-shadow: 0 0 0 4px rgba(32, 118, 111, 0.12);
}
.about-section h3 {
  font-size: 0.75rem;
  font-weight: 750;
  color: #53627a;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  margin: 1.55rem 0 0.75rem;
}
.about-section h3:first-of-type { margin-top: 0.9rem; }

.intro-lead {
  font-size: 1.04rem;
  line-height: 1.82;
  color: #233044;
  margin: 0.75rem 0 1.55rem;
  padding: 1.05rem 1.25rem 1.08rem;
  border-left: 4px solid var(--home-teal);
  border-radius: 0 8px 8px 0;
  background:
    linear-gradient(90deg, rgba(32, 118, 111, 0.08), rgba(183, 121, 31, 0.05));
}

.news-list {
  display: grid;
  gap: 0.65rem;
  list-style: none;
  padding-left: 0;
  margin: 0;
  font-size: 0.95rem;
  line-height: 1.58;
}
.news-list li {
  display: grid;
  grid-template-columns: 6rem 1fr;
  gap: 1rem;
  align-items: start;
  padding: 0.85rem 1rem;
  border: 1px solid rgba(217, 226, 236, 0.9);
  border-radius: 8px;
  background: var(--home-paper);
  color: #334155;
  box-shadow: 0 8px 22px rgba(23, 32, 51, 0.045);
}
.news-list li:first-child {
  border-color: rgba(32, 118, 111, 0.28);
  background:
    linear-gradient(90deg, rgba(32, 118, 111, 0.09), rgba(255, 255, 255, 0.96) 42%);
}
.news-list li > strong:first-child {
  color: var(--home-teal);
  font-weight: 750;
  font-size: 0.78rem;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  padding-top: 0.1rem;
}

.exp-entry {
  margin-bottom: 0.85rem;
  padding: 0.95rem 1.05rem;
  border: 1px solid rgba(217, 226, 236, 0.88);
  border-radius: 8px;
  background: rgba(255, 255, 255, 0.86);
  box-shadow: 0 10px 24px rgba(23, 32, 51, 0.035);
}
.exp-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  flex-wrap: wrap;
  gap: 0.65rem;
  margin-bottom: 0.15rem;
}
.exp-title {
  font-weight: 700;
  font-size: 1rem;
  color: var(--home-ink);
  letter-spacing: 0;
}
.exp-date {
  color: var(--home-muted);
  font-size: 0.74rem;
  font-weight: 700;
  font-variant-numeric: tabular-nums;
  white-space: nowrap;
  letter-spacing: 0.075em;
  text-transform: uppercase;
}
.exp-sub {
  color: #47566d;
  font-size: 0.92rem;
  margin: 0.05rem 0 0.25rem;
  line-height: 1.5;
}
.exp-desc {
  color: #69758a;
  font-size: 0.89rem;
  margin: 0;
  line-height: 1.6;
}

.pub-grid { margin: 0.25rem 0 0.4rem; }
.pub-entry {
  display: grid;
  grid-template-columns: 6.2rem 1fr;
  column-gap: 1rem;
  margin-bottom: 0;
  padding: 0.78rem 0;
  border-bottom: 1px solid rgba(217, 226, 236, 0.72);
  line-height: 1.58;
  font-size: 0.93rem;
  color: #33445c;
}
.pub-entry:first-child { padding-top: 0.3rem; }
.pub-entry:last-child { border-bottom: none; }
.pub-entry:hover .pub-tag {
  border-color: rgba(36, 86, 166, 0.26);
  background: #dde8f6;
}
.pub-tag {
  font-weight: 750;
  color: #173d73;
  background: #e8eef8;
  border: 1px solid rgba(36, 86, 166, 0.12);
  border-radius: 3px;
  padding: 0.2rem 0.35rem;
  font-size: 0.7rem;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  text-align: center;
  height: fit-content;
  margin-top: 0.2rem;
  transition: background-color 0.16s ease, border-color 0.16s ease;
}
.pub-content { min-width: 0; }
.pub-title { font-style: italic; color: var(--home-ink); }
.pub-content strong { color: #173d73; font-weight: 650; }
.pub-badge {
  display: inline-block;
  background: rgba(32, 118, 111, 0.12);
  color: #17645e;
  border: 1px solid rgba(32, 118, 111, 0.16);
  border-radius: 3px;
  padding: 0.05rem 0.42rem;
  font-size: 0.7rem;
  font-weight: 750;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  margin-left: 0.4rem;
  vertical-align: 1px;
}
.pub-links { font-size: 0.85rem; margin-left: 0.25rem; color: #8a96a8; }
.pub-links a { color: #66758d; border-bottom: none; }
.pub-links a:hover { color: var(--home-blue); }

.scholar-note {
  font-size: 0.91rem;
  color: var(--home-muted);
  margin: 0.15rem 0 0.15rem;
}

@media (max-width: 600px) {
  #main { margin-top: 1em; }
  .page__title { font-size: 2.05rem; }
  .intro-lead { padding: 0.9rem 1rem; }
  .pub-entry { grid-template-columns: 1fr; row-gap: 0.32rem; }
  .pub-tag { justify-self: start; padding: 0.18rem 0.5rem; }
  .news-list li { grid-template-columns: 1fr; gap: 0.12rem; }
  .news-list li > strong:first-child { padding-top: 0; }
  .exp-entry { padding: 0.85rem 0.9rem; }
}
</style>

<div class="about-section">

<p class="intro-lead">I am a Research Associate at the <a href="https://www.manchester.ac.uk/">University of Manchester</a>, working with <a href="https://chenjiaoyan.github.io/">Dr. Jiaoyan Chen</a> on the <a href="https://research.manchester.ac.uk/en/projects/ontoem-semantic-embedding-for-ontologies/">OntoEm</a> project (Semantic Embedding for Ontologies). My research focuses on <strong>ontology reasoning, modularization, and embedding</strong>, combining symbolic and neural approaches to knowledge representation.</p>

<h2 id="news">Recent News</h2>

<ul class="news-list">
  <li><strong>Jul 2026</strong> <span>An <strong>ISWC 2026</strong> tutorial has been accepted. [<a href="https://huiyang1997.github.io/OntoLM/">Tutorial webpage</a>]</span></li>
  <li><strong>Apr 2026</strong> <span>A paper accepted at <strong>KR 2026</strong> (ML Track). [<a href="https://arxiv.org/abs/2501.17518">arXiv</a>]</span></li>
  <li><strong>Jan 2026</strong> <span>A paper published at <strong>WWW 2026</strong>. [<a href="https://arxiv.org/abs/2601.12444">arXiv</a>]</span></li>
</ul>

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

</div>
