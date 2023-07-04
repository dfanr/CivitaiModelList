## Xrystl Mix
### 一、模型概述

- 标签：`anime`, `character`
- 下载数：263
- 收藏人数：79
- 评论人数：2
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] XrystlMx_0.3

- 统计数据
  - 发布时间：2023-06-27T16:20:17.467Z
  - 原始模型：Other
  - 下载数：263
  - 评分人数：0
  - 评分：0
- 下载地址
  - [xrystlMix_xrystlmx03.safetensors](https://civitai.com/api/download/models/105282)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/426d0198-208c-46d9-84a1-8088e18f646a/width=450/1310480.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/86a89d94-23ba-49f8-be36-002daaece6de/width=450/1310518.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bbfe3e71-cdcf-4bed-9ba1-28016bf0299b/width=450/1310524.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/513ff01b-762c-4548-90c0-1e630944621a/width=450/1310624.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>A very simple merge of publicly available models, I'm putting it here mostly for my own reference. Mainly for characters, but it can produce some nice detailed backgrounds. I use inpainting and i2i upscaling for uploading on Pixiv, but for this repo I will just give example images of t2i + Hires.</p><p></p><p>Settings to get you started</p><ol><li><p>Clip skip: 2 (1 can be a bit chaotic).</p></li><li><p>Sampler: DPM++ 2M Karras (good starting point) / Euler a (can sometimes give better but more random images)</p></li><li><p>VAE: I like orangemix.vae but you can swap out for whatever you want. There is no baked vae.</p></li><li><p>Steps: 20-30 steps. You can go higher but it doesn't make too much difference (except with Euler a)</p></li><li><p>CFG scale: 6-8</p></li><li><p>Hires upscaler: 20 steps with 0.5 denoising. Play around with upscalers to get your desired aesthetic</p></li><li><p>Negative prompts: EasyNegative, (bad-hands-5:0.8), (realistic, lips, nose, tooth:1.0)</p></li><li><p>Prompts: (masterpiece, best quality:1.1)</p></li></ol>