## Mars Mix
### 一、模型概述

- 标签：`character`, `photorealistic`, `sexy`, `female`, `porn`, `highly detailed`, `nudes`, `woman`, `sex`, `breasts`, `beautiful`, `fantasy`, `photorealism`, `portraits`, `realistic`, `women`
- 下载数：8440
- 收藏人数：1317
- 评论人数：14
- 评分人数：21
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v0.2

- 统计数据
  - 发布时间：2023-03-27T11:22:37.646Z
  - 原始模型：SD 1.5
  - 下载数：6366
  - 评分人数：14
  - 评分：5
- 下载地址
  - [marsMix_v02.safetensors](https://civitai.com/api/download/models/27008)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/449dc801-cbf6-4c2a-9570-b58a76b1a100/width=450/297678.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6092378c-0bbf-4c67-7c6c-f44f8e7e0f00/width=450/297677.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0be004de-bc0f-4a5c-fd36-ba08cfbcf400/width=450/297676.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/70edd191-952d-447e-ae18-27cb6d71dd00/width=450/297675.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v0.1

- 统计数据
  - 发布时间：2023-03-27T11:22:37.646Z
  - 原始模型：SD 1.5
  - 下载数：2074
  - 评分人数：7
  - 评分：5
- 下载地址
  - [marsMix_v01.safetensors](https://civitai.com/api/download/models/16860)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6d012280-5a3a-4122-159e-0deb8d3f0800/width=450/170533.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/eed7f779-89da-48de-087c-9b1d787d7d00/width=450/170545.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f6a0f80e-4430-4986-5e0c-6d98b86ef600/width=450/170544.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/309f3a58-8db0-46f7-084f-d60b8289e000/width=450/170543.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Attention: You need a VAE to use this model. I recommend you try <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/tree/main">this one</a> out.</p><p></p><p>This model involves dreamlike photoreal, so here is the <a target="_blank" rel="ugc" href="https://huggingface.co/dreamlike-art/dreamlike-photoreal-2.0/blob/main/LICENSE.md">license</a> that you must abide by. Also check out the license in the <a target="_blank" rel="ugc" href="https://civitai.com/models/6424/chilloutmix">chillout mix page </a>regarding commercial use, we have chillout in this model.</p><p></p><p>This is Mars Mix, closely related to <a target="_blank" rel="ugc" href="https://civitai.com/models/6931/ares-mix">Ares Mix</a>, but allowing for a hit in realism in exchange for some wilder poses / artistic possibilities and bigger breasts. The model uses the same photorealistic core as Ares Mix, but uses a rebuilt anime core with a much more aggressive block merge that allows for a lot of the posing and texture information from the anime model to come through, while keeping the photorealistic skin textures and faces. The result is a photorealistic model that allows for a more exaggerated anatomy, understands the booru tag prompting style really well and is compatible with CLIP skip 2, while still mostly keeping the hardcore capabilities of Ares Mix. If you're a member of the anime side of the community and would like to learn the ropes of photorealistic, I consider this model a good place to start.</p><p></p><p>All example images were made using CLIP skip 1, ENSD 31337. The parameters are included in the images. I recommend you always have <code>child</code> or <code>infant</code> in your negative prompt. Since Analog Diffusion is making an indirect appearance in the model list (by way of Chillout Mix), you may sometimes notice some facial blur or haze. This can be remedied by including <code>blur</code> and/or <code>haze</code> in the negative prompt.</p><p></p><p>Longer explanation for model merging enthusiasts:</p><p></p><p>This model uses the same anatomy core as Ares Mix, you can read about how to build it from that model's page. The anime core has been rebuilt using Chillout Mix instead of Basil Mix for the block merge, the complete removal of gape60 and anything v4.5, and updating grapefruit to version 3.1. Chillout is merged directly into grapefruit using the Abyss Orange Mix coefficients, then the result gets 15% merge with RPG v4. This forms the new anime core</p><p></p><p>The anatomy core is block merged with the anime core using the following Coefficients (anatomy is model A, anime is model B, base alpha set to 1.0):</p><p>"0.05199847612695355,0.05722134125067434,0.06354625877794251,0.07135480548979826,0.08122523963562354,0.09407671474206218,0.25,0.4,0.4,0.4,0.4,0.8,0.7,0.8,0.4,0.4,0.4,0.4,0.25,0.09407671474206218,0.08122523963562354,0.07135480548979826,0.06354625877794251,0.05722134125067434,0.05199847612695355".</p>