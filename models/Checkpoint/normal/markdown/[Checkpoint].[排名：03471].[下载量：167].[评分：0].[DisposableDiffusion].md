## DisposableDiffusion
### 一、模型概述

- 标签：`photorealistic`, `retro`, `base model`, `woman`, `man`, `realistic`
- 下载数：167
- 收藏人数：27
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-29T17:06:19.619Z
  - 原始模型：SD 1.5
  - 下载数：167
  - 评分人数：0
  - 评分：0
- 下载地址
  - [disposablediffusion_v10.safetensors](https://civitai.com/api/download/models/106339?type=Model&format=SafeTensor&size=full&fp=fp32)
  - [disposablediffusion_v10.safetensors](https://civitai.com/api/download/models/106339)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da333acb-febd-4423-8160-a584ef9c1c77/width=450/1336770.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/eff28603-0e4a-47dc-a937-61bbe35d4167/width=450/1336771.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/82766d7a-280e-4960-9625-607236ec86de/width=450/1336769.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d8aeb43d-b9d6-452f-8f80-d71c1d2be653/width=450/1336768.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>MAJOR UPDATE: I apologize for ANY inconvenience for my Pruned fp-16 checkpoint, as it was apparently generating static noises, which was an absolute shock to me since I thought I trained it well. I will fix it as soon as possible. Again, I'm sorry for any inconvenience. (Fixed it now on 6/29/23)</strong></p><p></p><p>Hey there, and welcome to my second checkpoint!</p><p></p><p>This time, I'm focusing on creating a photorealistic checkpoint based on the quality of disposable cameras (Fujifilm, Kodak, etc.), and merged <a target="_blank" rel="ugc" href="https://civitai.com/models/25694?modelVersionId=94744"><strong>epicRealism</strong></a> and <a target="_blank" rel="ugc" href="https://civitai.com/models/50000/cine-diffusion"><strong>Cine Diffusion</strong></a> along with my LoRAs to create that effect.</p><p></p><p><strong>Recommended keywords to gain the effect: </strong>"disposable camera quality", "Polaroid filter", "analog photo", etc.</p><p></p><p></p><p><strong>Recommended samplers: </strong>Euler A, or DPM++ 2M Karras</p><p><strong>Clip skip: </strong>2</p><p><strong>CFG Scale:</strong> 5-7</p><p><strong>Upscale by: </strong>2</p><p><strong>Denoising strength:</strong> (if you're doing hires. fix, do <strong>~0.55-0.7</strong>)</p><p></p><p><strong>I didn't bake any VAE in, but I highly recommend these VAEs:</strong></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/tree/main"><strong>vae-ft-mse-840000-ema-pruned</strong></a></p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/12262?modelVersionId=14459"><strong>Night Sky VAE (located at the download link)</strong></a></p><p></p><p>Suggestions and feedback are welcome! Hope you enjoy!</p>