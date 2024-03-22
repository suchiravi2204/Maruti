# Maruti Cars - Generative AI
The aim of the project is to fine-tune the [stable diffusion]{https://github.com/huggingface/diffusers} models 
on Maruti cars to generate realistic car model images in different environments using text prompts.

## Dataset
We used a set of images for a specific red color Maruti swift model with white background.
![swift car sample](https://github.com/exoper101/Maruti/blob/dev/dataset/sw01.jpg)
![swift car sample](https://github.com/exoper101/Maruti/blob/dev/dataset/sw02.jpg)
![swift car sample](https://github.com/exoper101/Maruti/blob/dev/dataset/sw03.jpg)
![swift car sample](https://github.com/exoper101/Maruti/blob/dev/dataset/sw04.jpg)

## Experimentation & results
Fine-tuning stable diffusion models with the following techniques to enhance the results.
### stable diffusion 1.5 with dreambooth
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exoper101/Maruti/blob/dev/Cars_DreamBooth_Stable_Diffusion.ipynb)

![Result](https://github.com/exoper101/Maruti/blob/dev/results/sd1.5_dreambooth/op-sd1.5-01.png)
![Result](https://github.com/exoper101/Maruti/blob/dev/results/sd1.5_dreambooth/op-sd1.5-02.png)


### stable diffusion XL with dreambooth and lora
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exoper101/Maruti/blob/dev/SDXL_DreamBooth_LoRA.ipynb)

![Result](https://github.com/exoper101/Maruti/blob/dev/results/sdxl_dreambooth_lora/op01.png)
![Result](https://github.com/exoper101/Maruti/blob/dev/results/sdxl_dreambooth_lora/op03.png)

### stable diffusion XL with textual inversion
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exoper101/Maruti/blob/dev/Cars_textual_inversion_sdxl.ipynb)

![Result](https://github.com/exoper101/Maruti/blob/dev/results/sdxl_textual_inversion/op-sdxl-tinv-01.png?)
![Result](https://github.com/exoper101/Maruti/blob/dev/results/sdxl_textual_inversion/op-sdxl-tinv-02.png?)

### stable diffusion inpainting
#### stable diffusion 1.5
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exoper101/Maruti/blob/dev/Cars_sd_inpaint.ipynb)

![Result](https://github.com/exoper101/Maruti/blob/dev/results/inpainting/op-sd1.5-inpainting-01.png?)
#### stable diffusion XL
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exoper101/Maruti/blob/dev/inpainting_cars.ipynb)

![Result](https://github.com/exoper101/Maruti/blob/dev/results/inpainting/op-sdxl-inp-01.png?)
