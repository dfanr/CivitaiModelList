## Ranma Style LORA
### 一、模型概述

- 标签：`anime`, `retro`, `80s`, `style`, `1980s`
- 下载数：999
- 收藏人数：208
- 评论人数：2
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Ranma_style LORA_V1 

- 统计数据
  - 发布时间：2023-02-10T02:32:57.103Z
  - 原始模型：Other
  - 下载数：999
  - 评分人数：2
  - 评分：5
- 下载地址
  - [80sanimestyle_V10.safetensors](https://civitai.com/api/download/models/7691)
  - [8_80sanimestyle person.zip](https://civitai.com/api/download/models/7691?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a427107b-1016-43f0-b79c-5e8ebd7f6f00/width=450/72187.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cd639fc6-311e-44ee-f1d8-8e17bcb2f100/width=450/72206.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/de05127d-ed01-4d69-8d3d-ecd755254d00/width=450/72205.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/aa7e49a9-aa4a-49f2-76e7-f652cb70cd00/width=450/72204.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>A LORA trained to imitate the style of late '80s early 90's anime specifically, the Ranma 1/2 anime. It's similar to my Ranma 1/2 checkpoint, but it's not an extraction from the .ckpt, rather I trained the LORA from scratch with a tweaked data set. IMO the the main differences between them is, that the LORA seems to do a better job with full bodies and it lacks the graininess, slight blur and the sort of analog feel the .ckpt has.</p><p></p><p>As with most other LORA you're going to have to change the strength to somewhere between .4-.7 otherwise it will probably overpower and distort your results. It was trained with Anything V3, so it should work with it's various offshoots.</p><p></p><p>My training parameters were:</p><ul><li><p>max_resolution: 512,512,</p></li><li><p>learning_rate: 1e-4,</p></li><li><p>train_batch_size: 1,</p></li><li><p>epoch: 5",</p></li><li><p>mixed_precision: fp16,</p></li><li><p>save_precision: fp16</p></li><li><p>text_encoder_lr: 5e-5,</p></li><li><p>unet_lr: 1e-4,</p></li><li><p>clip_skip: 2,</p></li></ul>