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

ACL SIGSEC holds regular talks about current NLP & LLM Security research.

Subscribe to our talks calendar to stay up-to-date, via [Google calendar](https://calendar.google.com/calendar/u/0?cid=NjJiZDUyOWUxOTU1NWUyNmM0NTIzOWNjMDE3OTg3ZTc5ZmIyMjA1MzVjNDI3MTI3NzgzODI4NTVkMGQzNmNkZEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t) or [iCal](https://calendar.google.com/calendar/ical/62bd529e19555e26c45239cc017987e79fb220535c42712778382855d0d36cdd%40group.calendar.google.com/public/basic.ics).


## Upcoming


### Text Embeddings Reveal (Almost) As Much As Text

*2023, November 2nd, 10.00 ET / 16.00 CET*

**John X. Morris**

How much private information do text embeddings reveal about the original text? We investigate the problem of embedding *inversion*, reconstructing the full text represented in dense text embeddings. We frame the problem as controlled generation: generating text that, when reembedded, is close to a fixed point in latent space. We find that although a naïve model conditioned on the embedding performs poorly, a multi-step method that iteratively corrects and re-embeds text is able to recover 92% of 32-token text inputs exactly. We train our model to decode text embeddings from two state-of-the-art embedding models, and also show that our model can recover important personal information (full names) from a dataset of clinical notes.

Zoom link: [https://itucph.zoom.us/j/3319000227](https://itucph.zoom.us/j/3319000227)


### Privacy Side Channels in Machine Learning Systems

*2023, November 23rd, 11.00 ET / 17.00 CET*

**Edoardo Debenedetti**

Most current approaches for protecting privacy in machine learning (ML) assume that models exist in a vacuum, when in reality, ML models are part of larger systems that include components for training data filtering, output monitoring, and more. In this work, we introduce privacy side channels: attacks that exploit these system-level components to extract private information at far higher rates than is otherwise possible for standalone models. We propose four categories of side channels that span the entire ML lifecycle (training data filtering, input preprocessing, output post-processing, and query filtering) and allow for either enhanced membership inference attacks or even novel threats such as extracting users' test queries. For example, we show that deduplicating training data before applying differentially-private training creates a side-channel that completely invalidates any provable privacy guarantees. Moreover, we show that systems which block language models from regenerating training data can be exploited to allow exact reconstruction of private keys contained in the training set -- even if the model did not memorize these keys. Taken together, our results demonstrate the need for a holistic, end-to-end privacy analysis of machine learning.

Zoom link: [https://itucph.zoom.us/j/3319000227](https://itucph.zoom.us/j/3319000227)

## Past