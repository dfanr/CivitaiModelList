## negative_hand Negative Embedding 
### 一、模型概述

- 标签：`concept`, `negative embedding`, `bad prompt`
- 下载数：76227
- 收藏人数：5021
- 评论人数：33
- 评分人数：103
- 评分：4.95

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] negative_hand

- 统计数据
  - 发布时间：2023-05-02T23:14:27.850Z
  - 原始模型：SD 1.5
  - 下载数：76227
  - 评分人数：103
  - 评分：4.95
- 下载地址
  - [negative_hand-neg.pt](https://civitai.com/api/download/models/60938)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/22b0d6e3-a955-42fb-8e96-a1e295152bb3/width=450/671892.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1de1b4da-e9eb-43bf-9e9c-050e51cbbb25/width=450/667878.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1879056f-9bc8-4914-b1bd-6a9495dbd037/width=450/667876.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/342ad8dc-0677-4585-9da8-482de1b107c5/width=450/667879.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2>negative_hand Negative Embedding</h2><h3>Problem with Negative Embedding's</h3><p>Currently, there are more and more negative embedding, while many are also very good and easy to use. However, almost all of them currently have a big problem... They change the main or initial artstyle of the used model. Best example would be my bad_prompt_version2 Negative Embedding. It helps enormously with the quality of an image, but drastically changes the artstyle of the model. That's not the point of it. For this reason, I have now trained my new Negative Embedding negative_hand!</p><p>An example of the issue:</p><p><a target="_blank" rel="ugc" href="https://civitai.com/images/667829?modelVersionId=60938&amp;prioritizedUserIds=162020&amp;period=AllTime&amp;sort=Most%20Reactions&amp;limit=20">Image Link</a></p><p></p><h3>So what is negative_hand?</h3><p>negative_hand is supposed to fix the said issue. That means it should improve the quality of the image, but without changing the initial artstyle of the model.</p><p>Pro:</p><ul><li><p>The artstyle of the model can be used without any problems and without possible artstyle changes.</p></li><li><p>The quality of the image and incorrect anatomy like hands are improved.</p></li></ul><p>Con:</p><ul><li><p>Since this embedding cannot drastically change the artstyle and composition of the image, not one hundred percent of any faulty anatomy can be improved.</p></li></ul><p></p><h3>Usage</h3><p>To use this embedding you have to download the file aswell as drop it into the "\stable-diffusion-webui\embeddings" folder.</p><p><strong>Please put the embedding in the negative prompt to get the right results!</strong></p><p>For special negative tags such as "malformed sword", you still need to add them yourself. The negative embedding is trained on a basic skeleton for the negative prompt, which should provide a high-resolution image as a result.</p>