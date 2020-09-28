---
layout: post
title: A Brief Talk on the Importance of Natural Language Processing in Biomedicine.
---
**When**:  Wednesday 30th of September, 9:00 AM

**Where**: Meet, check the address in the Google Calendar Event.

**Topic**:Encoder decoder, a.k.a. where copying isn’t cheating (even on the test set)

**Speaker**: 
[Luigi Procopio](https://twitter.com/luigi_proc)

### Abstract
Quite often, in generation tasks, a part of the output sequence we seek to generate can actually be found in the input 
itself. Leveraging this property is exactly what copying mechanisms in encoder-decoder architectures strive to do, 
augmenting models with the capability to copy parts of the input into the output. These techniques provide an 
interesting strategy to tackle a frequent type of OOV-s, i.e. those that appear in the input sequence (named entities, 
rare words, just to name a few), and they are a natural fit for many generation tasks (such as text correction and 
abstractive summarization) where the output is intrinsically related to the input.
In this talk, we are going to give an overview of this framework, focusing on arguably its 2 major approaches 
(CopyNet-s and Pointer-Generator networks), discussing in detail some of the subtleties that come with their 
implementation and presenting two recent works that try to tackle their shortcomings.


### Recommended Readings
- [Incorporating Copying Mechanism in Sequence-to-Sequence Learning](https://arxiv.org/pdf/1603.06393.pdf)
- [Get To The Point: Summarization with Pointer-Generator Networks](https://arxiv.org/pdf/1704.04368.pdf)
- [Sequential Copying Networks](https://arxiv.org/pdf/1807.02301.pdf)
- [Copy that! Editing Sequences by Copying Spans](https://arxiv.org/pdf/2006.04771.pdf)

### Questioners:
- Caterina Lacerra
- Federico Martelli
- Marco Maru