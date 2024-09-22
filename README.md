# Stable Diffusion Image Generation with Transformers


## Overview
This project utilizes Stable Diffusion and Transformers to generate images from text prompts. Built on the Stable Diffusion v2 model by Stability AI, it uses GPU acceleration for efficient image generation. The project includes a custom model pipeline that integrates prompt generation, image customization, and parameter control, all designed to produce high-quality, AI-generated visuals.


## Key Features
**Text-to-Image Generation:** Generates images based on text descriptions using Stable Diffusion.

**GPU Support:** Enhanced performance by leveraging CUDA for faster model inference.

**Customizable Settings:** Allows users to configure parameters such as the number of image generation steps, guidance scale for creativity, and output image size.


## Tools & Libraries
**Stable Diffusion Pipeline:** From Hugging Face’s Diffusers for generating images.

**Transformers Library:** For model management and prompt generation using GPT-2.

**PyTorch:** Used for neural network computations and GPU acceleration.


## How It Works
**Model Setup:** The Stable Diffusion model is loaded and set up with customizable parameters such as guidance scale, image size, and inference steps to control the output’s creativity and precision.

**Text Prompting:** Users provide a simple text prompt (e.g., "A butterfly on a flower"), which the model uses to generate a corresponding image.

**Image Generation:** The model processes the text prompt through the Stable Diffusion pipeline, producing a high-quality image that matches the input description. The resulting image is resized and saved as per user preferences.


## Installation & Usage
To use the project, install the required libraries, set up the model, and provide a text prompt. The system will generate an image based on the given text description and display or save the output.
