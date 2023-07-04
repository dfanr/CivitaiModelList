## Cleave Gag
### 一、模型概述

- 标签：`concept`, `bondage`, `bdsm`, `gag`
- 下载数：1788
- 收藏人数：358
- 评论人数：3
- 评分人数：3
- 评分：4.33

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0 

- 统计数据
  - 发布时间：2023-06-11T20:13:05.148Z
  - 原始模型：Other
  - 下载数：1443
  - 评分人数：3
  - 评分：4.33
- 下载地址
  - [cleave_gag_v1-000009.safetensors](https://civitai.com/api/download/models/94054)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fce6a36c-a187-4ad0-97c3-46766550d865/width=450/1113084.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/588ca05a-3f92-497f-a161-abcb55db36f9/width=450/1113086.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c7367d96-582d-4f2e-821f-a9849cbda5ab/width=450/1113128.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/82382100-4e95-491a-bc42-cec511cf5bbf/width=450/1113133.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0 Knotted Cleave

- 统计数据
  - 发布时间：2023-06-11T20:13:05.148Z
  - 原始模型：Other
  - 下载数：345
  - 评分人数：0
  - 评分：0
- 下载地址
  - [knotted_cleave_v1-000008.safetensors](https://civitai.com/api/download/models/94065)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3d21e581-1c9c-488d-82c5-c43c21b80207/width=450/1113246.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/203d3bb9-468e-4cf4-99a2-9d7c4912825b/width=450/1113357.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0c243d68-8397-48e3-8835-a5072383b87c/width=450/1113378.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a583e17d-5f04-4702-b578-92ac2212151d/width=450/1113383.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Made an attempt at cleave gags, they're alright. Separated into two Loras, one for normal and another for knotted. The latter had a much smaller dataset and generally performs worse especially when it comes to texturing the knot, but there's at least a noticeable difference between the two. I tagged them at the same time then trained separately, so they share a trigger word.</p><p></p><p>Trigger Word:</p><pre><code>clv</code></pre><p>I removed all "gag"-related tags since I figured they'd interfere, but I have found that adding</p><pre><code>cleave gag</code></pre><p>actually improves accuracy in some cases, at least when using a bondage model. Give that a try as well if you find it's not being consistent!</p><p></p><p>I also had some instances where it was noticeably difficult to add bindings with some combinations of other Loras and I'm unsure why. Perhaps this is better suited to inpainting? I also found the knotted cleave model to be more overfit than the normal one, so I had to use a smaller CFG to compensate. It also sometimes added animal ears, no clue why.</p><p></p><p>Recommended weight: ~1.0</p>