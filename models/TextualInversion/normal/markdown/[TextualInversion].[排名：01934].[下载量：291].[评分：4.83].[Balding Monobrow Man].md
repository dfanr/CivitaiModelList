## Balding Monobrow Man
### 一、模型概述

- 标签：`youtuber`, `mehdi sadaghdar`, `electroboom`, `balding`, `celebrity`, `male`
- 下载数：291
- 收藏人数：47
- 评论人数：13
- 评分人数：6
- 评分：4.83

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] ElectroBoom

- 统计数据
  - 发布时间：2023-02-11T18:14:16.372Z
  - 原始模型：SD 1.5
  - 下载数：291
  - 评分人数：6
  - 评分：4.83
- 下载地址
  - [electroboom.pt](https://civitai.com/api/download/models/9359)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4848283f-0699-4b91-6f75-b908ae2cab00/width=450/89919.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/698b8adf-e23a-4b7e-a610-19ad1bfbdb00/width=450/89925.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3bdbce9b-6eb8-4dc0-c193-00c2b768db00/width=450/89924.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/014feab1-5936-4e02-26a6-d025827e8000/width=450/89923.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Behold, the electrical man himself.</p><p></p><p>Go visit and subscribe to <a rel="ugc" href="https://www.youtube.com/@ElectroBOOM">ElectroBoom</a>, he is extremely entertaining and educational.</p><p></p><p>This embedding was trained using screencaps from the youtube videos and as such, it tends to be heavy on his studio background and soft lighting. So here is a small tutorial on how to properly cast embeddings in your prompt:</p><p></p><p>The wrong:</p><p>(EmbeddingName:0.5)</p><p>Don't do this. You can get away with a couple decimal points change, but the way embedding works, they don't properly scale with this method.</p><p></p><p>The chad way:</p><p>[Before:After:When]</p><p>This is available in Automatic1111 and probably in others, this controls when tokens or an embedding begins being used and stops being used. Like I said, this embedding will change your composition due to the photo availability of the subject, so the proper way of using is something like:</p><p>[a bald man:ElectroBoom:0.3]</p><p>This means the rendering will go for 30% before starting to use the token, giving the model plenty of time to create the background and the subject before changing it to be our hero.</p>