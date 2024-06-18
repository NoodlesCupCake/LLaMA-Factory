---
base_model: unsloth/Qwen2-7B-Instruct
library_name: peft
license: other
tags:
- llama-factory
- lora
- generated_from_trainer
model-index:
- name: qwen2-7b-instruct-lora-10-chunks-per-context-1-epoch
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# qwen2-7b-instruct-lora-10-chunks-per-context-1-epoch

This model is a fine-tuned version of [unsloth/Qwen2-7B-Instruct](https://huggingface.co/unsloth/Qwen2-7B-Instruct) on the 10-chunks-per-context-profession-accontants-standard dataset.

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
- train_batch_size: 2
- eval_batch_size: 8
- seed: 42
- gradient_accumulation_steps: 4
- total_train_batch_size: 8
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: cosine
- lr_scheduler_warmup_ratio: 0.1
- num_epochs: 1.0
- mixed_precision_training: Native AMP

### Training results



### Framework versions

- PEFT 0.11.1
- Transformers 4.41.2
- Pytorch 2.3.1+cu121
- Datasets 2.20.0
- Tokenizers 0.19.1