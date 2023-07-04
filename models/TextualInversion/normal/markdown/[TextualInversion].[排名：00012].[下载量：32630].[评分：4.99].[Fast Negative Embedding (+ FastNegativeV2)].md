## Fast Negative Embedding (+ FastNegativeV2)
### 一、模型概述

- 标签：`negative`, `negative embedding`, `textual inversion`, `embedding`, `tool`
- 下载数：32630
- 收藏人数：2891
- 评论人数：29
- 评分人数：79
- 评分：4.99

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] v2

- 统计数据
  - 发布时间：2023-06-11T19:54:48.446Z
  - 原始模型：SD 1.5
  - 下载数：17767
  - 评分人数：27
  - 评分：4.96
- 下载地址
  - [FastNegativeV2.pt](https://civitai.com/api/download/models/94057)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/966617fd-89bc-4909-b51b-c4558af5aaf7/width=450/1113092.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fdbc324d-b0a2-4285-aee7-fc0c3de2f57b/width=450/1113093.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/658c662e-2448-4427-8618-c1e2868783a3/width=450/1113099.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/becb9146-8ab8-4ebc-b51a-105bcbcdd2f1/width=450/1113125.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] v1.0 Normal [preferred for styles]

- 统计数据
  - 发布时间：2023-06-11T19:50:33.824Z
  - 原始模型：SD 1.5
  - 下载数：12463
  - 评分人数：46
  - 评分：5
- 下载地址
  - [FastNegativeEmbedding.pt](https://civitai.com/api/download/models/76712)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e6877c99-6167-48b7-883f-f78b516b3416/width=450/886029.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e5417bf6-0f79-4036-aa94-a44d5857676e/width=450/865879.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cd1cb436-07ba-4815-b457-9eeb0e0467d8/width=450/862630.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d0a4b3f5-e47b-4f78-a2d0-5e7963d1baed/width=450/865652.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] v1.0 Strong

- 统计数据
  - 发布时间：2023-06-11T19:50:33.824Z
  - 原始模型：SD 1.5
  - 下载数：2400
  - 评分人数：6
  - 评分：5
- 下载地址
  - [FastNegativeEmbeddingStrong.pt](https://civitai.com/api/download/models/76985)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0c11c0a7-88a6-4b70-8d4e-636c06b9d6a9/width=450/865642.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a48a1de5-0b32-416a-83ee-152d3e9b438a/width=450/863859.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d2112e6a-a1fd-41eb-9212-7accbc162cd3/width=450/863288.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c6780899-7829-496a-82a7-60ba51e75ca3/width=450/865875.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-94">Fast Negative Embedding</h1><p><strong>Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong><br /></p><p>Token mix of my usual negative embedding. This way it's faster to use and easier to reproduce.</p><p>I'm also working on a much stronger one that doesn't preserve styles but it's good on base models without style loras applied. I plan to upload it during the next week, so be sure to leave a ❤️ to be notified of future updates.</p><p><s>This is very much a </s><strong><s>work in progress</s></strong><s>, but since I'm already using it in examples, I thought I should upload it.</s></p><p>It should keep styles on all my style loras. If not please tell me in the comments. <br />Additionally, if you find this too overpowering, use it with weight, like <code>(FastNegativeEmbedding:0.9)</code>.</p><p><strong>Update: </strong>added <code>FastNegativeV2</code>. It shouldn't be necessary to lower the weight.</p><p></p><p>Of course, don't use this in the positive prompt.<br />This includes Nerf's <a target="_blank" rel="ugc" href="https://civitai.com/models/56519/negativehand-negative-embedding">Negative Hand</a> embedding.</p><p></p>