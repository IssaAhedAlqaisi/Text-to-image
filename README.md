# Text-to-Image Generator using Stable Diffusion

This is a simple web app built with **Gradio** that uses **Hugging Face Diffusers** and **Stable Diffusion v1.5** to generate images from text prompts.

##  Features

- Text prompt input
- High-quality image generation with Stable Diffusion
- Runs on GPU for fast results
- Simple Gradio interface

##  Model Used

- **Stable Diffusion v1.5** (`runwayml/stable-diffusion-v1-5`)
- Powered by the  `diffusers` library

##  Demo

Launch the app on Google Colab to try it out , using T4 at least.

##  Installation

Make sure to install the required dependencies:

```bash
# Install required libraries
!pip install diffusers transformers accelerate scipy safetensors gradio --quiet
