# Prodigy InfoTech Internship - Machine Learning Tasks

This repository contains all completed tasks for the **Prodigy InfoTech Machine Learning Internship** track.

## Repository Overview

| Task ID | Task Description | Model / Framework | File |
| :--- | :--- | :--- | :--- |
| **Prodigy_ML_01** | Text Generation | GPT-2 (Hugging Face) | `task1_gpt2.py` |
| **Prodigy_ML_02** | Text-to-Image Generation | Stable Diffusion v1.5 | `task2_image_gen.py` |
| **Prodigy_ML_03** | Markov Chain Text Generation | Markovify | `task3_markov_chain.py` |
| **Prodigy_ML_04** | Text Summarization | BART (`facebook/bart-large-cnn`) | `task4_summarization.py` |
| **Prodigy_ML_05** | Neural Style Transfer | VGG19 (PyTorch) | `task5_style_transfer.py` |

---

## Detailed Task Summaries

### Task 01: Text Generation with GPT-2
- **Objective:** Generate coherent text sequences given an input prompt.
- **Implementation:** Leverages pre-trained Hugging Face GPT-2 with top-k and top-p (nucleus) sampling techniques to produce natural language continuations.

### Task 02: Image Generation with Pre-trained Models
- **Objective:** Generate synthetic images from natural language text prompts.
- **Implementation:** Uses Stable Diffusion v1.5 via `diffusers` in PyTorch to construct 512x512 digital artwork.

### Task 03: Text Generation with Markov Chains
- **Objective:** Implement a lightweight statistical model to generate synthetic text.
- **Implementation:** Utilizes `markovify` to build word transition probability matrices over a sample training corpus.

### Task 04: Abstractive Text Summarization
- **Objective:** Summarize lengthy input text into concise, human-readable summaries.
- **Implementation:** Uses sequence-to-sequence BART transformer models via Hugging Face `transformers`.

### Task 05: Neural Style Transfer
- **Objective:** Transfer the artistic texture and color palette of a style image onto a target content image.
- **Implementation:** Implements feature extraction and loss optimization using a pre-trained VGG19 backbone in PyTorch.

---

## Installation & Setup

Install all required dependencies across all tasks using:

```bash
pip install torch torchvision transformers diffusers accelerate markovify pillow
