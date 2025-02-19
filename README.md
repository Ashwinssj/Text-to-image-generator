# Project Title: Text-to-Image Generation Using Stable Diffusion

## Short Description
This project implements a Text-to-Image Generator using the Stable Diffusion model, allowing users to generate high-quality images from textual descriptions. It leverages pre-trained deep learning models to create AI-generated images based on user-provided prompts. The project is designed with an interactive interface using Gradio, making it user-friendly for deployment and experimentation.

## Key Components Involved
### Programming Language
- Python

### Libraries Used
- **Gradio** – for building an interactive web-based interface
- **PIL (Pillow)** – for image processing
- **diffusers** – for accessing Stable Diffusion models
- **torch** – for deep learning computations
- **base64, io, os, IPython.display** – for handling image encoding and display

### Model Used
- Stable Diffusion from Hugging Face’s diffusers library

## Functionalities
- Accepts text prompts from users
- Uses Stable Diffusion to generate images based on the provided text
- Displays the generated image using Gradio for easy access
- Can be deployed as a web-based AI image generator
