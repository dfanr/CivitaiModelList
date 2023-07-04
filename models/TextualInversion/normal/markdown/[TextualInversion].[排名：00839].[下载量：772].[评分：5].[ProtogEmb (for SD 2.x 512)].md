## ProtogEmb (for SD 2.x 512)
### 一、模型概述

- 标签：`digital art`, `protogen`, `digital painting`, `style`, `embedding`
- 下载数：772
- 收藏人数：110
- 评论人数：1
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] ProtogEmb v1

- 统计数据
  - 发布时间：2023-01-13T20:39:27.426Z
  - 原始模型：SD 2.1
  - 下载数：772
  - 评分人数：1
  - 评分：5
- 下载地址
  - [protogemb.pt](https://civitai.com/api/download/models/5082)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cd7e0c25-7e08-42e0-83d7-dee8dd28f900/width=450/37645.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ba3f350b-58d8-4dd0-9696-503925e58500/width=450/37650.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c58d3379-ef8d-4086-ec44-6936b1bd3900/width=450/37649.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bd6cad9f-099a-4ff3-aed9-78eafe296700/width=450/37648.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p></p><p>I was missing that very distinct protogen style in SD 2.1, so I made this embedding using several images generated from it. It turned out pretty good!</p><p>this was trained on <strong>"SD v2.1 512"</strong> model, you can use it on the 768 model as well but the results are wonkier</p><p></p><p><strong>HOW TO USE?</strong></p><p>just drop it into your "embeddings" folder and type the name of the file in your prompt, you can also rename it to whatever you want and use that as the trigger.</p><p></p><p><strong>HOW WAS IT MADE?</strong></p><p>The images used to train it were from protogen 2.2 and 3.4 using the base prompt darkstorm2150<strong> </strong>used for the showcase images of the original models.</p><p></p><p>8 vectors per token, 1000 steps, 67 base images (134 with flipped versions), 5 gradient accumulation steps, style_filewords template, shuffle tags enabled, deterministic, everything else at default.</p>