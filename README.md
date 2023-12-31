🐣 Please follow me for new updates https://twitter.com/camenduru <br />
🔥 Please join our discord server https://discord.gg/k5BwmmvJJU <br />
🥳 Please join my patreon community https://patreon.com/camenduru <br />

### 🦒 Colab

| Colab | Info
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/DemoFusion-colab/blob/main/DemoFusion_colab.ipynb) | DemoFusion_colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/DemoFusion-colab/blob/main/DemoFusion_img2img_colab.ipynb) | DemoFusion_img2img_colab (Thanks to [radamar](https://twitter.com/radamar) ❤)

### 🦆 Kaggle

| Kaggle | Info
| --- | --- |
[![open_in_kaggle_small](https://user-images.githubusercontent.com/54370274/228924833-17316feb-d0fe-4249-90ba-682930ba11e5.svg)](https://kaggle.com/camenduru/demofusion) | DemoFusion_kaggle
[![open_in_kaggle_small](https://user-images.githubusercontent.com/54370274/228924833-17316feb-d0fe-4249-90ba-682930ba11e5.svg)](https://kaggle.com/camenduru/demofusion-img2img) | DemoFusion_img2img_kaggle

### 📋 Tutorial

2048x2048 will take around 800 seconds. (T4) <br />
![Screenshot 2023-12-08 133528](https://github.com/camenduru/DemoFusion-colab/assets/54370274/e4743713-50a3-470b-b606-baf5b817c800) <br />

`view_batch_size` (int, defaults to 16): The batch size for multiple denoising paths. Typically, a larger batch size can result in higher efficiency but comes with increased GPU memory requirements. <br />
`stride` (int, defaults to 64): The stride of moving local patches. A smaller stride is better for alleviating seam issues, but it also introduces additional computational overhead and inference time. <br />
`cosine_scale_1` (float, defaults to 3): Control the strength of skip-residual. For specific impacts, please refer to Appendix C in the DemoFusion paper. <br />
`cosine_scale_2` (float, defaults to 1): Control the strength of dilated sampling. For specific impacts, please refer to Appendix C in the DemoFusion paper. <br />
`cosine_scale_3` (float, defaults to 1): Control the strength of the Gaussian filter. For specific impacts, please refer to Appendix C in the DemoFusion paper. <br />
`sigma` (float, defaults to 1): The standard value of the Gaussian filter. Larger sigma promotes the global guidance of dilated sampling, but has the potential of over-smoothing. <br />
`multi_decoder` (bool, defaults to True): Determine whether to use a tiled decoder. Generally, when the resolution exceeds 3072x3072, a tiled decoder becomes necessary. <br />
`show_image` (bool, defaults to False): Determine whether to show intermediate results during generation. <br />

### 🧬 Code
https://github.com/PRIS-CV/DemoFusion

### 📄 Paper
https://arxiv.org/abs/2311.16973

### 🌐 Page
https://ruoyidu.github.io/demofusion/demofusion.html

### 🖼 Output

https://github.com/camenduru/DemoFusion-colab/assets/54370274/6ed1d6d8-0ea1-4cb6-b239-3a1e02a10fb1

https://github.com/camenduru/DemoFusion-colab/assets/54370274/927bb386-0626-4877-8123-c00f51c4ed3d

DemoFusion_img2img_colab

https://github.com/camenduru/DemoFusion-colab/assets/54370274/f41dcf3c-d489-480e-8637-bd4b5559c6ab

https://github.com/camenduru/DemoFusion-colab/assets/54370274/d7777a23-efb2-4cb2-a1f4-a49537fd8f15

### 🏢 Sponsor
https://modelslab.com
