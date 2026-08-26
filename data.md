---
title: Data
layout: page
permalink: data.html
menu: true
order: 2
description: Datasets, measurement systems, and AI-assisted workflows for the comparative study of political elites.
hide_description: true
---

My research relies on data infrastructures that make political elites observable across settings and over time. This page presents the datasets, measurement systems, and AI-assisted workflows that support the substantive papers described on the [Research page](/research.html). Together, these resources expand comparative coverage, scale document-based data construction, and extend political measurement beyond conventional biographical and textual records.

<h3>Comparative Political Elites Data</h3>

I am building a modular collection of political biographies that traces careers, education, political affiliations, family ties, and institutional positions across national and transnational settings. Individual modules are released separately while being aligned to a common data structure.

<p>
<strong>Chinese Political Elites.</strong><br>
Career histories and official portraits for more than 4,000 mid- and senior-level officials, including promotion timing and purge outcomes. These data support <a href="/assets/pdfs/JiangYang_Face.pdf" target="_blank"><em>Portraits of Power</em></a> and related research on political selection.
</p>

<p>
<strong>US Congressional Legislators.</strong><br>
A database of 8,841 senators and representatives spanning 1757–2025, with biographical information, education, career paths, party affiliations, geography, and political-family networks. <a href="https://riskalab-databank.vercel.app/us-congress" target="_blank">Explore the database →</a>
</p>

<p>
<strong>OECD Ministerial Officials.</strong><br>
A comparative database of 3,642 ministerial-level officials across 36 OECD member countries, covering education, prior careers, party affiliation, ministerial portfolios, and family networks. <a href="https://riskalab-databank.vercel.app/oecd-ministers" target="_blank">Explore the database →</a>
</p>

<p>
<strong>Career Trajectories of International-Organization Officials.</strong><br>
Biographical and career data for 6,870 officials who have served in international organizations. The collection contains 69,473 career records, including 21,794 positions within international organizations as well as pre- and post-IO careers in governments, universities, NGOs, and the private sector. <a href="https://riskalab-databank.vercel.app/io-officials" target="_blank">Explore the database →</a>
</p>

<p>
<strong>Russia and Southeast Asia Modules.</strong><br>
New national modules extend the collection to Russian political elites and ten Southeast Asian countries. Data cleaning and harmonization are ongoing.
</p>

These datasets are designed to support comparative research on elite recruitment and mobility; education, family background, and political networks; and movement across parties, governments, international organizations, and private institutions.

<h3>AI-Assisted Data Construction</h3>

My methodological work addresses two linked problems in document-based data production: how relevant evidence enters a dataset, and how coding rules are executed consistently once that evidence has been assembled.

> Dispersed and multilingual sources → source-linked evidence synthesis → codebook execution → expert adjudication → versioned datasets

<p>
<strong>Evidence discovery and synthesis.</strong><br>
<a href="/assets/pdfs/political_fact_extraction_20260305.pdf" target="_blank"><em>Agentic Framework for Political Biography Extraction</em></a> develops a two-stage workflow in which agents search for and synthesize biographical evidence before an LLM coder converts the curated material into structured records. The project is under revise and resubmit as a Research Note at the <em>American Journal of Political Science</em>.
</p>

<p>
<strong>Codebook execution and governance.</strong><br>
<em>The Codebook Is Not a Prompt</em> studies how complex social-science coding rules can be compiled into adaptive workflows that decompose tasks, identify relevant objects, escalate ambiguous cases to experts, preserve adjudication decisions, and apply revised rules consistently across previously coded cases. The project is in development.
</p>

Together, the two projects describe a continuous production chain: the first governs how evidence enters the system; the second governs how research rules are applied within it.

<h3>Multimodal Measurement</h3>

Biographical records reveal where elites come from and how their careers unfold, but they do not capture how authority, conflict, and emotion are performed in political settings. I therefore use images, voice, and video to construct measures of perceived appearance, vocal delivery, and facial affect.

<p>
<strong>Official portraits and political selection.</strong><br>
The data behind <a href="/assets/pdfs/JiangYang_Face.pdf" target="_blank"><em>Portraits of Power</em></a> link official portraits to human and machine estimates of perceived competence, trustworthiness, aggressiveness, and attractiveness, as well as detailed promotion and purge outcomes for more than 4,000 Chinese officials.
</p>

<p>
<strong>Voice, face, and legislative behavior.</strong><br>
The South Korean National Assembly project combines 355 hours of plenary video, 11,060 speech segments, facial and vocal measures, transcripts, and legislator biographies. The associated paper, <a href="/assets/pdfs/KangYang_2026.pdf" target="_blank"><em>Performing Opposition</em></a>, examines how partisan blame and changes between government and opposition shape emotional expression.
</p>

<p>
<strong>Dynamic affect in political hierarchy.</strong><br>
<em>The Disciplined Face of Power</em> draws on more than 20,000 video appearances of Chinese officials to study how rank and institutional role shape calmness, stress, and the management of facial affect over time.
</p>

<!-- Optional future visual: replace this comment with a compact horizontal figure showing
     (1) official portraits, (2) a legislative video frame with voice/face traces, and
     (3) a short sequence of official-video frames. Avoid a full card layout so the page
     continues to match the rest of the site. -->

<h3>Risk-A-Lab Data Intelligence</h3>

At Peking University, I lead the day-to-day development of [Risk-A-Lab Data Intelligence](https://riskalab-databank.vercel.app/), an interactive platform that organizes original databases, harmonized public datasets, and tools for discovery, documentation, visualization, and reuse. The platform extends this infrastructure-building work from individual research projects to shared resources for political science and international relations.

- [Original databases](https://riskalab-databank.vercel.app/databases)
- [Dataset library](https://riskalab-databank.vercel.app/library)
- [About the platform](https://riskalab-databank.vercel.app/about)

Risk-A-Lab Data Intelligence is a team-built platform. Editorial direction is set by the Lab Director; I lead day-to-day platform development, while database maintainers and research assistants contribute individual datasets and documentation.

<h3>Data Access and Collaboration</h3>

Public modules can be explored through Risk-A-Lab Data Intelligence. Replication materials for published findings will be released in accordance with journal requirements. Some image, video, licensed, or personally identifying source materials cannot be redistributed; where possible, I will provide source documentation, derived measures, code, and metadata needed to understand and reproduce the data-production process.

For data access, documentation, or collaboration inquiries, please contact me at [yangsp@pku.edu.cn](mailto:yangsp@pku.edu.cn).
