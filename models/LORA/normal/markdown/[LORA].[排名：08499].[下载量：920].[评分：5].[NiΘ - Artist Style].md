## NiΘ - Artist Style
### 一、模型概述

- 标签：`style`, `artist`, `artstyle`, `niθ`, `al azif`, `leica crusade`, `hadou ruri`
- 下载数：920
- 收藏人数：122
- 评论人数：4
- 评分人数：2
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v2.2

- 统计数据
  - 发布时间：2023-06-16T13:26:05.406Z
  - 原始模型：SD 1.5
  - 下载数：387
  - 评分人数：1
  - 评分：5
- 下载地址
  - [nithe-style_v2.2.safetensors](https://civitai.com/api/download/models/97253)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/190dd847-cbd8-414c-80a3-6a5f100b5038/width=450/1166475.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f8e557a5-0172-42db-b017-b58b531c410a/width=450/1166471.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/67c3fc24-6c02-4ea5-bd4b-19d2053a6544/width=450/1166477.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/28a24a37-0a17-423d-b010-8ecd9d97bb0f/width=450/1166476.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v1.1

- 统计数据
  - 发布时间：2023-06-16T13:10:52.132Z
  - 原始模型：SD 1.5
  - 下载数：281
  - 评分人数：0
  - 评分：0
- 下载地址
  - [nithe-style_v1.1.safetensors](https://civitai.com/api/download/models/95581)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7e86bf6f-e5a3-4762-a9f7-f83320e60a9b/width=450/1137719.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9f3ad9b1-5509-4bc6-9936-2e104b77203b/width=450/1137723.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9c84e801-ab3a-4354-ad84-7c03a23e6955/width=450/1137721.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/67adef85-d904-4380-a826-5f78ce6e41db/width=450/1137720.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v1.0

- 统计数据
  - 发布时间：2023-06-16T13:10:52.132Z
  - 原始模型：SD 1.5
  - 下载数：252
  - 评分人数：1
  - 评分：5
- 下载地址
  - [nithe-style_v1.0.safetensors](https://civitai.com/api/download/models/95155)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/06ed6995-762a-4657-ac17-b39b279bd36d/width=450/1130629.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/225e5d6b-78b7-4ef3-b422-963c4d9596ff/width=450/1130630.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9294a1c7-6df7-4c26-816a-ba2dbddc89c5/width=450/1130632.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a91d7dd1-3402-4862-9293-a4d0bbd4395b/width=450/1130633.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2 id="heading-12"><em>NiΘ</em> - Artist Style</h2><p><span style="color:rgb(193, 194, 197)">This Lora is trained in the art style of NiΘ</span>.</p><p>This style is somewhere between "Demonbane" and "塵骸魔京" (6:4).</p><p></p><p>Usage Tips:</p><ul><li><p>v1.0</p><ul><li><p>Deplicated.</p></li></ul></li><li><p>v2.2</p><ul><li><p>Added optional trigger words.</p></li></ul></li></ul><ul><li><p>Recommended model is <a target="_blank" rel="ugc" href="https://civitai.com/models/9942">AbyssOrangeMix3</a></p></li><li><p>Use a weight of 0.8 - 1.0</p></li><li><p>Optional trigger words: <code>al azif</code> <code>hadou ruri</code> <code>leica crusade</code></p></li></ul><p>Example:</p><pre><code># Base
Sampler: DPM++ SDE Karras
Steps: 30
CFG scale: 7.5
Clip skip: 2

# Hires
Hires upscale: 2
Hires upscaler: R-ESRGAN 4x+
Hires steps: 50
Denoising strength: 0.6

# Models
Model: AbyssOrangeMix_abyssorangemix3_aom3a1b
VAE: orangemix.vae</code></pre>