# Lightweight fine-tuning of a GPT2 model

- Applying parameter-efficient fine-tuning using the Hugging Face `peft` library.
- Hugging Face PEFT allows fine-tuning a model without having to fine-tune all of its parameters.
- Training a model using Hugging Face PEFT requires two additional steps beyond traditional fine-tuning
    1. Creating a PEFT config
    2. Converting the model into a PEFT model using the PEFT config

Inference using a PEFT model is almost identical to inference using a non-PEFT model. THe only difference is that it must be loaded as a PEFT model.

