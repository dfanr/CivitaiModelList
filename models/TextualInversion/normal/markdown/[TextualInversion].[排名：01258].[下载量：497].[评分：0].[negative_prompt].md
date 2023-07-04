## negative_prompt
### 一、模型概述

- 标签：`concept`, `negative`
- 下载数：497
- 收藏人数：69
- 评论人数：4
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-16T04:52:06.628Z
  - 原始模型：SD 1.5
  - 下载数：497
  - 评分人数：0
  - 评分：0
- 下载地址
  - [negative_prompt.pt](https://civitai.com/api/download/models/71971)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ad853f0-20c6-4d96-8f27-4ce585243196/width=450/804065.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b18498d1-40b9-48a0-9e92-1dddf7b59be4/width=450/803714.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a26f7ea5-9411-42bd-bd44-c5ba64789a0d/width=450/803732.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/57c0f172-5dcb-456d-b89d-56033eb9d3cf/width=450/804067.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Place in negative prompt field. DO use negative_prompt with a VERY strong negative TEXT prompt- DO NOT use on its own. DOES NOT combine well with other bad image negative embeddings. DOES work with bad hands v5 on standard sd 1.5 and haven't tested anything on other sd models. It allows a fuller range of cfg and steps to experiment with and generates a more aesthetically pleasing image in general when paired with a VERY strong negative text prompt. You may be able to pair it with weaker negative aesthetic prompting by turning down the strength like so- (negative_prompt:0.7). This was my first functional attempt and I will probably work on some refinements but it takes my 3060 several hours to make even 1000 step embeddings and I am not fully sure what I am doing, so any ideas about how to create style embeddings or negative style embeddings, experiments with graphs etc please share.</p>