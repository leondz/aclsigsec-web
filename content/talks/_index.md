---
# Title, summary, and page position.
title: SIGSEC talks
linktitle: Talks
summary: Talks on NLP & LLM Security
weight: 2
# icon: book
# icon_pack: fas

# Page metadata.
date: '2018-09-09T00:00:00Z'
toc: false
---

ACL SIGSEC holds regular talks about current NLP & LLM Security research. You can find all the prior talks on the [ACL SIGSEC YouTube channel](https://www.youtube.com/@ACLSIGSEC).

Subscribe to our talks calendar to stay up-to-date, via [Google calendar](https://calendar.google.com/calendar/u/0?cid=NjJiZDUyOWUxOTU1NWUyNmM0NTIzOWNjMDE3OTg3ZTc5ZmIyMjA1MzVjNDI3MTI3NzgzODI4NTVkMGQzNmNkZEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t) or [iCal](https://calendar.google.com/calendar/ical/62bd529e19555e26c45239cc017987e79fb220535c42712778382855d0d36cdd%40group.calendar.google.com/public/basic.ics).




## Upcoming

### Robust and Context-Faithful Language Understanding with (Large) Language Models

*2024, January 25th, 13.00 ET / 19.00 CET*

**Fei Wang** 

[https://feiwang96.github.io/](https://feiwang96.github.io/)

Large language models (LLMs) have achieved remarkable success in various language understanding tasks. However, their deployment in real-world scenarios raises significant accountability concerns. In this presentation, I will introduce our recent work on enhancing contextual faithfulness and robustness of LLMs. First, LLMs often make unfaithful predictions based on entity mentions or parametric knowledge, ignoring the context. I will present causality-driven approaches, including training-time and in-context causal intervention, to mitigate entity bias for both black-box and white-box LLMs. Second, LLMs may capture various unreliable prediction shortcuts, some of which could be unknown. I will demonstrate how to address this issue by proactively mitigating biases in the attention module without needing to identify the specific cause of the bias. Finally, I will outline future directions for advancing accountable and responsible LLMs.

Zoom: [https://itucph.zoom.us/j/3319000227](https://itucph.zoom.us/j/3319000227)


## Previous SIGSEC Talks

### vec2text: Text Embeddings Reveal (Almost) As Much As Text

*2023, November 2nd, 10.00 ET / 15.00 CET*

**Jack Morris**

How much private information do text embeddings reveal about the original text? We investigate the problem of embedding *inversion*, reconstructing the full text represented in dense text embeddings. We frame the problem as controlled generation: generating text that, when reembedded, is close to a fixed point in latent space. We find that although a naïve model conditioned on the embedding performs poorly, a multi-step method that iteratively corrects and re-embeds text is able to recover 92% of 32-token text inputs exactly. We train our model to decode text embeddings from two state-of-the-art embedding models, and also show that our model can recover important personal information (full names) from a dataset of clinical notes.

Video: [https://www.youtube.com/watch?v=4ZQLM2Pg0dE](https://www.youtube.com/watch?v=4ZQLM2Pg0dE)

arXiv: [https://arxiv.org/abs/2310.06816](https://arxiv.org/abs/2310.06816)


### LLM-Deliberation: Evaluating LLMs with Interactive Multi-Agent Negotiation Games

*2023, November 9th, 11.00 ET / 17.00 CET*

**Sahar Abdelnabi**

There is a growing interest in using Large Language Models (LLMs) as agents to tackle real-world tasks that may require assessing complex situations. Yet, we have a limited understanding of LLMs' reasoning and decision-making capabilities, partly stemming from a lack of dedicated evaluation benchmarks. As negotiating and compromising are key aspects of our everyday communication and collaboration, we propose using scorable negotiation games as a new evaluation framework for LLMs. We create a testbed of diverse text-based, multi-agent, multi-issue, semantically rich negotiation games, with easily tunable difficulty. To solve the challenge, agents need to have strong arithmetic, inference, exploration, and planning capabilities, while seamlessly integrating them. Via a systematic zero-shot Chain-of-Thought prompting (CoT), we show that agents can negotiate and consistently reach successful deals. We quantify the performance with multiple metrics and observe a large gap between GPT-4 and earlier models. Importantly, we test the generalization to new games and setups. Finally, we show that these games can help evaluate other critical aspects, such as the interaction dynamics between agents in the presence of greedy and adversarial players.

Video [https://www.youtube.com/watch?v=OAXUkjd7mec](https://www.youtube.com/watch?v=OAXUkjd7mec)

arXiv: [https://arxiv.org/abs/2309.17234](https://arxiv.org/abs/2309.17234)


### Privacy Side Channels in Machine Learning Systems

*2023, December 18th, 11.00 ET / 17.00 CET*

**Edoardo Debenedetti**

Most current approaches for protecting privacy in machine learning (ML) assume that models exist in a vacuum, when in reality, ML models are part of larger systems that include components for training data filtering, output monitoring, and more. In this work, we introduce privacy side channels: attacks that exploit these system-level components to extract private information at far higher rates than is otherwise possible for standalone models. We propose four categories of side channels that span the entire ML lifecycle (training data filtering, input preprocessing, output post-processing, and query filtering) and allow for either enhanced membership inference attacks or even novel threats such as extracting users' test queries. For example, we show that deduplicating training data before applying differentially-private training creates a side-channel that completely invalidates any provable privacy guarantees. Moreover, we show that systems which block language models from regenerating training data can be exploited to allow exact reconstruction of private keys contained in the training set -- even if the model did not memorize these keys. Taken together, our results demonstrate the need for a holistic, end-to-end privacy analysis of machine learning.

Video: [https://www.youtube.com/watch?v=LtJ7vSMWjJA](https://www.youtube.com/watch?v=LtJ7vSMWjJA)

arXiv: [https://arxiv.org/abs/2309.05610](https://arxiv.org/abs/2309.05610)


### New Important Instructions: Real-world exploits and mitigations in LLM Apps

*2024, January 11th, 11.00 ET / 17.00 CET*

**Johann Rehberger ([@wunderwuzzi23](https://twitter.com/wunderwuzzi23/))**

_Blog: [embracethered.com](https://embracethered.com)_

With the wide-spread rollout of Chatbots and LLM applications users are facing increased risks of scams, data exfiltration, loss of PII, and even remote code execution when processing untrusted data with LLM apps. This presentation will cover many demonstrations of real-world exploits in prominent LLM apps, such as automatic plugin/tool invocation and data exfiltration in ChatGPT, data exfiltration in Bing Chat, Anthropic Claude and Google Bard. The talk also highlights approaches vendors have taken to fix vulnerabilities. Finally, we also take a look how it is possible to use ChatGPT Builder to create a malicious GPT, while seemingly benign, is tricking users and stealing data.

Video: [https://www.youtube.com/watch?v=slIVToAG98M](https://www.youtube.com/watch?v=slIVToAG98M)

