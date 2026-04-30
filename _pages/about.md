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
.about-section {
  font-size: 1rem;
  line-height: 1.7;
  color: #1f2937;
  max-width: 760px;
}
.about-section [id] { scroll-margin-top: 0.5rem; }
.about-section p { margin-bottom: 0.8rem; }
.about-section strong { color: #0f172a; font-weight: 600; }
.about-section em { color: #111827; font-style: italic; }
.about-section a {
  color: #1d4ed8;
  text-decoration: none;
  border-bottom: 1px solid rgba(29, 78, 216, 0.22);
  transition: border-color 0.15s ease, color 0.15s ease;
}
.about-section a:hover {
  color: #1e3a8a;
  border-bottom-color: #1d4ed8;
}

.page__title {
  font-size: 2.3rem;
  font-weight: 700;
  color: #0f172a;
  letter-spacing: -0.025em;
  margin: 0.2rem 0 0.3rem;
  line-height: 1.15;
}

.about-section h2 {
  font-size: 1.18rem;
  font-weight: 700;
  color: #0f3a8c;
  letter-spacing: -0.005em;
  margin: 1.9rem 0 0.95rem;
  padding-bottom: 0.45rem;
  border-bottom: 1px solid #e3e6ed;
  position: relative;
}
.about-section h2::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: -1px;
  width: 48px;
  height: 2px;
  background: #1d4ed8;
}
.about-section h3 {
  font-size: 0.74rem;
  font-weight: 700;
  color: #475569;
  letter-spacing: 0.13em;
  text-transform: uppercase;
  margin: 1.4rem 0 0.7rem;
}
.about-section h3:first-of-type { margin-top: 0.9rem; }

.intro-lead {
  font-size: 1.03rem;
  line-height: 1.75;
  color: #1f2937;
  margin: 0.5rem 0 0.4rem;
  padding-left: 0;
  border-left: none;
}

.news-list {
  list-style: none;
  padding-left: 0;
  margin: 0;
  font-size: 0.94rem;
  line-height: 1.6;
}
.news-list li {
  display: flex;
  gap: 0.9rem;
  padding: 0.5rem 0;
  border-bottom: 1px solid #eef0f4;
  color: #374151;
}
.news-list li:first-child { padding-top: 0.2rem; }
.news-list li:last-child { border-bottom: none; padding-bottom: 0.1rem; }
.news-list li > strong:first-child {
  flex-shrink: 0;
  width: 5.4rem;
  color: #0f3a8c;
  font-weight: 600;
  font-size: 0.78rem;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  padding-top: 0.18rem;
}

.exp-entry {
  margin-bottom: 1.15rem;
  padding-left: 0;
  border-left: none;
}
.exp-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  flex-wrap: wrap;
  gap: 0.6rem;
  margin-bottom: 0.15rem;
}
.exp-title {
  font-weight: 600;
  font-size: 1rem;
  color: #0f172a;
  letter-spacing: -0.005em;
}
.exp-date {
  background: transparent;
  color: #64748b;
  font-size: 0.74rem;
  font-weight: 600;
  font-variant-numeric: tabular-nums;
  white-space: nowrap;
  padding: 0;
  border-radius: 0;
  letter-spacing: 0.075em;
  text-transform: uppercase;
}
.exp-sub {
  color: #475569;
  font-size: 0.92rem;
  margin: 0.05rem 0 0.25rem;
  line-height: 1.5;
}
.exp-desc {
  color: #64748b;
  font-size: 0.89rem;
  margin: 0;
  line-height: 1.55;
}

.pub-grid { margin: 0.2rem 0 0.3rem; }
.pub-entry {
  display: grid;
  grid-template-columns: 5.6rem 1fr;
  column-gap: 0.95rem;
  margin-bottom: 0.78rem;
  line-height: 1.55;
  font-size: 0.93rem;
  color: #334155;
}
.pub-tag {
  font-weight: 700;
  color: #0f3a8c;
  background: #e7edfa;
  border-radius: 3px;
  padding: 0.18rem 0;
  font-size: 0.7rem;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  text-align: center;
  height: fit-content;
  margin-top: 0.2rem;
}
.pub-grid > .pub-entry:last-child { margin-bottom: 0; }
.pub-content { min-width: 0; }
.pub-title { font-style: italic; color: #0f172a; }
.pub-content strong { color: #1e3a8a; font-weight: 600; }
.pub-badge {
  display: inline-block;
  background: #dcfce7;
  color: #166534;
  border-radius: 3px;
  padding: 0.05rem 0.42rem;
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  margin-left: 0.4rem;
  vertical-align: 1px;
}
.pub-links { font-size: 0.85rem; margin-left: 0.25rem; color: #94a3b8; }
.pub-links a { color: #64748b; border-bottom: none; }
.pub-links a:hover { color: #1d4ed8; }

.scholar-note {
  font-size: 0.91rem;
  color: #64748b;
  margin: 0.2rem 0 0;
}

@media (max-width: 600px) {
  .page__title { font-size: 2rem; }
  .pub-entry { grid-template-columns: 1fr; row-gap: 0.3rem; }
  .pub-tag { justify-self: start; padding: 0.18rem 0.5rem; }
  .news-list li { flex-direction: column; gap: 0.15rem; }
  .news-list li > strong:first-child { padding-top: 0; }
}
</style>

<div class="about-section">

<p class="intro-lead">I am a Research Associate at the <a href="https://www.manchester.ac.uk/">University of Manchester</a>, working with <a href="https://chenjiaoyan.github.io/">Dr. Jiaoyan Chen</a> on the <a href="https://research.manchester.ac.uk/en/projects/ontoem-semantic-embedding-for-ontologies/">OntoEm</a> project (Semantic Embedding for Ontologies). My research focuses on <strong>ontology reasoning, modularization, and embedding</strong>, combining symbolic and neural approaches to knowledge representation.</p>

<h2 id="news">Recent News</h2>

<ul class="news-list">
  <li><strong>Apr 2026</strong> <span>A paper accepted at <strong>KR 2026</strong> (ML Track). [<a href="https://arxiv.org/abs/2501.17518">arXiv</a>]</span></li>
  <li><strong>Jan 2026</strong> <span>A paper accepted at <strong>WWW 2026</strong>. [<a href="https://arxiv.org/abs/2601.12444">arXiv</a>]</span></li>
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
  <span class="pub-tag">WWW 2026</span>
  <span class="pub-content"><span class="pub-title">Large Language Model for OWL Proofs.</span> <strong>Hui Yang</strong>, Jiaoyan Chen, Uli Sattler. <em>The Web Conference 2026</em>.<span class="pub-badge">Accepted</span> <span class="pub-links">[<a href="https://arxiv.org/abs/2601.12444">arXiv</a>]</span></span>
</div>

<div class="pub-entry">
  <span class="pub-tag">KR 2026</span>
  <span class="pub-content"><span class="pub-title">RegD: Hierarchical Embeddings via Dissimilarity between Arbitrary Euclidean Regions.</span> <strong>Hui Yang</strong>, Jiaoyan Chen. <em>KR 2026 (ML Track)</em>.<span class="pub-badge">Accepted</span> <span class="pub-links">[<a href="https://arxiv.org/abs/2501.17518">arXiv</a>]</span></span>
</div>

</div>

<h3>Conference Papers</h3>

<div class="pub-grid">

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
