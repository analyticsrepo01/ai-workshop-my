# Image Generation with Imagen on Vertex AI

This README provides an overview of the image generation capabilities using Imagen on Vertex AI, as demonstrated in the `part_Imagen.ipynb` notebook.

## Overview

[Imagen on Vertex AI](https://cloud.google.com/vertex-ai/docs/generative-ai/image/overview) allows application developers to leverage Google's state-of-the-art generative AI to create high-quality visual assets from text prompts. With Imagen, you can:

- Generate novel images from text prompts (text-to-image).
- Edit and upscale existing images.
- Fine-tune models for specific subjects.
- Get text descriptions of images (visual captioning).
- Answer questions about images (Visual Question Answering).

This notebook focuses specifically on **image generation**.

## Objectives

The `part_Imagen.ipynb` notebook explores the image generation features of Imagen using the Vertex AI Python SDK. The main objectives are:

- Generate images using text prompts.
- Experiment with different parameters to influence the output, including:
    - Increasing the number of images generated.
    - Fixing a seed for reproducibility.
    - Using negative prompts to exclude objects.

## Key Features Demonstrated

The notebook demonstrates the following key features:

- **Text-to-Image Generation:** Generating images from simple text prompts.
- **Parameter Exploration:**
    - `number_of_images`: Generating multiple images at once.
    - `seed`: Ensuring reproducibility of results.
    - `negative_prompt`: Excluding specific objects from the generated images.

## Getting Started

For detailed instructions and code examples, please refer to the `part_Imagen.ipynb` notebook.
