## "Trending on ArtStation" trained without a dataset
### 一、模型概述

- 标签：`base model`, `art style`, `woman`, `illustration`, `artstyle`, `digital illustration`, `fantasy`, `portraits`
- 下载数：171
- 收藏人数：53
- 评论人数：13
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1

- 统计数据
  - 发布时间：2023-03-25T05:18:11.207Z
  - 原始模型：SD 1.5
  - 下载数：171
  - 评分人数：1
  - 评分：5
- 下载地址
  - [TrendingOnArtstation_v1.ckpt](https://civitai.com/api/download/models/27591?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [TrendingOnArtstation_v1.safetensors](https://civitai.com/api/download/models/27591)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6a1f9bca-107a-4288-091f-a41784b10900/width=450/304024.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/072b55ff-e1d4-454d-03db-0665f7b89600/width=450/304025.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/804cdc9f-d91e-44a8-aaf6-7f3e2f572900/width=450/304027.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4b4a4dfe-823b-4680-3e3e-51e3dafce100/width=450/304026.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>Training does not require a dataset, only words.</strong><br /><br />Trained in 2400 steps (about 7 hrs on 2 a6000s) using only text with:<br /><a target="_blank" rel="ugc" href="https://github.com/ntc-ai/conceptmod"><u>https://github.com/ntc-ai/conceptmod</u></a><br /><br /><strong>Training prompt for the first 2000 steps:</strong><br /><em>"=trending on artstation, 8k, ultra hd|boring=exciting|drab=captivating|1woman%generic woman wearing generic clothes:0.003|1woman%woman wearing many unique tasteful accessories and a cute outfit:-0.003|@monochrome--|@black and white--|@text--|@written words--"</em></p><ul><li><p>Pulls the unconditional towards "trending on artstation, 8k, ultra hd"</p></li><li><p><s>Replaces</s> Pulls "boring" to "exciting" and "drab" to "captivating".<br /><strong>Update: this doesn't replace. It pulls towards. Replace needs an additional % term, see the readme.md</strong></p></li><li><p>Reduces the occurrence of "monochrome", "black and white", "text", and "written words".</p></li><li><p>Slightly blends 1woman away from "generic woman wearing generic clothes"</p></li><li><p>Slightly blends 1woman towards "woman wearing many unique tasteful accessories and a cute outfit"<br /><strong>Update: I think these terms might be backwards. LOL</strong></p></li></ul><p><br /><strong>Training prompt for the next 400 steps:</strong><br /><em>"@#|1woman=ugly manly sad wretched:-0.1|1woman=woman wearing many unique tasteful accessories and a cute outfit|nipples--:0.1|cleavage--:0.01"</em></p><ul><li><p>Freezes the unconditional concept using the "@#" operator.</p></li><li><p>Reduces the occurrence of "nipples" by 0.1 and "cleavage" by 0.01.<br /></p></li></ul><p>Technique based on <a target="_blank" rel="ugc" href="https://github.com/rohitgandikota/erasing">https://github.com/rohitgandikota/erasing</a><br />Model based on <a target="_blank" rel="ugc" href="https://civitai.com/models/13565/criarcys-fantasy-to-experience">https://civitai.com/models/13565/criarcys-fantasy-to-experience</a></p>