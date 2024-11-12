---
title: "Machine Learning and: You A Whirlwind Tour"
sub_title: “Original Workshop at Access Conference in Canada"
author: John Fink, Tim Ribaric
---

AI Workshop
---


<!-- end_slide -->

Why Care About Local?
---


# Privacy

<!-- pause -->

# Environmental

<!-- pause -->

# Cost

<!-- end_slide -->

Attention is All You Need
---

Seminal Paper that introduces the Transformer Architecture which is what the rest of the Workshop will be about. 

```
https://arxiv.org/abs/1706.03762
```

<!-- pause —> 

<!-- end_slide -->

Attention is All You Need
---

Key points from the paper: 

## Attention Mechanism: A way to weigh the importance of different parts of an input sequence when processing a specific part

<!-- pause -->

## Transformer Architecture: A sequence-to-sequence model that uses self-attention to relate different positions of an input sequence

<!-- pause -->

## No recurrent neural networks (RNN) or convolutional neural networks (CNN). Relies solely on self-attention. This eliminates the need for recurrent or convolutional operations

<!-- pause -->

## Parallel computation: The transformer allows for parallel computation making it more efficient than RNN-based models

<!-- end_slide -->

Important Concepts from transformer based models
---

### Context Window and Tokens

### Temperature

### Training

### Parameters

### The Random Seed

### The Prompt aka “Programming for English Majors"

<!-- pause -->

<!-- end_slide -->

Important Concepts from transformer based models
---

### Context Window and Tokens

<!-- pause -->

Context Window is the “memory” of an LLM 

<!-- pause -->

And Tokens — words, roughly — fill up that “memory"

And the response also takes tokens

<!-- pause -->

<!-- end_slide -->

Important Concepts from transformer based models
---

### Temperature

<!-- pause -->

The “entropy” of a model’s response.

Low temperature tend towards predictable and repetitive.

High temperature makes models get … goofy

<!-- pause -->

<!-- end_slide -->

Important Concepts from transformer based models
---

### Training

Usually done on text corpuses.

The Pile (825GiB), GitHub, ShareGPT etc.,

**cough** books, others

The larger the model, the more resources needed to train or retrain 

<!-- pause -->

<!-- end_slide -->

Important Concepts from transformer based models
---

### Parameters

Very roughly corresponds to how “Complex” or “Smart” a model is

Generally the higher the number the more complex it is and typically is shrouded in mystery for competitive reasons

<!-- pause -->

Smaller modules are amusing and funny 

#### What is Quantization

<!-- pause -->

This is analogous to FLAC -> mp3 that allows us to have this workshop

<!-- end_slide -->

Important Concepts from transformer based models
---

### The Random Seed