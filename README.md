---
license: creativeml-openrail-m
tags:
- pytorch
- diffusers
- stable-diffusion
- text-to-image
- diffusion-models-class
- dreambooth-hackathon
- animal
widget:
- text: a photo of swimming dodam in the Acropolis
---

# DreamBooth model for the swimming concept trained by ganghyeon on the GanghyeonLeee/dodam dataset.

This is a Stable Diffusion model fine-tuned on the swimming concept with DreamBooth. It can be used by modifying the `instance_prompt`: **a photo of swimming dodam**

This model was created as part of the DreamBooth Hackathon 🔥. Visit the [organisation page](https://huggingface.co/dreambooth-hackathon) for instructions on how to take part!

## Description


This is a Stable Diffusion model fine-tuned on `dodam` images for the animal theme.


## Usage

```python
from diffusers import StableDiffusionPipeline

pipeline = StableDiffusionPipeline.from_pretrained('ganghyeon/swimming-dodam')
image = pipeline().images[0]
image
```
