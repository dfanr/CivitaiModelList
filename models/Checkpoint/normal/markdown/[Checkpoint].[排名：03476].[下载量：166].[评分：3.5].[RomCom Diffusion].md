## RomCom Diffusion
### 一、模型概述

- 标签：`movie`, `style`, `1990s`
- 下载数：166
- 收藏人数：46
- 评论人数：0
- 评分人数：2
- 评分：3.5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] 1.0

- 统计数据
  - 发布时间：2022-12-20T01:20:43.963Z
  - 原始模型：SD 1.5
  - 下载数：138
  - 评分人数：1
  - 评分：4
- 下载地址
  - [romcomDiffusion_10.safetensors](https://civitai.com/api/download/models/1689)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c16bc701-eb40-4466-dbe1-dd669412d500/width=450/15416.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/abb5218c-5820-448e-c70a-cc58db32a700/width=450/15415.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/475e3675-f357-44a7-886a-6302c87ec000/width=450/15414.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cf74bab7-5ca5-42a6-f245-34b92b2fda00/width=450/15413.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] 1.0

- 统计数据
  - 发布时间：2022-12-20T01:20:43.963Z
  - 原始模型：SD 1.5
  - 下载数：28
  - 评分人数：1
  - 评分：3
- 下载地址
  - [romcomDiffusion_10.ckpt](https://civitai.com/api/download/models/1688)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ae4b6565-5b54-47b6-d458-f72d2bfe5300/width=450/15420.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/141dd134-7536-4b21-e073-8db1d90d8d00/width=450/15419.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7fb6a559-9c1e-4337-26a5-31aefae56000/width=450/15418.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3eb8b4a4-b545-42e3-8c4a-ae5f9ede4000/width=450/15417.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Originally posted to <a href="https://huggingface.co/jkcarney/romcom-diffusion-1.0" rel="ugc" target="_blank">HuggingFace by jkcarney</a></p><p>Dreambooth model fine tuned on cropped 512x512 stills from various 1990s era romantic comedy movies. These stills are primarily of human subjects, but there are also samples of wide shots, crowds, and cars. Currently the list of movies used is:</p><ol><li>10 Things I Hate About You (64)</li><li>Clueless (45)</li><li>American Pie (37)</li></ol><p>In the future I may release a new version with more movie stills from additional movies. My hope is that more samples from more movies would increase facial fidelity and style.</p><p>Trained using Stable Diffusion 1.5 as a base.</p><p>I also recommend including movie still in your prompt; it was the class prompt for regularization images and I found it produces the best results.</p><p>I've found the best results using the DPM++ 2S a Karras sampler as well, but obviously feel free to experiment</p>