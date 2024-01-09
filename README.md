# ELECTRA-Small Fine-Tuning for Adversarial SQuAD

This repository documents the fine-tuning of the ELECTRA-Small model for question answering using the Adversarial SQuAD dataset. The objective was to enhance the model's performance on challenging examples by incorporating adversarial instances during training.

## Project Overview

The primary goal was to improve the ELECTRA-Small model's question-answering capabilities, especially when encountering misleading or adversarial text. By combining the original SQuAD dataset with various amounts of adversarial examples, the project aimed to train a more robust model capable of discerning between correct and distractor contexts.

## Key Insights

- **Background**: Identified the challenge of adversarial text within the Adversarial SQuAD dataset and its impact on language understanding models.
- **Approach**: Outlined the methodology, incorporating adversarial examples into training and evaluating model performance on both SQuAD and Adversarial SQuAD datasets.
- **Results**: Highlighted a notable improvement of up to 8 points in EM and F1 scores on the Adversarial SQuAD evaluation split after fine-tuning the model with increasing amounts of adversarial examples.
- **Conclusions**: Demonstrated that integrating adversarial examples during training reduced model susceptibility to misleading contexts. However, acknowledged the need for more diverse datasets for better generalization.


## Conclusion

The project's fine-tuning approach significantly improved the ELECTRA-Small model's performance on challenging examples present in the Adversarial SQuAD dataset. However, future research integrating diverse datasets could further enhance the model's adaptability across various linguistic nuances and contexts.
