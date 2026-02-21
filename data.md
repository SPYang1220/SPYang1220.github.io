---
title: Data
layout: page
permalink: data.html
menu: true
order: 2
---

<div style="background:#f4f4f4; padding:12px 18px; border-radius:6px; font-size:0.95em; margin-bottom:2em;">

<strong>Data & Replication Policy</strong><br>

- Replication materials necessary to reproduce published findings will be made publicly available upon article publication, in accordance with journal requirements.
- For access to more detailed datasets, ongoing projects, or collaboration inquiries, please contact me via email.

</div>

---

# I. The Face of Political Elites

This research agenda examines how the *“face”* of political elites—understood broadly as visible appearance, affective expression, and embodied signaling—shapes political evaluation, hierarchy, and institutional accountability across regime types.

Across different political contexts, I construct original large-scale multimodal datasets linking visual and emotional cues to elite career outcomes and institutional incentives.

## Data Infrastructure

**1. Elite Facial Image Dataset (China – Political Promotion and Purge Risk)**  
From: *Portraits of Power: Facial Appearances and the Tacit Domain of Political Selection in China.* (APSR, Conditionally Accepted)

- 4,000+ mid- and senior-level Chinese officials, 2000-2022  
- Official portrait photographs collected from government archives  
- Linked to detailed career histories, promotion timing, and purge outcomes  
- Machine-estimated facial traits (competence, trustworthiness, aggressiveness, attractiveness) using a deep-learning model trained to replicate human evaluations  

This dataset enables analysis of how perceived facial traits predict political survival and promotion in authoritarian bureaucracies.

**2. Elite Affective Expression Dataset (China – Hierarchical Emotional Discipline)**  
From: *The Disciplined Face of Power: Affective Signaling and Hierarchical Rule in China.*（Working paper)

- 20,000+ video appearances of Chinese officials  
- Frame-level facial affect extraction using deep neural networks  
- Measures of emotional calmness, stress signaling, and affective regulation  

This dataset examines how emotional discipline functions as an informal signaling mechanism within bureaucratic hierarchies.

**3. Legislative Emotional Performance Dataset (South Korea – Electoral Accountability)**  
From: *Spontaneous Outburst or Strategic Signal? Legislative Emotions in South Korea.*（Working paper)

- Full universe of plenary sessions (784 sessions; 1,750+ hours) of the Korean National Assembly, 2010–2025  
- Automated video-based emotion recognition applied to parliamentary debate recordings  
- Integrated with legislative transcripts and legislator-level biographical metadata  

This dataset enables analysis of how electoral accountability incentives shape strategic emotional expression in democratic legislative settings.

## Visualizations

### 1. Facial Appearance and Political Selection
From: *Portraits of Power: Facial Appearances and the Tacit Domain of Political Selection in China*  
(<strong><em>American Political Science Review</em></strong>, Conditionally Accepted)

**Average Faces by Facial Rating and Gender**

The figures below visualize how perceived facial traits correlate with elite political advancement in China. Officials are grouped by percentile rankings of machine-estimated facial traits. Synthetic “average faces” are generated within each percentile group to illustrate systematic perceptual variation associated with career outcomes.

<div style="display:flex; justify-content:space-between; gap:3%; flex-wrap:wrap; margin-top:1em;">

<div style="flex:48%; text-align:center;">
<img src="/assets/img/data/portraits/female_adjusted3.png" style="width:100%;">
<p><em>Female Officials</em></p>
</div>

<div style="flex:48%; text-align:center;">
<img src="/assets/img/data/portraits/male_adjusted3.png" style="width:100%;">
<p><em>Male Officials</em></p>
</div>

</div>

<p style="font-size:0.9em; color:#666;">
The leftmost and rightmost images represent averages of the highest- and lowest-rated officials for each trait.
</p>

**Contributions of Facial Regions to Trait Perceptions**

The figures below illustrates the contributions of different facial regions to the machine-based ratings of the four facial traits. The facial heat maps are produced by Gradient-weighted Class Activation Mapping (Grad-CAM), a visualization technique for interpreting deep-learning models. Regions highlighted in red indicate significant contributions to the prediction of the trait, while blue regions indicate minimal contributions.

<div style="text-align:center; margin-top:1em;">
<img src="/assets/img/data/portraits/Grad_CAM.png" style="width:75%; max-width:900px; border-radius:6px;">
</div>

<p style="font-size:0.9em; color:#666;">
Heat maps are generated using Gradient-weighted Class Activation Mapping (Grad-CAM).
</p>

### 2. Affective Hierarchy and Emotional Discipline  
From: *The Disciplined Face of Power: Affective Signaling and Hierarchical Rule in China*  
(Working paper)

Coming soon.

---

# II. LLMs and Social Science Research Methods

This research agenda develops automated frameworks for extracting political facts, coding legal texts, and scaling expert-level annotations using large language models.

*Visualizations and datasets forthcoming soon.*

---

# III. Political Elites in Global Governance

This research agenda studies elite networks, institutional power, and leadership selection in international organizations and global governance institutions.

*Visualizations and datasets forthcoming soon.*