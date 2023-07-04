## Shadow97's Particle
### 一、模型概述

- 标签：`anime`, `style`, `semirealistic`
- 下载数：1089
- 收藏人数：338
- 评论人数：18
- 评分人数：3
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] M3A1

- 统计数据
  - 发布时间：2023-05-10T05:15:57.043Z
  - 原始模型：SD 1.5
  - 下载数：582
  - 评分人数：1
  - 评分：5
- 下载地址
  - [shadow97sParticle_m3a1.safetensors](https://civitai.com/api/download/models/66580)
  - [shadow97sParticle_m3a1.safetensors](https://civitai.com/api/download/models/66580?type=Model&format=SafeTensor&size=full&fp=fp32)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a33686fa-17e8-4269-97e5-9434ecd6cf4d/width=450/742811.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/664b3546-3a48-4622-b672-fe9124eff9a3/width=450/742813.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e6fe10a9-d81d-473f-a56a-db8e24afa2e7/width=450/742814.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/76c34066-daff-4005-b487-7560e4012390/width=450/742815.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] M2

- 统计数据
  - 发布时间：2023-05-09T20:23:37.385Z
  - 原始模型：SD 1.5
  - 下载数：507
  - 评分人数：2
  - 评分：5
- 下载地址
  - [shadow97sParticle_m2.safetensors](https://civitai.com/api/download/models/55393?type=Model&format=SafeTensor&size=full&fp=fp32)
  - [shadow97sParticle_m2.safetensors](https://civitai.com/api/download/models/55393)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4ec8a626-8d82-4b95-958c-e423c9813a00/width=450/600200.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/34a8dfd6-3e92-45a3-3475-93d9ca57cf00/width=450/600199.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e59ca8c7-afd2-49fc-7930-bf6dbd9fa100/width=450/600175.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/38bfc906-1220-4aa2-4ace-86ae73768400/width=450/600176.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is a rather old model of mine, so it might be faulty in some aspects. Most notably, it sometimes produces nonsensical faces and creates textures where they shouldn't be, but you should be fine as long as you use recommended settings.</p><p></p><p>Sampler: DPM++ 2M Karras, DPM++ SDE Karras</p><p>Steps: 20+</p><p>CFG Scale: Anywhere between 4 to 11, beyond that I did not test, but I doubt you'd be using values outside of that bracket anyway. Lower scale values seem to be more "creative" at the cost of producing more muted colors. Also, higher CFG scale values tend to produce aforementioned errors more often (for instance, on Euler a with 20 steps and no hires.fix)</p><p>Hires.fix: on, upscaler either any of the Latents or R-ESRGAN 4x of your taste. Latent is more creative, R-ESRGAN is less prone to nonsense generations. Use denoise strength in the range of 0.55 to 0.75 for Latent and 0.3 to 0.75 for R-ESRGAN.</p><p>Clip Skip: 1 or 2, the effect is similar to CFG Scale with 1 being more creative and 2 having deeper contrast and more popping colors (all example images made with Clip Skip 2).</p><p>VAE: the one from the base SD 1.5 model. I didn't bake it in just in case you want to use something else with the model.</p>