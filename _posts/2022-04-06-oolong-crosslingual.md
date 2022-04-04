---
layout: post
title: Oolong: Investigating What Makes Crosslingual Transfer Hard with Controlled Studies

---
**When**:  Wednesday, 6th of April, 09:00 AM

**Where**: [https://meet.google.com/bhq-joiu-bhh](https://meet.google.com/bhq-joiu-bhh)

**Topic**: Oolong: Investigating What Makes Crosslingual Transfer Hard with Controlled Studies

           
### Recommended Readings
- [Oolong: Investigating What Makes Crosslingual Transfer Hard with Controlled Studies](https://arxiv.org/pdf/2202.12312.pdf) Zhengxuan Wu, Isabel Papadimitriou, Alex Tamkin, February 2022


### Abstract
Little is known about what makes cross-lingual transfer hard, since factors like tokenization, morphology, and syntax all change at once between languages. To disentangle the impact of these factors, we propose a set of controlled transfer studies: we systematically transform GLUE tasks to alter different factors one at a time, then measure the resulting drops in a pretrained model's downstream performance. In contrast to prior work suggesting little effect from syntax on knowledge transfer, we find significant impacts from syntactic shifts (3-6% drop), though models quickly adapt with continued pretraining on a small dataset. However, we find that by far the most impactful factor for crosslingual transfer is the challenge of aligning the new embeddings with the existing transformer layers (18% drop), with little additional effect from switching tokenizers (<2% drop) or word morphologies (<2% drop). Moreover, continued pretraining with a small dataset is not very effective at closing this gap - suggesting that new directions are needed for solving this problem.
