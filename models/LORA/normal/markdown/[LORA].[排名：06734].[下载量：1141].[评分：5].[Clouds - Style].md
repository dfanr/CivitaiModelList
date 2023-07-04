## Clouds - Style
### 一、模型概述

- 标签：`anime`, `style`, `illustration`, `artstyle`, `2.5d`
- 下载数：1141
- 收藏人数：204
- 评论人数：0
- 评分人数：1
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0 - Std

- 统计数据
  - 发布时间：2023-04-03T23:00:05.282Z
  - 原始模型：SD 1.5
  - 下载数：992
  - 评分人数：1
  - 评分：5
- 下载地址
  - [clouds.safetensors](https://civitai.com/api/download/models/34665)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/02351d7b-27a4-403a-6516-0e26437e6400/width=450/419904.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bf719927-0976-4037-7c74-45ea74be0d00/width=450/419903.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b1dfc0c7-0e07-481f-fd8b-8ab63141dc00/width=450/419887.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a8252243-69a8-4476-76f0-6eeb2c716400/width=450/419890.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0 - Raw

- 统计数据
  - 发布时间：2023-04-03T23:00:00.320Z
  - 原始模型：SD 1.5
  - 下载数：149
  - 评分人数：0
  - 评分：0
- 下载地址
  - [clouds_raw.safetensors](https://civitai.com/api/download/models/34673)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/10d32a2c-7e0b-4b9d-0c86-07af55376d00/width=450/419991.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/82e67259-4fbc-4a61-5ad8-acb9bc570700/width=450/419988.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e7bd7181-5874-41ed-8e37-6dd320114500/width=450/419989.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/48b2ff0f-dd92-4dbd-233d-f72efd76a100/width=450/419990.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/31f745fb-aa84-4ccf-e986-af380b6bbc00/width=525/31f745fb-aa84-4ccf-e986-af380b6bbc00" /><h3>What's this LoRA</h3><p>This is a LoRA trained on a particular style. This LoRAs has a nice 2.5d syle with soft colors and borders.</p><p>The images in the examples are created using only this LoRA and different models (mainly my customs: <a target="_blank" rel="ugc" href="https://civitai.com/models/24149">Mistoon_Anime</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/26332">Mistoon_Ruby</a> and <a target="_blank" rel="ugc" href="https://civitai.com/models/28322/mistoonemerald">Mistoon_Emerald</a>)</p><p>You don't need to specify a word to trigger this LoRA.</p><p>The LoRA works well on NSFW (check last examples).</p><p>The images are created using different weights (you can check on the image generation panel)</p><p></p><h3>Different Flavors</h3><p>My LoRAs are usually trained on AI generated images in two different steps. The first training uses images generated using a model (I choose it based on what I'm going to build) with a size of 512x768, and this is usually 10 images with different content but a similar style. The second training is based on pictures generated using the LoRA from the first step. This is done at a higher resolution (768x1152) and the output is usually upscaled using img2img.</p><p>The LoRA is available in two different flavors:</p><ul><li><p><strong>RAW</strong>: This is based on the first batch of images, it has usually a more creative output, but usually needs hiresfix or img2img to really shine</p></li><li><p><strong>Standard</strong>: This is based on the secon batch of images, it has usually a less creative output, but way more stable.</p></li></ul><p>Here's a quick comparison (not cherrypicked):</p><p><strong>RAW:</strong></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/00ddcc9d-3835-4a3c-ca8e-0edc354b0100/width=525/00ddcc9d-3835-4a3c-ca8e-0edc354b0100" /><p><strong>Standard:</strong></p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/24d7201c-0eb6-4527-5ea9-72a96d08a700/width=525/24d7201c-0eb6-4527-5ea9-72a96d08a700" /><p></p><h3>Guides</h3><p>Learn how to create pictures like mine with my step-by-step tutorials:</p><ul><li><p><a target="_blank" rel="ugc" href="https://medium.com/p/bd7dbcd5ce4b">Beginner's Guide</a></p></li><li><p><a target="_blank" rel="ugc" href="https://medium.com/p/35eacb3dc5f4">Prompting</a></p></li><li><p><a target="_blank" rel="ugc" href="https://medium.com/@inzaniak/stable-diffusion-ultimate-guide-pt-3-high-resolution-a4f5d7b60f38">My Workflow</a></p></li><li><p><a target="_blank" rel="ugc" href="https://medium.com/p/772ea69472c9">Inpainting</a></p></li></ul><p><strong>If you want to create images with a high LoRA weight, I highly suggest you to check the tutorial.</strong></p><p></p><h3>Support</h3><p>If you want to support my work, you can check out my music here:</p><p><a target="_blank" rel="ugc" href="https://inzaniak.bandcamp.com/">https://inzaniak.bandcamp.com/</a></p><p>You can also check my AI Art accounts, where you'll find daily pictures made with my models (and previews of new ones coming):</p><ul><li><p><a target="_blank" rel="ugc" href="https://www.instagram.com/inzaniak_aiart/">Instagram</a></p></li><li><p><a target="_blank" rel="ugc" href="https://www.deviantart.com/inzaniak">DeviantArt</a></p></li></ul><p></p>