# Generative Models for Vision

## Project Overview

This project explores diffusion-based generative models for image creation and editing using Stable Diffusion. Through a series of controlled experiments, I examined how different generation settings affect image quality, prompt accuracy, reproducibility, and visual consistency.

The project also includes image-to-image editing using a personal photograph and an experiment demonstrating a common limitation of diffusion models: difficulty following exact counting instructions.

This project was completed as part of **ITAI 1378 – Computer Vision** at **Houston City College**.

---

## Objectives

- Understand how diffusion models generate images.
- Explore the effects of guidance scale, inference steps, and random seeds.
- Use negative prompts to reduce unwanted image artifacts.
- Perform image-to-image editing using an original photograph.
- Evaluate a known limitation of diffusion models.
- Practice controlled experimentation by changing one parameter at a time.

---

## Technologies Used

- Python
- PyTorch
- Hugging Face Diffusers
- Stable Diffusion v1.5
- Pillow
- Matplotlib
- Google Colab

---

## Techniques Implemented

- Text-to-Image Generation
- Prompt Engineering
- Guidance Scale Tuning
- Inference Step Comparison
- Random Seed Control
- Negative Prompting
- Image-to-Image Editing
- Reproducible Generation
- Model Limitation Analysis

---

## Experiments

### Guidance Scale Sweep

Generated images using guidance values of **3, 7, and 12** while keeping the prompt, seed, and number of steps fixed.

This experiment showed how higher guidance values make the model follow the prompt more closely, while lower guidance values allow more creative variation.

### Inference Steps Sweep

Compared images generated using **10, 25, and 50 inference steps**.

The results showed that increasing the number of steps improved image detail, but the difference between 25 and 50 steps was smaller than the difference between 10 and 25.

### Random Seed Comparison

Generated multiple images using the same prompt and settings but different random seeds.

This demonstrated that the seed controls the starting noise and produces different image compositions while preserving the same general prompt.

### Negative Prompt Experiment

Compared image generation with and without the following negative prompt:

`blurry, low quality, watermark, text, extra objects`

The negative prompt helped reduce unwanted artifacts and produced a cleaner image.

### Image-to-Image Editing

Used an original beach photograph and transformed it into a tropical beach scene using Stable Diffusion img2img.

The model preserved the overall layout of the original photo while changing the lighting, atmosphere, vegetation, and visual style.

### Counting Failure Experiment

The model was asked to generate exactly seven apples, but it produced twelve.

This experiment demonstrated that diffusion models may struggle with precise counting and exact spatial requirements.

---

## Project Files

| File | Description |
|------|-------------|
| `L07_AbouHarb_Eva_ITAI1378_notebook.ipynb` | Jupyter notebook containing the Stable Diffusion experiments, code, generated images, and outputs. |
| `L07_AbouHarb_Eva_ITAI1378_report.pdf` | Controlled generation report documenting the experiments, observations, figures, and reflection. |

---

## Skills Demonstrated

- Generative AI
- Diffusion Models
- Stable Diffusion
- Prompt Engineering
- Image Generation
- Image Editing
- Experimental Design
- Model Evaluation
- Python Programming
- GPU-Accelerated Computing

---

## Key Learning Outcomes

Through this project, I learned how different Stable Diffusion settings influence generated images. I gained practical experience controlling guidance scale, inference steps, random seeds, and negative prompts while keeping other variables fixed.

I also learned the importance of reproducibility in generative AI and how a locked seed can recreate the same result. The image-to-image experiment demonstrated how generative models can transform an existing photograph while preserving parts of its original structure.

Finally, the counting experiment showed that generative models can produce visually realistic images while still failing to follow precise instructions. This reinforced the importance of evaluating generated outputs carefully instead of assuming the model followed every part of the prompt correctly.
