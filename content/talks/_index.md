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

### Evolving Perceptions and Mitigation of Toxicity in Language Models

*2023, November 30rd, 10.00 ET / 16.00 CET*

**Beyza Ermis**

This two-part talk delves into the dynamic nature of toxicity perception and mitigation in automated systems. The first segment of the talk examines how the evolving standards of what constitutes 'toxic' content, influenced by cultural and geographic diversity, impacts the reproducibility of research findings in toxicity detection models. By re-evaluating widely recognized benchmark models from the HELM project with the latest version of a commercial toxicity detection API, we uncover shifts in model rankings, challenging prior comparative studies. These findings underscore the need for caution in direct comparisons and advocate for a structured, time-conscious framework in assessing toxicity detection models.

The second segment introduces a novel, retrieval-based methodology for toxicity mitigation in text generation models. This method represents a significant stride forward, not only matching the mitigation effectiveness of state-of-the-art models but also emphasizing efficiency. This approach is designed to adapt to the fluid nature of language, offering a more sustainable solution that accommodates the continuous evolution of language use in real-world scenarios.

Zoom link: [https://itucph.zoom.us/j/3319000227](https://itucph.zoom.us/j/3319000227)



### Privacy Side Channels in Machine Learning Systems

*2023, December 7th, 11.00 ET / 17.00 CET*

**Edoardo Debenedetti**

Most current approaches for protecting privacy in machine learning (ML) assume that models exist in a vacuum, when in reality, ML models are part of larger systems that include components for training data filtering, output monitoring, and more. In this work, we introduce privacy side channels: attacks that exploit these system-level components to extract private information at far higher rates than is otherwise possible for standalone models. We propose four categories of side channels that span the entire ML lifecycle (training data filtering, input preprocessing, output post-processing, and query filtering) and allow for either enhanced membership inference attacks or even novel threats such as extracting users' test queries. For example, we show that deduplicating training data before applying differentially-private training creates a side-channel that completely invalidates any provable privacy guarantees. Moreover, we show that systems which block language models from regenerating training data can be exploited to allow exact reconstruction of private keys contained in the training set -- even if the model did not memorize these keys. Taken together, our results demonstrate the need for a holistic, end-to-end privacy analysis of machine learning.

Zoom link: [https://itucph.zoom.us/j/3319000227](https://itucph.zoom.us/j/3319000227)




### vec2text: Text Embeddings Reveal (Almost) As Much As Text

*2023, November 2nd, 10.00 ET / 15.00 CET*

**Jack**

How much private information do text embeddings reveal about the original text? We investigate the problem of embedding *inversion*, reconstructing the full text represented in dense text embeddings. We frame the problem as controlled generation: generating text that, when reembedded, is close to a fixed point in latent space. We find that although a naïve model conditioned on the embedding performs poorly, a multi-step method that iteratively corrects and re-embeds text is able to recover 92% of 32-token text inputs exactly. We train our model to decode text embeddings from two state-of-the-art embedding models, and also show that our model can recover important personal information (full names) from a dataset of clinical notes.

Video: [https://www.youtube.com/watch?v=4ZQLM2Pg0dE](https://www.youtube.com/watch?v=4ZQLM2Pg0dE)


### LLM-Deliberation: Evaluating LLMs with Interactive Multi-Agent Negotiation Games

*2023, November 9th, 11.00 ET / 17.00 CET*

**Sahar Abdelnabi**

There is a growing interest in using Large Language Models (LLMs) as agents to tackle real-world tasks that may require assessing complex situations. Yet, we have a limited understanding of LLMs' reasoning and decision-making capabilities, partly stemming from a lack of dedicated evaluation benchmarks. As negotiating and compromising are key aspects of our everyday communication and collaboration, we propose using scorable negotiation games as a new evaluation framework for LLMs. We create a testbed of diverse text-based, multi-agent, multi-issue, semantically rich negotiation games, with easily tunable difficulty. To solve the challenge, agents need to have strong arithmetic, inference, exploration, and planning capabilities, while seamlessly integrating them. Via a systematic zero-shot Chain-of-Thought prompting (CoT), we show that agents can negotiate and consistently reach successful deals. We quantify the performance with multiple metrics and observe a large gap between GPT-4 and earlier models. Importantly, we test the generalization to new games and setups. Finally, we show that these games can help evaluate other critical aspects, such as the interaction dynamics between agents in the presence of greedy and adversarial players.

Video [https://www.youtube.com/watch?v=OAXUkjd7mec](https://www.youtube.com/watch?v=OAXUkjd7mec)


