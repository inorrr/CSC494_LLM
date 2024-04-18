---
language:
- de
- en
tags:
- generated_from_trainer
datasets:
- iwslt2017
model-index:
- name: temp
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# temp

This model is a fine-tuned version of [bild](https://huggingface.co/bild) on the iwslt2017 iwslt2017-de-en dataset.
It achieves the following results on the evaluation set:
- eval_loss: 1.0805
- eval_bleu: 34.4194
- eval_gen_len: 27.5259
- eval_runtime: 649.726
- eval_samples_per_second: 1.367
- eval_steps_per_second: 1.367
- step: 0

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 8
- eval_batch_size: 1
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 3.0

### Framework versions

- Transformers 4.25.0.dev0
- Pytorch 2.2.1+cu121
- Datasets 2.17.1
- Tokenizers 0.13.3
