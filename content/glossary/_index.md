---
# Title, summary, and page position.
title: LLMSEC Glossary
linktitle: Glossary
summary: 
weight: 100
# icon: book
# icon_pack: fas

# Page metadata.
date: '2024-11-22T00:00:00Z'
toc: false
---

## AI Red Teaming

Systematically testing AI models and systems containing AI models to identify vulnerabilities, biases, and behaviors that pose threats or risks to the systems running or using those models.  It can be subdivided into two areas:
* Security Red Teaming: Assessing the robustness of the model and the system containing the model to attacks impacting traditional security properties (e.g., confidentiality, integrity, availability), either of the model itself or the system containing the model.  Attacks such as adversarial inputs, model extraction, training data inference and extraction, or prompt injection as used to violate a security property are typically evaluated by a security red team. These activities typically require teams with a traditional security background to leverage findings and evaluate their impact.
* Content-based Red Teaming: Assessing the model for unwanted behavior under adversarial manipulation, producing outputs that violate some pre-specified behavior contract for the model, either explicit (e.g., model card) or implicit. These behaviors may include outputs that are offensive, unwanted, or unsafe, including biased or racist productions, instructions on unsafe or illegal activities, making promises on behalf of the model owner, or making decisions based on protected characteristics.  Common techniques involve various forms of jailbreaking and guardrail evasion.  These activities typically require the support of an ethics team, a legal team, or other similar domain experts to assess the impact of findings.
Care should be taken to specify the specific subdomain of "Red Teaming": different audiences will often make different assumptions about which form is being referred to.