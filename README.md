---
license: cc-by-sa-4.0
base_model: klue/bert-base
tags:
- generated_from_trainer
metrics:
- accuracy
model-index:
- name: dummy-kosts
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# dummy-kosts

This model is a fine-tuned version of [klue/bert-base](https://huggingface.co/klue/bert-base) on [klue/ynat](https://huggingface.co/datasets/klue/viewer/ynat).
It achieves the following results on the evaluation set:
- Loss: 0.6433
- Accuracy: 0.8642

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 8
- eval_batch_size: 8
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 3.0

### Training results

| Training Loss | Epoch | Step  | Validation Loss | Accuracy |
|:-------------:|:-----:|:-----:|:---------------:|:--------:|
| 0.4139        | 1.0   | 5710  | 0.4763          | 0.8528   |
| 0.3358        | 2.0   | 11420 | 0.5527          | 0.8650   |
| 0.2045        | 3.0   | 17130 | 0.6433          | 0.8642   |


### Framework versions

- Transformers 4.35.2
- Pytorch 2.1.0+cu121
- Datasets 2.16.1
- Tokenizers 0.15.1
