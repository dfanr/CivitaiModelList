## Kotosmix
### 一、模型概述

- 标签：`anime`, `base model`, `semi-realistic`
- 下载数：51829
- 收藏人数：9944
- 评论人数：163
- 评分人数：257
- 评分：4.93

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] V1.0

- 统计数据
  - 发布时间：2023-02-23T13:36:20.853Z
  - 原始模型：SD 1.5
  - 下载数：51829
  - 评分人数：257
  - 评分：4.93
- 下载地址
  - [kotosmix_v10.safetensors](https://civitai.com/api/download/models/6087?type=Model&format=SafeTensor&size=full&fp=fp16)
  - [kotosmix_v10.safetensors](https://civitai.com/api/download/models/6087)
  - [vae-ft-mse-840000-ema-pruned.ckpt](https://civitai.com/api/download/models/6087?type=VAE&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/62f620e7-8ff8-4f86-bc96-d6e2016c5e00/width=450/52456.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3310686f-35ec-465f-7aaf-53d838728f00/width=450/52462.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dd94f861-ca0c-4552-ab99-e7634986e900/width=450/111446.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4a8adf48-2cc3-4c28-e257-9de47e1b5d00/width=450/111445.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is a general purpose model able to do pretty much anything decently well from realistic to anime to backgrounds</p><p>All the images are raw outputs (with some using highresfix) no postprocessing involved or img2img upscaling</p><p></p><h3>Prompt style</h3><p>Keep it short and simple. If you want realism simply add (Realistic:1.5) to the beginning of your prompt and don't overcomplicate things</p><p></p><p>I recommend using DPM++ 2M Karras as the sampler</p><p></p><p>The images uploaded were upscaled through</p><p></p><p>latent(bilinear) 0.55-0.6 denoise upscaled by 1.5-2.5 OR</p><p>ESRGAN-4x 0.3-0.5 denoise upscaled by 1.5-2</p><p></p><h3>Where are the negative embeddings you used?</h3><p><a target="_blank" rel="ugc" href="https://huggingface.co/embed/EasyNegative/tree/main">https://huggingface.co/embed/EasyNegative/tree/main</a></p><p></p><h3>My generations are all desaturated and not colourful like yours?</h3><p><a target="_blank" rel="ugc" href="https://stable-diffusion-art.com/how-to-use-vae/">https://stable-diffusion-art.com/how-to-use-vae/</a></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/yesyeahvh/bad-hands-5/tree/main">https://huggingface.co/yesyeahvh/bad-hands-5/tree/main</a></p><p>these are the best ones</p><p></p><h3>My generations STILL don't look like yours?</h3><p>Did you use clip skip 2 and xformers AND the negative embeddings?</p><p></p><p>The images with longer prompts are very old generations I made back in October of 2022 there has been ALOT of changes since then and you might have a hard time replicating those gens.</p><p></p><p></p><p></p><h3>What vae did you use?</h3><p>For most of the images above I used the orange vae.</p><p><a target="_blank" rel="ugc" href="https://huggingface.co/WarriorMama777/OrangeMixs/blob/main/VAEs/orangemix.vae.pt">https://huggingface.co/WarriorMama777/OrangeMixs/blob/main/VAEs/orangemix.vae.pt</a></p><p></p><p>However I would recommend <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt">https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt</a> as It gives you much more vibrant realistic colours</p><p></p><h3>My generations have ugly faces?</h3><p>After some recent updates to auto1111 some things have changes. One noticeable thing is the order of the prompts you use matter ALOT more. Try reducing the prompt and use HIRESFIX or generating at a higher resolution</p><h3>I want to replicate the first image in the previews?</h3><h3><a target="_blank" rel="ugc" href="https://files.catbox.moe/y9pfir.png">https://files.catbox.moe/y9pfir.png</a></h3><p>the link above has the image with all the metadata</p><p></p>