---
title: Data Infrastructure for Political Elites
menu_title: Data
layout: page
permalink: data.html
menu: true
order: 2
description: Comparative political biographies, auditable AI-assisted data construction, and multimodal measures of elite behavior.
hide_description: true
---

<link rel="stylesheet" href="{{ '/assets/css/data-page-final.css' | relative_url }}">

<div class="elite-data-page" markdown="0">

<section class="ed-hero" aria-label="Research agenda">
<div class="ed-hero-copy">
<p class="ed-kicker">Research agenda</p>
<p class="ed-hero-lead">My research asks who governs, how political elites rise, and how institutions shape their behavior across political systems. I build comparative biographies, auditable AI-assisted data-production systems, and multimodal measures to answer these questions.</p>
<p class="ed-hero-note">Across these projects, the goal is the same: to make political elites observable across countries, over time, and in forms that conventional records miss.</p>
</div>
<div class="ed-hero-axis" aria-label="Three dimensions of the research agenda">
<a href="#breadth">
<span>01 · Breadth</span>
<strong>Comparative biographies</strong>
<small>Across countries and institutions</small>
</a>
<a href="#scale">
<span>02 · Scale</span>
<strong>Auditable data production</strong>
<small>From dispersed evidence to structured data</small>
</a>
<a href="#depth">
<span>03 · Depth</span>
<strong>Behavior beyond text</strong>
<small>Images, voice, and political video</small>
</a>
</div>
</section>

<nav class="ed-local-nav" aria-label="On this page">
<a href="#breadth">Comparative data</a>
<a href="#scale">Data construction</a>
<a href="#depth">Multimodal measurement</a>
<a href="#shared-access">Shared access</a>
</nav>

<section id="breadth" class="ed-section" aria-labelledby="breadth-title">
<header class="ed-section-head">
<div>
<p class="ed-kicker">01 · Breadth</p>
<h2 id="breadth-title">Comparative Political Elites Data</h2>
</div>
<p>My comparative data program traces how elites enter, move through, and exit political institutions. Current national and transnational modules cover the United States, OECD governments, international organizations, China, Russia, and ten Southeast Asian countries; harmonization to a common career and affiliation schema is ongoing.</p>
</header>

<div class="ed-theme-line" aria-label="Substantive research themes">
<span>Elite recruitment and mobility</span>
<span>Education, family, and political networks</span>
<span>Circulation across institutions</span>
</div>

<!--
RECOMMENDED IMAGE 1: a clean coverage map, placed here.
File: /assets/img/data/elite-coverage-map.png
Format: 16:9 or 2:1 landscape. Distinguish public modules, research-linked modules,
and modules under construction; represent international organizations with a separate icon.

<figure class="ed-wide-figure">
<img src="/assets/img/data/elite-coverage-map.png" alt="Geographic and institutional coverage of comparative political elites data modules" loading="lazy">
<figcaption>Current national and transnational modules. Harmonization across modules is ongoing.</figcaption>
</figure>
-->

<div class="ed-dataset-list" aria-label="Selected political elites data modules">

<article class="ed-dataset-row">
<div class="ed-dataset-copy">
<p class="ed-item-label"><span class="ed-status ed-status-public">Public platform</span> United States</p>
<h3>U.S. Congressional Legislators</h3>
<p>Supports research on legislative careers, political recruitment, representation, education, and political dynasties.</p>
</div>
<dl class="ed-facts">
<div><dt>Coverage</dt><dd>8,841 members</dd></div>
<div><dt>Historical span</dt><dd>1757–2025</dd></div>
</dl>
<a class="ed-action" href="https://riskalab-databank.vercel.app/us-congress" target="_blank" rel="noopener">Explore <span aria-hidden="true">↗</span></a>
</article>

<article class="ed-dataset-row">
<div class="ed-dataset-copy">
<p class="ed-item-label"><span class="ed-status ed-status-public">Public platform</span> Comparative</p>
<h3>OECD Ministerial Officials</h3>
<p>Enables cross-national comparison of ministerial recruitment, political careers, education, party affiliation, and family networks.</p>
</div>
<dl class="ed-facts">
<div><dt>Coverage</dt><dd>3,642 officials</dd></div>
<div><dt>Scope</dt><dd>OECD member countries</dd></div>
</dl>
<a class="ed-action" href="https://riskalab-databank.vercel.app/oecd-ministers" target="_blank" rel="noopener">Explore <span aria-hidden="true">↗</span></a>
</article>

<article class="ed-dataset-row">
<div class="ed-dataset-copy">
<p class="ed-item-label"><span class="ed-status ed-status-public">Public platform</span> Transnational</p>
<h3>Career Trajectories of International Organization Officials</h3>
<p>Traces movement into, across, and beyond international organizations, including education, family ties, and pre- and post-IO careers.</p>
</div>
<dl class="ed-facts">
<div><dt>Coverage</dt><dd>6,870 officials</dd></div>
<div><dt>Records</dt><dd>69,473 career entries</dd></div>
<div><dt>Career span</dt><dd>1852–2025</dd></div>
</dl>
<a class="ed-action" href="https://riskalab-databank.vercel.app/io-officials" target="_blank" rel="noopener">Explore <span aria-hidden="true">↗</span></a>
</article>

<article class="ed-dataset-row">
<div class="ed-dataset-copy">
<p class="ed-item-label"><span class="ed-status ed-status-published">Published research</span> China</p>
<h3>Chinese Political Elites</h3>
<p>Links detailed career histories to official portraits and perceived facial traits in order to study promotion, political selection, and purge outcomes.</p>
</div>
<dl class="ed-facts">
<div><dt>Coverage</dt><dd>4,000+ officials</dd></div>
<div><dt>Linked data</dt><dd>Careers and portraits</dd></div>
</dl>
<a class="ed-action" href="/assets/pdfs/JiangYang_Face.pdf" target="_blank" rel="noopener">Paper <span aria-hidden="true">↗</span></a>
</article>

</div>

<div class="ed-expansion-note">
<p class="ed-item-label"><span class="ed-status ed-status-development">In construction</span> Comparative expansion</p>
<p><strong>Russia and Southeast Asia.</strong> New modules covering Russian political elites and ten Southeast Asian countries are being cleaned and aligned to the common career, education, affiliation, and institutional-position schema.</p>
</div>
</section>

<section id="scale" class="ed-section" aria-labelledby="scale-title">
<header class="ed-section-head">
<div>
<p class="ed-kicker">02 · Scale</p>
<h2 id="scale-title">Scalable and Auditable Data Construction</h2>
</div>
<p>Constructing data from documents requires more than asking a model to code. My methodological work separates two linked problems: how relevant evidence is found and synthesized, and how complex coding rules are executed, revised, and audited across cases.</p>
</header>

<div class="ed-pipeline" role="img" aria-label="A four-stage pipeline from dispersed sources to versioned research data">
<div class="ed-pipeline-step">
<span>01</span>
<strong>Dispersed sources</strong>
<small>Search multilingual documents and open-web evidence</small>
</div>
<div class="ed-pipeline-step">
<span>02</span>
<strong>Source-linked evidence</strong>
<small>Resolve identity and synthesize claims with citations</small>
</div>
<div class="ed-pipeline-step">
<span>03</span>
<strong>Executable codebook</strong>
<small>Apply rules, escalate ambiguity, and preserve rulings</small>
</div>
<div class="ed-pipeline-step">
<span>04</span>
<strong>Versioned dataset</strong>
<small>Recode consistently and retain an auditable record</small>
</div>
</div>

<p class="ed-pipeline-note">Expert adjudication feeds decisions back into the workflow, allowing rule updates to be applied consistently across previously coded cases.</p>

<!--
RECOMMENDED IMAGE 2: one evidence-to-data composite, placed here or alongside the first project.
File: /assets/img/data/evidence-to-data.png
Format: 16:9. Show three readable panels: source document or webpage; source-linked
biographical synthesis; final structured record. Use a real example and keep text large enough to read.
Avoid model logos and dense screenshots of the full agent architecture.
-->

<div class="ed-method-list">

<article class="ed-method-item">
<div class="ed-method-number">01</div>
<div class="ed-method-copy">
<p class="ed-item-label">Evidence discovery and synthesis</p>
<h3>Agentic Framework for Political Biography Extraction</h3>
<p class="ed-question">How can researchers recover reliable biographical evidence from dispersed, multilingual, and unevenly documented sources?</p>
<p>The project evaluates a two-stage synthesis-and-coding workflow across Chinese, American, and OECD political elites, benchmarking automated data production against human-curated and human-coded records.</p>
<div class="ed-item-footer">
<span class="ed-status ed-status-review">Revise &amp; resubmit · AJPS Research Note</span>
<a class="ed-text-link" href="/assets/pdfs/political_fact_extraction_20260305.pdf" target="_blank" rel="noopener">Read paper <span aria-hidden="true">→</span></a>
</div>
</div>
</article>

<article class="ed-method-item">
<div class="ed-method-number">02</div>
<div class="ed-method-copy">
<p class="ed-item-label">Consistent codebook execution</p>
<h3>The Codebook Is Not a Prompt</h3>
<p class="ed-subtitle">Compiling Social Science Coding Rules into Adaptive LLM Workflows</p>
<p class="ed-question">How can complex coding rules be translated into workflows that preserve expert decisions, resolve ambiguity, and support consistent recoding?</p>
<p>The project treats a codebook as an executable and governed data-production process rather than a single prompt, with structured task decomposition, expert escalation, persistent rulings, and version-aware recoding.</p>
<div class="ed-item-footer">
<span class="ed-status ed-status-development">In development</span>
</div>
</div>
</article>

</div>

<div class="ed-bridge"><strong>The first project governs evidence; the second governs rules.</strong> Together they form a complete path from fragmented documents to transparent, research-ready comparative data.</div>
</section>

<section id="depth" class="ed-section" aria-labelledby="depth-title">
<header class="ed-section-head">
<div>
<p class="ed-kicker">03 · Depth</p>
<h2 id="depth-title">Measuring Elite Behavior Beyond Text</h2>
</div>
<p>Biographical records reveal where elites come from and how their careers unfold. Images, audio, and video reveal how political selection, authority, conflict, and emotion are expressed in real time.</p>
</header>

<div class="ed-project-list">

<article class="ed-project-row">
<div class="ed-project-visual ed-stat-visual" aria-label="Portraits of Power project scale">
<span>Official portraits × career histories</span>
<strong>4,000+</strong>
<small>Chinese political elites</small>
</div>
<div class="ed-project-copy">
<p class="ed-item-label"><span class="ed-status ed-status-published">APSR · Online First</span> Official portraits</p>
<h3>Portraits of Power</h3>
<p class="ed-subtitle">Facial Appearances and the Tacit Domain of Political Selection in China</p>
<p>Uses official portraits and career histories to examine how perceived competence, trustworthiness, aggressiveness, and attractiveness relate to promotion and purge outcomes.</p>
<div class="ed-item-footer">
<span class="ed-media-tag">Images + career histories</span>
<a class="ed-text-link" href="/assets/pdfs/JiangYang_Face.pdf" target="_blank" rel="noopener">Read paper <span aria-hidden="true">→</span></a>
</div>
</div>
</article>

<!--
RECOMMENDED IMAGE 3A: replace the Portraits of Power stat panel above.
File: /assets/img/data/portrait-selection-strip.png
Use a deliberately cropped, website-specific figure: two rows (female and male) and three columns
(low / middle / high) for ONE theoretically central perceived trait, ideally trustworthiness or aggressiveness.
Do not reuse both full 4-by-5 figures; their labels become unreadable on the page.
-->

<article class="ed-project-row ed-project-row-reverse">
<div class="ed-project-visual ed-stat-visual" aria-label="Performing Opposition project scale">
<span>Voice × face × text</span>
<strong>355</strong>
<small>hours of legislative video</small>
</div>
<div class="ed-project-copy">
<p class="ed-item-label"><span class="ed-status ed-status-review">Under review</span> Video · Voice · Text</p>
<h3>Performing Opposition</h3>
<p class="ed-subtitle">Multimodal Evidence from South Korea's National Assembly</p>
<p>Combines legislative video, speech audio, facial affect, transcripts, and legislator biographies to study how partisan conflict and shifts between government and opposition shape emotional expression.</p>
<div class="ed-item-footer">
<span class="ed-media-tag">247 legislators · 11,060 speeches</span>
<a class="ed-text-link" href="/assets/pdfs/KangYang_2026.pdf" target="_blank" rel="noopener">Read paper <span aria-hidden="true">→</span></a>
</div>
</div>
</article>

<!--
RECOMMENDED IMAGE 3B: replace the Performing Opposition stat panel above.
File: /assets/img/data/korea-multimodal-frame.png
Use one 16:9 composite built from an actual National Assembly frame, a short audio waveform,
and a small facial-affect or voice-anger trace. Keep the legislator visible and the analytic overlays restrained.
-->

<article class="ed-project-row">
<div class="ed-project-visual ed-stat-visual" aria-label="The Disciplined Face of Power project scale">
<span>Political video × facial affect</span>
<strong>20,000+</strong>
<small>recorded appearances</small>
</div>
<div class="ed-project-copy">
<p class="ed-item-label"><span class="ed-status ed-status-development">Work in progress</span> Political video</p>
<h3>The Disciplined Face of Power</h3>
<p class="ed-subtitle">Affective Signaling and Hierarchical Rule in China</p>
<p>Uses large-scale video of Chinese officials to examine how political hierarchy shapes facial affect, stress display, calmness, and the strategic management of emotion.</p>
<div class="ed-item-footer">
<span class="ed-media-tag">Video + facial affect</span>
</div>
</div>
</article>

<!--
RECOMMENDED IMAGE 3C: replace the Disciplined Face stat panel above.
File: /assets/img/data/china-video-affect.png
Use three sequential frames from one public political video with a compact affect-over-time trace below.
A sequence is more informative than a single headshot and makes the temporal character of the measure visible.
-->

</div>
</section>

<section id="shared-access" class="ed-section" aria-labelledby="shared-title">
<header class="ed-section-head">
<div>
<p class="ed-kicker">04 · Shared access</p>
<h2 id="shared-title">From Research Infrastructure to Shared Infrastructure</h2>
</div>
<p>Risk-A-Lab Data Intelligence turns project-specific databases and data-management practices into shared resources for political science and international relations.</p>
</header>

<div class="ed-platform">
<div class="ed-platform-copy">
<p class="ed-item-label">Platform lead · PKU Analytics Lab for Global Risk Politics</p>
<h3>Risk-A-Lab Data Intelligence</h3>
<p>At Peking University, I lead day-to-day development of a platform that organizes original databases, harmonized public datasets, and interactive tools for discovery, documentation, visualization, and reuse.</p>
<ul class="ed-platform-functions">
<li><strong>Original data</strong><span>Interactive access to datasets produced by the lab and affiliated projects.</span></li>
<li><strong>Harmonization</strong><span>Common substantive classifications and comparable data structures.</span></li>
<li><strong>Discovery and reuse</strong><span>Dataset and variable search, linkage, visualization, documentation, and reproducible export.</span></li>
</ul>
<div class="ed-buttons">
<a class="ed-button ed-button-primary" href="https://riskalab-databank.vercel.app/" target="_blank" rel="noopener">Visit platform</a>
<a class="ed-button" href="https://riskalab-databank.vercel.app/databases" target="_blank" rel="noopener">Original databases</a>
<a class="ed-button" href="https://riskalab-databank.vercel.app/library" target="_blank" rel="noopener">Dataset library</a>
</div>
</div>

<div class="ed-browser-preview" aria-label="Stylized preview of Risk-A-Lab Data Intelligence">
<div class="ed-browser-bar"><span></span><span></span><span></span></div>
<div class="ed-browser-body">
<p>Risk-A-Lab Data Intelligence</p>
<div><strong>Original Databases</strong><span>Explore political elites and global-risk data</span></div>
<div><strong>Dataset Library</strong><span>Find datasets by topic, unit, place, and time</span></div>
<div><strong>Interactive Tools</strong><span>Search, visualize, document, and export</span></div>
</div>
</div>
</div>

<!--
RECOMMENDED IMAGE 4: replace the stylized browser preview above.
File: /assets/img/data/riskalab-platform.png
Capture an interior page with real database cards, filters, or a visualization—not only the landing-page logo.
Crop to roughly 16:10 and retain enough interface detail to demonstrate that the platform is functional.
-->

<div class="ed-access-note">
<p><strong>Data access and replication.</strong> Public modules can be explored through Risk-A-Lab Data Intelligence. Replication materials for published findings will be released in accordance with journal requirements. Where underlying image, video, licensed, or personally identifying sources cannot be redistributed, I will provide source documentation, derived measures, code, and metadata wherever possible.</p>
<p>Risk-A-Lab Data Intelligence is team-built. Editorial direction is set by the Lab Director; I lead day-to-day platform development, with database maintainers and research assistants contributing individual datasets and documentation. For access or collaboration inquiries, please <a href="mailto:yangsp@pku.edu.cn">contact me</a>.</p>
</div>
</section>

</div>
