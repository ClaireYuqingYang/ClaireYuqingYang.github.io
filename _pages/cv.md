---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **M.S. in Applied Statistics for Social Science Research**, New York University, Sept. 2024 – May 2026
  * GPA: 3.967/4.0
  * Core Courses: Causal Inference, Multilevel Modeling, Messy Data and Machine Learning, Statistical Computing, Frequentist Inference, Modern Approaches in Measurement, Generative AI for the Social Sciences, Database and Data Science Practicum, Experimental and Quasi-Experimental Design, Missing Data, Computer Vision

* **B.B.A. in Management (Global Business Management)**, Chinese University of Hong Kong, Shenzhen, Sept. 2019 – May 2024
  * Upper Second Class (Honors) · Major GPA: 3.27/4.0
  * Minor in Applied Psychology · Minor GPA: 3.73/4.0
  * Honors: 2022–23 & 2023–24 Dean's List; Four-Year Entrance Scholarship ($16,900)

Research Interests
======
**Topics:** Behavioral decision-making in consumer and organizational contexts, with a focus on misinformation, attention, moral judgment, and authenticity in technology-mediated environments.

**Methodology:** Survey design, laboratory and online experiments, causal inference for behavioral data, multilevel modeling, and computational social science (NLP-based measurement, behavioral trace data).

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks & Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Research Experience
======
* **Development Lead / RA**, Columbia Business School, Br-Ane Lab, Sept. 2025 – Present
  * Advisor: Prof. Kristen Lane & Prof. Melanie Brucks
  * Designed and built an experimental Chrome extension to causally manipulate and measure participants' exposure to misinformation in real time at Bluesky, incorporating a transformer-based arousal model, misinformation model (linguistic-feature-based), and behavioral trace logging for hypothesis testing.
  * Designed and tested GPT-based conversational agents to replace the second human participant in a dual-party creativity experiment, programming prompts that manipulate cognitive similarity vs. difference by holding or shifting causal pathways.
  * Conducted LLM prompt evaluations to assess Digital Twin alignment in behavioral tasks.

* **Summer Research Intern**, Columbia Business School, Jun. 2025 – Aug. 2025
  * Advisor: Prof. Kristen Lane
  * Co-designed the JPPM proposal *FeedFrame*, contributing to the conceptual framework, pilot, and preregistered analysis plan.
  * Built the web demo and embedded it into Qualtrics (HTML/CSS/JavaScript), implementing a News/Entertainment toggle and capturing interaction logs (JSON clickstream, timestamps).
  * Estimated mixed-effects logistic models; used ICC to assess hierarchical dependence, two-way cluster-robust SEs for participant/post cross-classification, and DID for causal identification.
  * Ran two Digital Twin Mega Study replications; replicated human WTP effects of digital certification but not status perceptions; found Digital Twin (not humans) improved truth discernment under accuracy nudges.
  * Conducted field data collection in Queens and the Bronx for a voter-perception survey during the NYC Democratic Primary.

* **Research Assistant**, LARP Game and Organization Theory, Nov. 2022 – Apr. 2024
  * Advisor: Prof. Rongrong Zhang
  * Drew on 40,000+ words of LARP field notes and scripts to analyze how interactive narratives create authenticity and collective meaning. Contributed to a qualitative study presented at 2023 AoM.
  * Conducted a follow-up experiment applying LARP to diversity training, examining how identity–role similarity leads to positive training outcomes (perspective-taking, psychological safety).

* **Research Assistant**, Organizational Dynamics Lab, Mar. 2024 – Aug. 2024
  * Advisor: Prof. Xinyue Pan
  * Replicated the agent-based Evolutionary Game Theory model using Python and R.
  * Reproduced and analyzed Q-learning inspired models of cooperation; reviewed literature on Social Norm Change and Ethnocentrism.

* **Research Assistant**, Consumer Behavior Research, Jul. 2023 – Mar. 2024
  * Advisor: Prof. Yohoon Jin
  * Conducted review of 10 JCR papers on positive consumer experiences, identifying research gaps in firms' use of music and AI tools.
  * Designed, ran, and analyzed two pilot behavioral studies on luxury consumption and customer tolerance using Qualtrics and SPSS.

Related Projects
======
* **The Topic Tug-of-War: Why LLMs Beat LDA at Making Sense of Conversations**, Jan. 2025 – May 2025
  * [GitHub](https://github.com/ClaireYuqingYang/llm-vs-lda-topic-modeling)
  * Built a corpus of organizational conversations from IETF's mailing-list archive via API scraping.
  * Compared LDA with a local LLM for semantic clustering; LLM-based clustering reduced redundant topics and captured more coherent high-level themes.

* **MLB Pitch-Type Prediction & Strategic Interaction Analysis**, Dec. 2024 – Jan. 2025
  * CSAS 2025 Data Challenge — Team Captain; Poster presented at CSAS 2025, Yale University
  * Built predictive models (Random Forest, BART) to classify pitch types and evaluate strategic batter-pitcher interactions. Identified quasi-causal effects of extreme bat-speed observations on pitcher fastball decisions.

* **Exploring Inflated Self-Reporting in Social Surveys**, Oct. 2024 – Dec. 2024
  * Course project for Messy Data & Machine Learning at NYU; presented at 2025 NYU Society for Statistics Conference
  * Investigated self-reporting bias using General Social Survey (N=13,932). Used inverse probability weighting with boosted regression. Found professional overstatement of educational achievements (~24%, p<.01).

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Entrepreneurship
======
* **Founder**, Shanhai Yi Culture Media Co., Ltd. (Live Action Role Play Game), Sept. 2021 – Jun. 2022
  * Founded and operated a LARP script-publishing studio. Co-authored and managed the release of five scripts; two published and sold nationally.

* **Founding Member**, Qianshang Technology Co., Ltd., Oct. 2022 – Dec. 2022
  * Led the Intelligent Sleep-Aid Pillow project, integrating hardware, data science, and medical research.

* **Product Consultant**, Versee Technology Co., Ltd. (VR Game, Seed Round), Apr. 2022 – Sept. 2022
  * Led ten+ game script projects; co-created a six-player interactive VR game demo *The Descent* set in a Lovecraftian universe.

Industry Experience
======
* **Project Assistant**, Visagio (Management Consulting), May 2021 – Aug. 2021
  * Analyzed internal operation data for Thyssenkrupp Middle East; led market research for Intel's FPGA in China.
  * Conducted proposal for Visagio's Go-to-China project; conducted ~100 cold calls, reaching 15 potential clients.

* **Project Assistant**, McKinsey & Company, Shanghai, Mar. 2021 – Apr. 2021
  * Authored a pivotal section in McKinsey's 2021 White Book for the SaaS industry (IPO-stage companies, e.g. Asana).
  * Categorized cloud businesses into general and specialized types and conducted comparative analysis.

Skills
======
* **Programming:** R, Python, SQL, JavaScript, HTML/CSS, Git/GitHub, Qualtrics scripting
* **Quantitative Methods:** Mixed-effects models, causal inference (DID, cluster-robust SEs), multilevel modeling, hypothesis testing
* **ML & NLP:** Embeddings, topic modeling, Bayesian Additive Regression Trees (BART), prompt engineering
* **Languages:** English (IELTS 7.5), Mandarin (Native)
