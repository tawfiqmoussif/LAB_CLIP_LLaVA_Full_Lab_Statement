# CLIP & LLaVA — Multimodal AI Lab

## Overview

This project explores multimodal artificial intelligence using CLIP and LLaVA for image classification, image retrieval, image description, and visual question answering.

## Models

- **CLIP:** `openai/clip-vit-base-patch32`
- **LLaVA:** `llava-hf/llava-1.5-7b-hf`

## Experiments

1. CLIP zero-shot image classification
2. CLIP image-text similarity and image retrieval
3. Top-5 image retrieval
4. LLaVA image description and visual question answering
5. Visual hallucination analysis
6. CLIP vs LLaVA comparison
7. Interactive Multimodal Image Assistant

## Results

- **VQA accuracy:** 88% (22/25), based on manual evaluation.
- **Hallucination:** LLaVA invented the color and location of a nonexistent bicycle.
- **Mini-project:** An interactive image assistant was implemented using LLaVA.

## How to Run

1. Open the notebook in Google Colab.
2. Enable a GPU runtime.
3. Install the required dependencies.
4. Load the CLIP and LLaVA models.
5. Run the notebook cells in order.
6. Use the interactive image assistant to select an image and ask a question.

## Conclusion

CLIP demonstrated image classification and retrieval capabilities, while LLaVA enabled image description and visual question answering. The experiments also highlighted limitations such as visual hallucinations.