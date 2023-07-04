## Background Complexity Additive
### 一、模型概述

- 标签：`lighting`, `scenery`, `background`
- 下载数：1063
- 收藏人数：213
- 评论人数：3
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] BG2_dpep4+silicon29dim64

- 统计数据
  - 发布时间：2023-06-16T03:30:16.421Z
  - 原始模型：SD 1.5
  - 下载数：818
  - 评分人数：0
  - 评分：0
- 下载地址
  - [BG2_dpep4+silicon29dim64.safetensors](https://civitai.com/api/download/models/97004)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0484cf95-08f6-4c1a-9245-a691353a784b/width=450/1161962.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a25a7a38-1196-4e01-a6ea-4cacd840949b/width=450/1161936.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d27654db-d391-44e5-9bad-e5393e247e4a/width=450/1161934.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/070303cd-22aa-439c-8023-6571b057ca5f/width=450/1161935.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] BG_dpep4+silicon29dim4

- 统计数据
  - 发布时间：2023-06-16T03:26:25.184Z
  - 原始模型：SD 1.5
  - 下载数：245
  - 评分人数：0
  - 评分：0
- 下载地址
  - [background-complexity-additive.safetensors](https://civitai.com/api/download/models/96171)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a06e5e44-36d6-47df-8a4f-a534cdf8f29c/width=450/1146836.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2f316bf2-109c-4487-b89e-6b6b06c112a7/width=450/1146823.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d389a7c6-ba7a-4e80-b359-d91c8dd85c67/width=450/1146826.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e5f32409-1d15-4a7f-847e-d4952c36903d/width=450/1146828.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This model is meant to enhanced the complexity and prominence of your backgrounds. It's made by combining background-focused loras and then target isolating blocks to reduce the effect on things like style, clothing, coloring, anatomy, or facial details.</p><p>In practice it's a bit finicky. The primary observed effect it that without any tags for shot distance, it will make your background take up more space. It won't necessarily make your background better, persay, but will increase the number of visible background elements, their density, and their prominence. In the case of images where you want one extremely prominent backdrop or you want your character to be silhouetted against the backdrop it actually might be better not to prompt it or prompt it negative, as prompting it negative will creat the opposite effect. Because of the way it's block isolated, you can prompt it at strong weights without it making your picture look like a complete mess. I recommend toying with both positive and negative weights if you decide to use it, as both create interesting outcomes.</p><p>If you prompt for an image that only has landscape/scenery, prompting it will increase coherency. Likewise, negative prompting it will make the landscape make less sense. Both have their own uses.</p>