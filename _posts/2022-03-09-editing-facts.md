---
layout: post
title: Editing Factual Knowledge in Language Models

---
**When**:  Wednesday, 9th of March, 09:00 AM

**Where**: [https://meet.google.com/bhq-joiu-bhh](https://meet.google.com/bhq-joiu-bhh)

**Topic**: Editing Factual Knowledge in Language Models

           
### Recommended Readings
- [Editing Factual Knowledge in Language Models](https://arxiv.org/abs/2104.08164) Nicola De Cao, Wilker Aziz, Ivan Titov, April 2021


### Abstract
**(tl;dr how do you remove/edit knowledge in a pretrained LM? You predict a weight update with another network)**
We present KnowledgeEditor, a method that can be used to edit this knowledge and, thus, fix 'bugs' or unexpected predictions without the need for expensive re-training or fine-tuning. In our approach, we train a hyper-network with constrained optimization to modify a fact without affecting the rest of the knowledge; the trained hyper-network is then used to predict the weight update at test time. We show KnowledgeEditor's efficacy with two popular architectures and knowledge-intensive tasks: i) a BERT model fine-tuned for fact-checking, and ii) a sequence-to-sequence BART model for question answering. With our method, changing a prediction on the specific wording of a query tends to result in a consistent change in predictions also for its paraphrases. We show that this can be further encouraged by exploiting (e.g., automatically-generated) paraphrases during training. Interestingly, our hyper-network can be regarded as a 'probe' revealing which components of a model need to be changed to manipulate factual knowledge; our analysis shows that the updates tend to be concentrated on a small subset of components.

## Material
- [Slides](https://sapienzanlp.github.io/reading-group/material/2022-03-09-editing-facts/Reading Group - Editing LM.pdf)
- [Presentation](https://drive.google.com/file/d/1XVtSx7c2uvFuRUB57HSkIbvZtLnyT1kO/view?usp=sharing)
