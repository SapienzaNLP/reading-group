---
layout: post
title: Fixed Encoder Self-Attention Patterns in Transformer-Based Machine Translation
---
**When**:  Wednesday 25th of November, 09:00 AM

**Where**: Meet, check the address in the Google Calendar Event.

**Topic**: Attention
           
**Speaker**: 
[Alessandro Raganato](https://raganato.github.io/)

### Material
- [Slides](https://sapienzanlp.github.io/reading-group/material/2020-11-25-fixed-attention/Fixed Attention presentation - SapienzaNLP reading group.pdf)
- [Presentation](https://drive.google.com/file/d/1AaQdITRmOyQ_8xa94CtCFa7cV1v6v1Zq/view?usp=sharing)


### Abstract
Transformer-based models have brought a radical change to neural machine translation. A key feature of the Transformer architecture is the so-called multi-head attention mechanism, which allows the model to focus simultaneously on different parts of the input. However, recent works have shown that most attention heads learn simple, and often redundant, positional patterns. In this paper, we propose to replace all but one attention head of each encoder layer with simple fixed -- non-learnable -- attentive patterns that are solely based on position and do not require any external knowledge. Our experiments with different data sizes and multiple language pairs show that fixing the attention heads on the encoder side of the Transformer at training time does not impact the translation quality and even increases BLEU scores by up to 3 points in low-resource scenarios.


