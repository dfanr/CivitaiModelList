## Tape Gag
### 一、模型概述

- 标签：`concept`, `bondage`, `bdsm`, `hentai`, `nsfw`
- 下载数：4326
- 收藏人数：815
- 评论人数：5
- 评分人数：2
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2.0

- 统计数据
  - 发布时间：2023-05-09T18:23:55.937Z
  - 原始模型：Other
  - 下载数：2868
  - 评分人数：1
  - 评分：5
- 下载地址
  - [tape_v8_pt2.safetensors](https://civitai.com/api/download/models/66499)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8e8139c1-9499-4329-9943-2375b02e62b3/width=450/738276.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d470ecad-1909-4a78-947b-3ea8ac0e1ac3/width=450/738275.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/de6447b8-edc9-4d13-8828-609e29dd31db/width=450/738292.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d9698316-5dfb-43ad-afe2-4b86405f49df/width=450/738304.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] tape gag v1.0

- 统计数据
  - 发布时间：2023-05-09T18:27:54.510Z
  - 原始模型：Other
  - 下载数：1458
  - 评分人数：1
  - 评分：5
- 下载地址
  - [tape_v4.safetensors](https://civitai.com/api/download/models/60323)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/35271128-c682-46b5-16c1-aea0dc4bd200/width=450/659029.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2f898b4a-1390-4f65-1308-b3bc27a4ef00/width=450/659039.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/293eaea4-cbf3-4576-8f16-b3e7817f4900/width=450/659045.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/acf98f9b-e99a-4ede-76f1-2b9a176c5400/width=450/659048.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>V2.0: Retrained so it's roughly the same number of steps but now 50% on a large dataset and 50% on a smaller cherry-picked one. Not strictly better than V1.0, but should affect the original prompts less than before.<br /><br />Pretty simple Lora that adds tape gags to characters when prompted. I made this and a couple earlier versions a while ago before there were others on here, but figured it was worth uploading anyways. I've mainly been using it on some bondage mixes using AOM and other anime-based models with reasonable results, though it still microwaves the image in certain models and with too many other Loras due to over-fitting. Also seems to be way worse on average outside of bust shots, so the preview pics are pretty boring as a result. I'd like to improve that, so feedback appreciated!</p><p>Can also be used through in-painting, but I find it rarely matches the face well in those cases. Tags such as "gag", "gagged", etc. were removed from the training set so only the trigger words would be necessary.</p><p>Recommended weight: 1.0 on bondage models, ~0.5-0.75 otherwise.</p><p>Recommended CFG: ~6-7</p><p></p><p>Models used are all some mix based off of bondage-v11: <a target="_blank" rel="ugc" href="https://civitai.com/models/34777/bondage-v11">https://civitai.com/models/34777/bondage-v11</a><br />Definitely check it out!</p><p></p><p>Specifically, the Meina model is:</p><p>meina-pro-mistoon-hll3.safetensors + bondage-v11 + v1-5-pruned-emaonly</p><p>Multiplier: 0.5</p><p>Add difference, copy config from A, B, or C</p>