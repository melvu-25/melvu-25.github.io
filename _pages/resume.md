---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /cv/
---

{% include base_path %}

<!-- To link a PDF version: put resume.pdf in /files/ and uncomment the next line -->
<!-- [Download resume (PDF)](/files/resume.pdf) -->

<!--
How each entry is laid out:
  <p class="cv-head"> = organization (bold) + location on the right
  <p class="cv-sub">  = role or degree (italic) + dates on the right
  then a normal bullet list
-->

Education
======

<p class="cv-head"><span class="cv-date">College Park, MD</span><strong>University of Maryland, College Park</strong></p>
<p class="cv-sub"><span class="cv-date">Expected 05/2031</span><em>Doctor of Philosophy in Information Science</em></p>

* Computational Social Science, Social Network Analysis, Natural Language Processing.
* Advisors: [Dr. Masha Krupenkin](https://masha-krupenkin.com/) and [Dr. Yiwei Xu](https://www.yiweixu.net/) (co-advisor)
* Labs: [Computational Linguistics and Information Processing (CLIP)](https://wiki.umiacs.umd.edu/clip/index.php/Main_Page) and Computational Sociodynamics Lab (CSDL).
* Dean's Fellowship Award recipient.

<p class="cv-head"><span class="cv-date">Gambier, OH</span><strong>Kenyon College</strong></p>
<p class="cv-sub"><span class="cv-date">08/2022 – 05/2026</span><em>Bachelor of Science, Mathematics (Applied Statistics track) and Chinese double major.</em></p>

* GPA: 3.7 - Daniel T. Finkbeiner II Scholarship for Excellence in Mathematics and Statistics.
* Activities: Pi Mu Epsilon Mathematics Honor Society, Women in Math, Community Choir, Dance Concert.
* Fall 2024 in Shanghai, China: Advanced Chinese, Chinese Economy, Contemporary Chinese Cinema, Internship.

Research experience
======

<p class="cv-head"><span class="cv-date">College Park, MD</span><strong>University of Maryland, College Park</strong></p>
<p class="cv-sub"><span class="cv-date">08/2026 – Present</span><em>Graduate Research Assistant | Advisor: Dr. Masha Krupenkin</em></p>

* Designed a study of how borrowers' online discourse tracks government complaint data, linking 162K r/StudentLoans posts and 2.1M comments (2011 to 2026) with 106K CFPB student loan complaints in a reproducible Python and DuckDB pipeline.
* Used Claude Code agents to run EDA, literature review, and user profiling in parallel, while owning the research design and logging each methodological decision for advisor review.
* Developed a scalable topic modeling pipeline (BERTopic, transformer embeddings) over 1.9M Reddit texts and CFPB narratives, condensing 262 raw topics into 71 interpretable themes, and profiled the top 100 commenters' cross-subreddit activity to study who shapes the discussion.

<p class="cv-head"><span class="cv-date">Gambier, OH</span><strong>Kenyon College</strong></p>
<p class="cv-sub"><span class="cv-date">05/2025 – 08/2026</span><em>Research Assistant | John W. Adams Summer Scholars</em></p>

* Analyzed public discourse and opinion dynamics around a local solar energy project with computational methods, mentored by Professor Nicholas Theis through a competitive, fully funded research fellowship.
* Modeled 3,000+ public comments with large-scale content analysis and network methods in R (community detection, betweenness centrality), identifying ideological clusters.
* Second author on a paper developed from this research; manuscript in preparation for journal submission by the end of 2026.

<p class="cv-sub"><span class="cv-date">12/2023 – 05/2026</span><em>Senior Student Researcher | Institutional Research (IR) Office</em></p>

* Standardized 10,000+ inconsistent survey records into analysis-ready longitudinal datasets in R and Excel via a reusable cleaning pipeline, cutting prep time and enabling leadership decisions on retention and student success.
* Recognized by the IR Office Director as having "Exceeded Expectations" and promoted to the senior role for outstanding performance, with added responsibility of mentoring junior interns.

Research projects
======

<p class="cv-head"><span class="cv-date">10/2026</span><strong>What AI Calls You: Social Deixis, Pronoun Systems, and the Limits of AI Agents in Vietnamese</strong></p>

* Studied how AI agents choose Vietnamese pronouns to address the user and to refer to themselves, a choice governed by age, gender, and family rank; designed 36 persona-based scenarios across 3 difficulty tiers (up to family rank vs. age conflicts).
* Built an evaluation pipeline (Google Apps Script, OpenRouter API) that queries Claude Opus 5.5, Qwen 3.5-Plus, and Llama 4 Maverick and auto-drafts codes with an LLM coder; validated LLM-assisted coding against hand codes (94% agreement on 81 preliminary replies).
* Expanding the pilot into a full study (36 scenarios, 324 replies) for publication, adding LLM-assisted labeling of all replies, a second native-speaker rater (Krippendorff's alpha), and a Bayesian mixed-effects model of register choice by difficulty tier and model.

<p class="cv-head"><span class="cv-date">05/2026</span><strong>Whose Vietnam War? How LLMs Answer Contested History in Three Languages</strong> <a href="https://digital.kenyon.edu/dh_iphs_ai/66/"><em>publication link</em></a></p>

* Designed and executed a cross-lingual bias audit of four frontier LLMs (Grok 4, GPT-5.5, Claude Opus 4.7, DeepSeek V4), prompting each with four contested historical questions in English, Vietnamese, and Mandarin across 48 isolated chat sessions to prevent context contamination; ranked #1 in the class and selected by faculty for publication.
* Built a manual coding framework (question-specific 1-5 stance scale, balance, hedging frequency, cross-language consistency) and found models gave identical stances across languages only 43.75% of the time, ranging from 75% for Claude Opus 4.7 down to 25% for GPT-5.5 and DeepSeek V4.
* Tested language sensitivity with a chi-square test of independence in R, validated by a 10,000-iteration Monte Carlo permutation test, showing bias concentrates on questions where official national narratives diverge.

<p class="cv-head"><span class="cv-date">01/2026</span><strong>Two Moles, Two Worlds: Network Analysis of "Infernal Affairs" and "The Departed"</strong> <a href="https://digital.kenyon.edu/dh_iphs_prog/82/"><em>publication link</em></a></p>

* Designed and executed a network-based comparative analysis of two film adaptations in Python (pandas, NetworkX, matplotlib), modeling character interactions through weighted co-presence and directed dialogue graphs; selected by faculty for publication on Digital Kenyon.
* Engineered structured interaction datasets from raw subtitle files and screenplays, using Gemini to transform unstructured dialogue text into 4 quantified interaction matrices (co-presence and directed dialogue per film).
* Applied graph-theoretic methods (modularity-based community detection, betweenness centrality, weighted edge analysis) to identify cross-community bridges and structural differences in social organization.

Publications and conferences
======

* Theis, N., **Vu, M.**, & Warshauer, A. "No View Under the Sun: A Content and Social Network Analysis of Political Engagement with Frasier Solar." ***Manuscript in preparation for journal submission***.
* **Vu, M.** "What AI Calls You: Social Deixis, Pronoun Systems, and the Limits of AI Agents in Vietnamese." Technology for Second Language Learning (TSLL) Conference, Iowa State University, October 2026. ***Presenter and panel chair***.
* Theis, N., & **Vu, M.** "Social Network Analysis of Public Discourse Around the Frasier Solar Project." Midwest Sociological Society (MSS) Annual Meeting, March 2026. ***Co-presenter***.

Industry experience
======

<p class="cv-head"><strong>VinBigdata @ VinGroup</strong></p>
<p class="cv-sub"><span class="cv-date">05/2024 – 08/2024</span><em>Data Science Intern</em></p>

* Improved production pricing accuracy by 40% by engineering features and implementing open-source ML models on 15M+ ride records in Python and SQL, optimizing the ETA component of Green SM Taxi's fare-calculation service.
* Ran K-means clustering at scale to segment ride-demand patterns nationally, surfacing geographic and behavioral demand signals that informed the dynamic-pricing strategy delivered to product managers.
* Designed and built interactive dashboards in Tableau and Power BI, delivering actionable insights to project managers and product teams on dynamic pricing models, driver availability, and customer demand.

<p class="cv-head"><span class="cv-date">Shanghai, China</span><strong>Grant Thornton</strong></p>
<p class="cv-sub"><span class="cv-date">08/2024 – 12/2024</span><em>Forensic Advisory (FAS) Research Intern</em></p>

* Researched applications of AI and predictive modeling in forensic accounting; authored two research articles on fraud detection and corporate compliance distributed to 1,000+ clients.
* Conducted economic and political scenario analysis on multinational business risks in China and prepared presentation materials that were delivered at a national real estate conference, attended by 140+ executives, leading to multiple invitations from chambers to repeat the presentation at future events.

Skills
======

* **Technical skills:** Python (pandas, scikit-learn, LightGBM, NetworkX), R, SQL (DuckDB), Google Apps Script, Evidently AI, MATLAB, C++, Atlas.ti, Power BI, Tableau, Microsoft Excel, Qualtrics.
* **NLP and AI tools:** BERTopic, transformer embeddings, LLM-assisted annotation, OpenRouter API, Claude Code.
* **Languages:** English (fluent), Vietnamese (native), Chinese Mandarin (advanced).
