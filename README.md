# Image Outpainting Project

This project represents my exploration into image outpainting using the Stable Diffusion Inpainting model. As a student learning about AI-powered image manipulation, I developed this script to extend the borders of an input image while maintaining its style and atmosphere.

## Project Overview

- Downloads an image from Google Drive
- Resizes the image for processing
- Creates an extended canvas and mask for outpainting
- Utilizes the Stable Diffusion Inpainting model for generating new content
- Displays and saves the outpainted result

## Requirements

- Python 3.7+
- PyTorch
- Diffusers
- Transformers
- PIL (Python Imaging Library)
- Matplotlib
- gdown

## How I Built This

1. I started by setting up the necessary imports and downloading the target image.
2. I resized the original image to 512x512 to manage memory usage.
3. I created an extended canvas and a mask for the outpainting areas.
4. I used the "runwayml/stable-diffusion-inpainting" model for the outpainting process.
5. I crafted a detailed prompt to guide the outpainting, describing the scene elements.
6. I set the inference steps to 50 and the guidance scale to 7.5 after experimentation.

## Challenges and Learnings

- I encountered difficulties in achieving a natural extension of the image.
- I learned that outpainting quality can vary significantly based on the prompt and parameters.
- I discovered the importance of balancing inference steps and guidance scale for better results.

## Future Improvements

- Experiment with different models like "stabilityai/stable-diffusion-2-inpainting"
- Try gradual outpainting (one side at a time) for potentially better results
- Implement post-processing techniques to enhance blending

## Note

This project is part of my learning journey in AI and image processing. The results may not always be perfect, and further refinement of the technique is an ongoing process.

## Personal Use

This code is for my personal learning and experimentation. It's not licensed for distribution or commercial use. If you're a fellow student or researcher interested in this work, please reach out to me directly for any questions or collaborations.
