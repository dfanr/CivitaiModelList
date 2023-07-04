## Groo the Wanderer
### 一、模型概述

- 标签：`character`, `cartoon`
- 下载数：124
- 收藏人数：15
- 评论人数：7
- 评分人数：0
- 评分：0

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] 1

- 统计数据
  - 发布时间：2023-03-16T16:02:41.355Z
  - 原始模型：SD 1.5
  - 下载数：72
  - 评分人数：0
  - 评分：0
- 下载地址
  - [grooTheWanderer_1.safetensors](https://civitai.com/api/download/models/22858)
  - [grooTheWanderer_1_trainingData.zip](https://civitai.com/api/download/models/22858?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3a1d56e4-f068-4c39-b048-270210769200/width=450/263093.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e6264ecc-eb10-48e7-4180-1cb3b1601100/width=450/247278.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1ef31418-6dca-4ae8-49de-38f028d91a00/width=450/247279.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4d49cdd3-2770-4fd2-efbb-d229758e2b00/width=450/249649.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] style

- 统计数据
  - 发布时间：2023-03-16T16:02:41.355Z
  - 原始模型：SD 1.5
  - 下载数：23
  - 评分人数：0
  - 评分：0
- 下载地址
  - [grooTheWanderer_style.ckpt](https://civitai.com/api/download/models/24197)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7678a938-9320-4b85-f66c-9bcd59040900/width=450/263087.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/14b9878f-499f-416e-6e01-b0ee456b8a00/width=450/263086.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fa7d8358-5cea-4de2-b160-b4cdc5b46e00/width=450/263085.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/65ee4b0b-3979-4740-fa87-18c30f1e5e00/width=450/263084.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] 2

- 统计数据
  - 发布时间：2023-03-16T16:02:41.355Z
  - 原始模型：SD 2.1
  - 下载数：29
  - 评分人数：0
  - 评分：0
- 下载地址
  - [grooTheWanderer_2.safetensors](https://civitai.com/api/download/models/23073)
  - [grooTheWanderer_2_trainingData.zip](https://civitai.com/api/download/models/23073?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2e1c5b8b-a6e2-4230-70c6-8e469ed46500/width=450/249648.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2097a1fc-6a1b-41a2-a4a1-848e4ac09200/width=450/249647.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b30710e1-a046-4187-f762-eb9745507e00/width=450/249646.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0859b7e8-09d7-43e6-daca-25f4c76c8c00/width=450/249645.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is a dreambooth trained on the comic book character Groo the Wanderer.<br /></p><p>The base stable diffusion models struggle to draw this character, my guess that it's because of its unusual style, and insufficient images of him outside of comic book pages, where he appears small and hard to extract from the background.</p><p><br />The trained data is available for download<br /><br />Version 1 is trained on  sd 1.5, with 10 images of Groo with the background removed. it worked better to create funny versions of Groo as a real-life person<br /><br />Version 2 is trained on sd 2.1 with the same 10 images plus 19 images without their background removed. I didn't upload it as a new version because it got worse at drawing a recognizable Groo if I ask for photorealism, but some things it does better. It makes a much more realistic barbarian<br /><br />There is a LoRA, that makes more sense for a single character, but I couldn't get the same funny real life version of Groo with that too. It's the same training data as groo-01.<br /><br />Example images have a different hash because that was before I converted the model to safetensor</p>