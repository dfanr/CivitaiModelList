## Ellie (TLOU part 1) Clean Lora
### 一、模型概述

- 标签：`character`, `the last of us`, `tlou`, `characters`, `lora`, `ellie`, `clean lora`
- 下载数：1534
- 收藏人数：162
- 评论人数：9
- 评分人数：2
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] AnyLora_epoch22_v1.0

- 统计数据
  - 发布时间：2023-06-06T04:02:44.902Z
  - 原始模型：Other
  - 下载数：1182
  - 评分人数：2
  - 评分：5
- 下载地址
  - [lora_CleanLORA_Ellie_(TLOU_p1)_Bake=AnyLORA_epoch22.safetensors](https://civitai.com/api/download/models/90110)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d5930106-7b3c-47b9-b1e2-ce97a00b0bfd/width=450/1045174.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/890def23-04fc-48c4-b826-ac5071e96e17/width=450/1050176.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/26b9800b-a1e9-4b18-bd50-7711675eb65c/width=450/1047114.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/93ebd647-9231-4ee0-97c0-60f69ae01fa5/width=450/1047076.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] GhostMixV3_epoch22_v1.0

- 统计数据
  - 发布时间：2023-06-06T04:02:44.902Z
  - 原始模型：Other
  - 下载数：182
  - 评分人数：0
  - 评分：0
- 下载地址
  - [lora_CleanLORA_Ellie_(TLOU_p1)_Bake=GhostMixV3_epoch22.safetensors](https://civitai.com/api/download/models/90129)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/24641e8a-8e0d-4687-9a9f-59eab82b06bc/width=450/1045432.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bc314449-ce93-4590-93b3-1fbee7c5b46a/width=450/1045427.jpeg" /> |
| ---- | ---- |

#### [版本1/共3个版本] SDV1.5_epoch22_v1.0

- 统计数据
  - 发布时间：2023-06-06T04:02:44.902Z
  - 原始模型：SD 1.5
  - 下载数：170
  - 评分人数：0
  - 评分：0
- 下载地址
  - [lora_CleanLORA_Ellie_(TLOU_p1_Bake=SD1.5_epoch22.safetensors](https://civitai.com/api/download/models/90141)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ef07f247-2895-448a-bdc6-9745297e1bb8/width=450/1045559.jpeg" /> |
| ---- |


### 三、详情
<p>This is my own version of Ellie from The last of us (part 1).</p><p><strong>What's special about this LORA is that every training images are generated in Blender with original game model with complete white background, which results in every generations being constant and stable in quality. Thus naming it, CLEAN LORA.</strong></p><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2e9039b4-acf2-48cd-8ed3-fb042da7c70f/width=525/2e9039b4-acf2-48cd-8ed3-fb042da7c70f.jpeg" /></p><p>Images with most popular camera angles are prioritized in learning with minor camera angles still being learnt but with less repetition. Ensuring most generations resulting in good camera shots. 35 repetitions are portrait and upper body shots. 25 are full body shots. 15 are extreme angles and sitting, and character looking away.</p><p></p><p><strong>3 bake versions are uploaded, </strong>AnyLora and Stable Diffusion v1.5 base. And then GhostMix v3 bake which is for using with GhostMix mainly.</p><p></p><p><strong>Prompts:</strong></p><p><strong>TLOU_EW </strong>is an optional token that can be used in prompts but unnecessary.<strong> </strong>Use this to get your image closer to trained images.</p><p></p><p><strong>MUST PLACE (bruise, dirty:1.3) in NEGATIVES to produce clean face without artifacts.</strong></p><p></p><p><strong>Recommended LORA strength = </strong>0.5 ~ 0.6</p><p></p><p><strong>Machine Learning Stats:</strong></p><p>Dimension = 512 x 768</p><p></p><p>(25 images x 35 repeats = 1015 steps)</p><p>+ (17 images x 25 repeats = 425 steps)</p><p>+ (21 images x 15 repeats = 315 steps)</p><p>/3 batch process = 585 steps per epoch</p><p></p><p>585 steps x 22 epoch = 12870 total steps</p><p></p>