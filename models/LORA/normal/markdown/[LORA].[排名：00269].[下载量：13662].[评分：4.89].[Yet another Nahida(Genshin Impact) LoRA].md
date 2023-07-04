## Yet another Nahida(Genshin Impact) LoRA
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `video game`, `genshen，nahida`
- 下载数：13662
- 收藏人数：2106
- 评论人数：13
- 评分人数：38
- 评分：4.89

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] NahidaV3

- 统计数据
  - 发布时间：2023-03-11T12:56:11.926Z
  - 原始模型：Other
  - 下载数：12643
  - 评分人数：35
  - 评分：4.89
- 下载地址
  - [Nahida3.safetensors](https://civitai.com/api/download/models/21618)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e9a2f65d-d913-4c2d-020b-e4fc5ddc4300/width=450/229908.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b1d97bb9-f75e-4fe8-4ebe-492a9b2baa00/width=450/229907.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d455930d-e356-41db-e68d-d3bf1084a000/width=450/229906.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da9b43c7-4edd-45df-2b79-d125972ac700/width=450/229905.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] NahidaV2

- 统计数据
  - 发布时间：2023-03-11T12:56:11.926Z
  - 原始模型：Other
  - 下载数：687
  - 评分人数：2
  - 评分：5
- 下载地址
  - [Nahida.safetensors](https://civitai.com/api/download/models/20211)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4f2bcb29-85ca-47fd-8faa-9e4006cf2300/width=450/213695.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8560ff5b-7f92-4706-e1c8-878e5cf65d00/width=450/213694.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f374bd8b-edd7-4b8a-0748-d9a7cbc61900/width=450/213693.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/477fac70-8c17-4417-25f2-92b9e1c28c00/width=450/213692.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] NahidaV1

- 统计数据
  - 发布时间：2023-03-11T12:56:11.926Z
  - 原始模型：Other
  - 下载数：332
  - 评分人数：1
  - 评分：5
- 下载地址
  - [Nahida.safetensors](https://civitai.com/api/download/models/19976)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e1db01be-612a-436d-19cb-c36916be6600/width=450/210978.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bcd5c79b-1f0f-41cd-64b6-7c9ffa1a7c00/width=450/210983.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/105c018e-a7c2-4a84-69af-3d4567d1cf00/width=450/210982.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/004e1b76-113c-4ee8-a934-b523aed6ae00/width=450/210980.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is yet another Nahida Lora.</p><p></p><h3>Notice</h3><p>V3 has better performance than V2, and V2 has significantly better performance than V1.</p><p></p><h3>Compatibility</h3><p>Trained on the NAI model, and is therefore compatible with any anime-styled model such as Anything, Counterfeit, AOM, and PastelMix. This is shown in the example images.</p><p></p><p>Note that the cross-shaped pupils show up best in Anything and AOM.</p><p></p><h3>Features</h3><p>As of V3, the LoRA is able to do the following.</p><ul><li><p>Dress up Nahida in alternate outfits. Examples of how to do this are in the sample images</p></li><li><p>Responds very well to perspective prompts such as from below, from behind, etc.</p></li><li><p>Give Nahida her signature cross-shaped pupils. This occurs whenyou generate at a sufficiently large resolution(above 896x896). Examples are given in the sample images</p></li><li><p>Can inpaint in the perfect looking cross-shaped pupils</p></li></ul><p></p><h3>Inpainting</h3><p>If you have generated a good Nahida image and wish to add the pupils in via inpainting, simply mask the face and inpaint with the following settings</p><p>prompt: masterpiece, best quality, 1girl, solo, nahida_genshin, cross-shaped pupils &lt;lora:NahidaV3:1&gt;</p><p>neg-prompt: EasyNegative, extra fingers, fewer fingers</p><p>Default inpainting settings, 25 steps, 832x832 resolution, and 0.55 denoising strength. Make sure to select inpaint area as "Only masked"</p><p>This should add her cross-shaped pupils in a few tries.</p><p></p><h3>Recommended Weight</h3><p>In V3, generating at weight = 1.0 produces good results for all occasions. </p>