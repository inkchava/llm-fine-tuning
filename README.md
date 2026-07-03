# LLM Fine-Tuning & Evaluation with Qwen2.5

An end-to-end project exploring supervised fine-tuning of an instruction-tuned large language model using the Hugging Face ecosystem. This project fine-tunes **Qwen2.5-0.5B-Instruct** on multiple-choice machine learning questions and evaluates model performance before and after training.

## Project Overview

Large language models can be adapted to specialized domains through supervised fine-tuning. This project demonstrates the complete workflow of preparing training data, fine-tuning an open-source LLM, running inference, and benchmarking model performance.

The primary objective was to improve performance on domain-specific machine learning questions while understanding the trade-offs between specialization and generalization.

## Technologies

* Python
* PyTorch
* Hugging Face Transformers
* TRL (SFTTrainer)
* Pandas

## Pipeline

1. Prepared multiple-choice datasets in instruction-style chat format.
2. Fine-tuned **Qwen2.5-0.5B-Instruct** using supervised instruction tuning.
3. Built an inference pipeline for model evaluation.
4. Benchmarked model performance before and after fine-tuning using accuracy-based evaluation.
5. Generated predictions for downstream evaluation tasks.

## Key Learning Outcomes

* Instruction tuning of open-source LLMs
* End-to-end model training and evaluation
* Transformer fine-tuning with Hugging Face
* Prompt formatting for conversational models
* Performance benchmarking and error analysis

## Repository Structure

```
├── notebook.ipynb          # Fine-tuning workflow
├── data/                   # Training and evaluation datasets
├── outputs/                # Saved checkpoints and predictions
└── README.md
```

## Future Improvements

* Compare supervised fine-tuning with parameter-efficient methods such as LoRA.
* Evaluate catastrophic forgetting using broader benchmark datasets.
* Experiment with prompt engineering and inference-time decoding strategies.
* Expand evaluation beyond accuracy to include robustness and generalization.

## Acknowledgements

This project was completed as part of UC Berkeley coursework and extends a provided instructional framework through model training, evaluation, and experimentation.
