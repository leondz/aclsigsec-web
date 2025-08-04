---
# Title, summary, and page position.
title: LLMSEC 2025
linktitle: LLMSEC 2025
summary: The first ACL Workshop on LLM and NLP Security; Summer 2025, Vienna, Austria
weight: 3
# icon: book
# icon_pack: fas

image:
  filename: covers/keysindoor.jpeg
  caption: by Andrea Piacquadio

# Page metadata.
date: '2024-11-22T00:00:00Z'
toc: false
---

LLMSEC is an academic event publishing & presenting work on adversarially-induced failure modes of large language models, the conditions that lead to them, and their mitigations. 

* Date: Aug 1, 2025
* Location: Vienna, Austria 
* Co-located with [ACL 2025](https://2025.aclweb.org/) as a workshop

## Proceedings

You can get the paper proceedings of the workshop directly, [proceedings.pdf](/proceedings.pdf)

## Program

Friday August 1st, Austria Center Vienna, Hall B. Times in CEST

- 09.00-09.05: Opening
- 09.05-09.55: Keynote 1 - Erick Galinkin: A Bunch of Garbage and Hoping: LLMs, Agentic Security, and Where We Go From Here
- 09.55-10.30: Posters 1 (Hall X5)
  - UTF: Under-trained Tokens as Fingerprints —— a Novel Approach to LLM Identification
  - Using Humor to Bypass Safety Guardrails in Large Language Models
  - LongSafety: Enhance Safety for Long-Context LLMs
  - ArithmAttack: Evaluating Robustness of LLMs to Noisy Context in Math Problem Solving
  - RealHarm: A Collection of Real-World Language Model Application Failures
- 10.30-11.00: Break
- 11.00-11.50: Keynote 2 - Niloofar Mireshghallah: What does it mean for agentic AI to preserve privacy?
- 11.50-12.50: Papers 1
  - 11.50-12.05: Paper - Shortcut Learning in Safety: The Impact of Keyword Bias in Safeguards
  - 12.05-12.20: Paper - Beyond Words: Multilingual and Multimodal Red Teaming of MLLMs
  - 12.20-12.35: Paper - X-Guard: Multilingual Guard Agent for Content Moderation
  - 12.35-12.50: Paper - RedHit: Adaptive Red-Teaming of Large Language Models via Search, Reasoning, and Preference Optimization
- 12.50-14.00: Lunch
- 14.00-14.50: Keynote 3 - Johann Rehberger: Trust No AI - Prompt Injection Along the CIA Security Triad
- 14.50-15.25: Posters 2 (Hall X5)
  - Bypassing LLM Guardrails: An Empirical Analysis of Evasion Attacks against Prompt Injection and Jailbreak Detection Systems
  - Fine-Tuning Lowers Safety and Disrupts Evaluation Consistency
  - SPADE: Structured Prompting Augmentation for Dialogue Enhancement in Machine-Generated Text Detection
  - CAPTURE: Context-Aware Prompt Injection Testing and Robustness Enhancement
- 15.25-16.00: Break
- 16.00-16.30: Papers 2
  - 16.00-16.15: Paper - Weakest Link in the Chain: Security Vulnerabilities in Advanced Reasoning Models
  - 16.15-16.30: Paper - 1-2-3 Check: Enhancing Contextual Privacy in LLM via Multi-Agent Reasoning
- 16.30-16.40: Best paper award, SIGSEC business, closing
  

## Keynotes

### A Bunch of Garbage and Hoping: LLMs, Agentic Security, and Where We Go From Here

*Erick Galinkin, NVIDIA Corporation*

Large Language Models are, in some ways, a miracle. Despite a paucity of theoretical linguistic underpinning and a swath of known weaknesses, they have proven empirically successful beyond the wildest imaginings of many, leading to integration in a wide variety of applications. This has necessitated a strong response from both the information security community and those who study large language models.

This talk examines both cybersecurity implications of LLMs and the LLM implications of cybersecurity. We provide some background on adversarial examples in computer vision as a lens to view the problems in AI systems and cover the parlance of cybersecurity as it frames AI problems. Using these two lenses, we examine the state of LLM security and discuss approaches to uncover and mitigate the risks inherent in LLM-powered applications.

Slides: [pdf](https://www.derczynski.com/~llmsec/garbage_and_hoping.pdf)

**Bio**

Erick Galinkin is a Research Scientist at NVIDIA working on the security assessment and protection of large language models.
Previously, he led the AI research team at Rapid7 and has extensive experience working
in the cybersecurity space. He is an alumnus of Johns Hopkins University and holds
degrees in applied mathematics and computer science. Outside of his work, Erick is a lifelong student, currently at Drexel University
and is renowned for his ability to be around equestrians.

### Trust No AI - Prompt Injection Along the CIA Security Triad

*Johann Rehberger, Independent Researcher*

The CIA security triad - Confidentiality, Integrity, and Availability - is a cornerstone of data and cybersecurity. With the emergence of large language model (LLM) applications, a new class of threat, known as prompt injection, was first identified in 2022. Since then, numerous real-world vulnerabilities and exploits have been documented in production LLM systems, including those from leading vendors like OpenAI, Microsoft, Anthropic and Google. This paper compiles real-world exploits and proof-of concept examples, based on the research conducted and publicly documented, demonstrating how prompt injection undermines the CIA triad and poses ongoing risks to cybersecurity and AI systems at large.

Furthermore the talk will explore command and control infrastructure for ChatGPT which is exploited entirely based on prompt injection and memory persistence.

**Bio**

Johann Rehberger has over twenty years of experience in threat modeling, risk management, penetration testing, and red teaming. During his tenure at Microsoft, Johann established a Red Team within Azure Data and led the program as Principal Security Engineering Manager. He went on to build a Red Team at Uber, and currently serves as Red Team Director at Electronic Arts. In addition to his industry roles, Johann is an active security researcher and a former instructor in ethical hacking at the University of Washington. Johann contributed to the MITRE ATT&CK and ATLAS frameworks and is the author of "Cybersecurity Attacks – Red Team Strategies". He holds a master's degree in computer security from the University of Liverpool. You can find his latest research at [embracethered.com](https://embracethered.com).

### What does it mean for agentic AI to preserve privacy?

*Niloofar Mireshghallah, Meta/CMU*

The rise of agentic LLMs has fundamentally altered the privacy landscape: models now orchestrate information flows between emails, calendars, medical records, and external services, creating novel attack vectors where traditional data protection falls short. These agents must constantly decide what to share, with whom, and in what context—decisions that require nuanced understanding of contextual integrity rather than binary public/private classifications. In this talk, we first introduce CONFAIDE, a benchmark grounded in contextual integrity theory that systematically measures LLMs' privacy reasoning capabilities across increasingly complex scenarios, revealing that frontier models fail up to 39% of the time. We then present a privacy-preserving framework for leveraging powerful models on private data without exposing it: using Socratic Chain-of-Thought reasoning, we decompose tasks between untrusted powerful models that generate reasoning templates and trusted local models that access private data. This enables a 1B-parameter local model augmented with privacy-preserved remote reasoning to outperform GPT-4o by 7.1 percentage points. We conclude with the urgent need for new alignment techniques that incorporate contextual privacy norms into LLM development.

Slides: [pdf](https://www.derczynski.com/~llmsec/inference_privacy_llmsec_2025.pdf)

**Bio**

Dr. Mireshghallah is a Research Scientist at Meta AI’s FAIR Alignment group and joins Carnegie Mellon University’s Engineering & Public Policy (EPP) Department and Language Technologies Institute (LTI) as an Assistant Professor in Fall 2026.

Her research interests are privacy, natural language processing, and the societal implications of ML. Dr. Mireshghallah explores the interplay between data, its influence on models, and the expectations of the people who regulate and use these models. Her work has been recognized by the NCWIT Collegiate Award and the Rising Star in Adversarial ML Award.

## Recognition

### Outstanding Paper Awards

“LongSafety: Enhance Safety for Long-Context LLMs”
- Mianqiu Huang, Xiaoran Liu, Shaojun Zhou, Mozhi Zhang, Qipeng Guo, Linyang Li, Pengyu Wang, Yang Gao, Chenkun Tan, Linlin Li, Qun Liu, Yaqian Zhou, Xipeng Qiu and Xuanjing Huang

“RedHit: Adaptive Red-Teaming of Large Language Models via Search, Reasoning, and Preference Optimization”
- Mohsen Sorkhpour, Abbas Yazdinejad and Ali Dehghantanha

### Best Paper Award

“Weakest Link in the Chain: Security Vulnerabilities in Advanced Reasoning Models”
- Arjun Krishna, Aaditya Rastogi, Erick Galinkin

## Accepted papers

**UTF: Under-trained Tokens as Fingerprints —— a Novel Approach to LLM Identification**<br/>
Jiacheng Cai, Jiahao Yu, Yangguang Shao, Yuhang Wu and Xinyu Xing

**RedHit: Adaptive Red-Teaming of Large Language Models via Search, Reasoning, and Preference Optimization**<br/>
Mohsen Sorkhpour, Abbas Yazdinejad and Ali Dehghantanha

**Using Humor to Bypass Safety Guardrails in Large Language Models**<br/>
Pedro Cisneros-Velarde

**LongSafety: Enhance Safety for Long-Context LLMs**<br/>
Mianqiu Huang, Xiaoran Liu, Shaojun Zhou, Mozhi Zhang, Qipeng Guo, Linyang Li, Pengyu Wang, Yang Gao, Chenkun Tan, Linlin Li, Qun Liu, Yaqian Zhou, Xipeng Qiu and Xuanjing Huang

**ArithmAttack: Evaluating Robustness of LLMs to Noisy Context in Math Problem Solving**<br/>
Zain Ul Abedin, Shahzeb Qamar, Lucie Flek and Akbar Karimi

**X-Guard: Multilingual Guard Agent for Content Moderation**<br/>
Bibek Upadhayay and Vahid Behzadan

**RealHarm: A Collection of Real-World Language Model Application Failures**<br/>
Pierre Le Jeune, Jiaen Liu, Luca Rossi and Matteo Dora

**Bypassing LLM Guardrails: An Empirical Analysis of Evasion Attacks against Prompt Injection and Jailbreak Detection Systems**<br/>
William Hackett, Lewis Birch, Stefan Trawicki, Neeraj Suri and Peter Garraghan

**1-2-3 Check: Enhancing Contextual Privacy in LLM via Multi-Agent Reasoning**<br/>
Wenkai Li, Liwen Sun, Zhenxiang Guan, Xuhui Zhou and Maarten Sap

**Fine-Tuning Lowers Safety and Disrupts Evaluation Consistency**<br/>
Kathleen C. Fraser, Hillary Dawkins, Isar Nejadgholi and Svetlana Kiritchenko

**SPADE: Structured Prompting Augmentation for Dialogue Enhancement in Machine-Generated Text Detection**<br/>
Haoyi Li, Angela Yifei Yuan, Soyeon Caren Han and Chirstopher Leckie

**Weakest Link in the Chain: Security Vulnerabilities in Advanced Reasoning Models**<br/>
Arjun Krishna, Erick Galinkin and Aaditya Rastogi

**CAPTURE: Context-Aware Prompt Injection Testing and Robustness Enhancement**<br/>
Gauri Kholkar and Ratinder Ahuja

**Shortcut Learning in Safety: The Impact of Keyword Bias in Safeguards**<br/>
Panuthep Tasawong, Napat Laosaengpha, Wuttikorn Ponwitayarat, Sitiporn Sae Lim, Potsawee Manakul, Samuel Cahyawijaya, Can Udomcharoenchaikit, Peerat Limkonchotiwat, Ekapol Chuangsuwanich and Sarana Nutanong

**Beyond Words: Multilingual and Multimodal Red Teaming of MLLMs**<br/>
Erik Derner and Kristina Batistič



## Scope

Large Language Models accept a variety of inputs and produce a variety of outputs. It is possible to find inputs that lead to LLM outputs that model creators, owners, or users do not want. Defining and enumerating this space is an open task. We describe LLM security as the field of investigating how models that process text can, by an adversary, be made to behave in unintended and harmful ways. %The field covers both weaknesses and vulnerabilities.

Research at LLMSEC includes the entire life cycle of LLMs, from training data through fine-tuning and alignment over to inference-time. It also covers deployment context of LLMs, including risk assessment, release decisions, and use of LLMs in agent-based systems.

Event scope is LLM attacks, LLM defence,
and the contextualisation of LLM security. LLM
attacks are anything that causes LLMs to behave
in an unexpected/unintended manner usable by an
adversary. In the LLM life cycle, this includes
techniques like data poisoning and other model
supply chain attacks, as well as the adversarial
inputs that yield insecure outputs. Topics include:

* Adversarial attacks on LLMs
* Automated and adaptive LLM attacks
* Data poisoning
* Data extraction from trained models
* Defining LLM vulnerabilities
* Detection of adversarial LLM inputs
* Ethical aspects of LLM security
* Legal impacts and debates related to model security
* LLM Denial-of-service
* LLM security measurement
* LLM supply chain attacks
* Model input/output guardrails
* Model inversion
* Model policy
* Multi-modal and cross-model models (e.g. vision&text-to-text, text-to-speech, speech-to-text)
* Organising model exploits
* Organising model failure modes
* Practical tools for exploiting LLMs
* Privacy breaches mediated by LLM
* Privilege escalation and lateral movement mediated by LLMs
* Prompt injection
* Proofs-of-concept of LLM exploits
* Red teaming of LLMs
* Retrieval Augmented Generation security
* Secure LLM use and deployment


## Submission formats

Submissions must be anonymised & de-identified following ACL policy, and in the ACL template.

### Long & Short papers
We invite both short and long papers; short papers with a 4 page limit, long papers with an 8 page limit, with references,
ethics statements, & other compulsory sections not subjected to this limit.

### Qualitative work
As a relatively new field, still engaged in sense-making of the context of this research, we particularly welcome rigorous
qualitative work, and work that provides novel information about LLMSEC practice and context.

### War stories
Following cybersecurity tradition,
LLMSEC also welcomes "war stories", that is, accounts of security investigations or operations that are informative to broader audiences. 
These are intended to connect researchers and practitioners; LLM security is highly interdisciplinary and we have a lot to share with each other.

War story submissions need not provide novel quantitative empirical results, but should be illuminating and helpful to the workshop audience.
They may be up to four pages, with references, appendices, and compulsory sections excluded from the limit

### Submission link

Manage your submission via softconf: [https://softconf.com/acl2025/llmsec2025/](https://softconf.com/acl2025/llmsec2025/)

## Important Dates

* Pre-reviewed (ARR) submission deadline: March 25, 2025
* Direct submission deadline: April 15, 2025
* Notification of acceptance: May 17, 2025
* Camera-ready paper deadline: June 16, 2025
* Pre-recorded video due: July 5, 2025
* Workshop dates: July 31st / August 1st 2025

TZ: Anywhere on earth


## Co-ordinated disclosure

Works describing new ways of making models or other technologies behave in an unintended and potentially harmful way, e.g. papers documenting security vulnerabilities or weaknesses, may only be published at LLMSEC as part of co-ordinated disclosure. This requires that authors attempt to contact the technology developers first, and give a reasonable but limited amount of time for them to address the problem and notify their communities of the problem, before openly publishing the weakness anywhere. An example of the process is given in this [CISA blog post](https://www.cisa.gov/news-events/news/engaging-security-researchers-embracing-see-something-say-something-culture). 


## Organisation

**Leon Derczynski.** Principal Scientist in LLM Security at NVIDIA Corporation,
Associate Professor in NLP at ITU University
of Copenhagen, President of ACL SIGSEC. [https://www.linkedin.com/in/leon-derczynski/](https://www.linkedin.com/in/leon-derczynski/)

**Jekaterina Novikova.** Science Lead at the
AI Risk and Vulnerability Alliance (ARVA),
Expert Advisor of ACL SIGSEC. [https://jeknov.github.io/](https://jeknov.github.io/)

**Muhao Chen.** Assistant Professor of Computer Science at Uuniversity of California,
Davis, Secretary of ACL SIGSEC. Prof Chen
has considerable organisational and service experience, including SAC and AC at NAACL,
ACL, EMNLP, and AAAI, and co-chairing
workshops at NAACL 2022 and AKBC 2022.
[https://muhaochen.github.io/](https://muhaochen.github.io/)


## Committee

tba
