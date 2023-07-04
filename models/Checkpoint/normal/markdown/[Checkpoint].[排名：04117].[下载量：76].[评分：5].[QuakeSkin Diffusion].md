## QuakeSkin Diffusion
### 一、模型概述

- 标签：`game art`, `game asset`, `style`, `video game`
- 下载数：76
- 收藏人数：48
- 评论人数：2
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-03-08T15:33:22.929Z
  - 原始模型：SD 1.5
  - 下载数：76
  - 评分人数：1
  - 评分：5
- 下载地址
  - [quakeskinDiffusion_v10.ckpt](https://civitai.com/api/download/models/20307?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [quakeskinDiffusion_v10.safetensors](https://civitai.com/api/download/models/20307)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/738a24cc-9fca-40ee-de7c-643f30538500/width=450/214977.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c735f03a-2fd0-4148-9b6a-f5faef2df500/width=450/214980.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d1a3af84-1873-4b3b-7598-344a1da10d00/width=450/214992.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/accd6dcb-9dd2-4b9f-69ed-60d754929b00/width=450/214978.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>QuakeSkin Diffusion</strong> is trained on UV unwrapped texture layouts for the Quake 1 Ranger model and can generate a wide variety of novel character types not seen in the small dataset (12 random skins from <a target="_blank" rel="ugc" href="https://www.moddb.com/games/quake/addons/quake-1-skins-pack">https://www.moddb.com/games/quake/addons/quake-1-skins-pack</a>). The training was run until the model learned the concept without reproducing any of the dataset examples.</p><h2>Instructions</h2><p><br /><a target="_blank" rel="ugc" href="https://www.dropbox.com/s/3p06uurglozq8ya/QuakeSkin_Input.png?dl=0">https://www.dropbox.com/s/3p06uurglozq8ya/QuakeSkin_Input.png?dl=0</a></p><p>To ensure the correct layout use the QuakeSkin_Input.png in img2img at <strong>512x512</strong> resolution. In my testing I used <strong>euler_a sampler @ 50 steps</strong> and <strong>CFG 12</strong> with a <strong>Denoising Strength of 0.75</strong>.</p><p>Prompt your subject followed by trigger words <code>in demoura artstyle</code></p><p>The front and back usually match up but not every time so generate in batches to pick the best ones.</p><p>To finish the skin you can feed the result back into img2img at <strong>1024x1024</strong> resolution, using similar or more steps + CFG, with a <strong>Denoising Strength of 0.2 - 0.3</strong> (as sometimes it might lose the back of the head and do two front faces)</p><p>To view your skins correctly on a player model, find and download <code>Ranger (A-posed &amp; Rigged)</code> model and scale the <strong>UV map</strong> in the <strong>Y dimension</strong> until the textures fit properly</p>