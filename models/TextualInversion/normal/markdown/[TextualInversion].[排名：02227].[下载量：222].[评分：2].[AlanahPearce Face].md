## AlanahPearce Face
### 一、模型概述

- 标签：`girl`, `person`, `textual inversion`, `youtuber`, `twitch`, `streamer`, `woman`, `celebrity`, `embedding`, `faces`, `realistic`, `face`
- 下载数：222
- 收藏人数：21
- 评论人数：6
- 评分人数：1
- 评分：2

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v0.1-positive

- 统计数据
  - 发布时间：2023-06-10T16:49:28.469Z
  - 原始模型：SD 1.5
  - 下载数：165
  - 评分人数：1
  - 评分：2
- 下载地址
  - [alanah_pearce.pt](https://civitai.com/api/download/models/89443)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ffd26335-3467-4011-a648-8c0c7ef87101/width=450/1034333.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ac946349-263c-4e3b-a172-aa6005803d39/width=450/1035339.jpeg" /> |
| ---- | ---- |

#### [版本1/共2个版本] v0.1-negative

- 统计数据
  - 发布时间：2023-06-10T16:49:28.469Z
  - 原始模型：SD 1.5
  - 下载数：57
  - 评分人数：0
  - 评分：0
- 下载地址
  - [alanah_pearce-neg.pt](https://civitai.com/api/download/models/93178)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d06c4f34-034c-4604-bcb1-497ad058eb97/width=450/1098697.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/103f6b70-2d59-463c-89e1-8760b8b0a9cd/width=450/1098698.jpeg" /> |
| ---- | ---- |


### 三、详情
<p>I trained a Textual Inversion model on one of my favorite youtubers turned game designer, Alanah Pearce, and after some tinkering I was able to get some decent gens out of it so it's time to share.</p><p>I seem to get best results by using the keyword as <code>((alanah_pearce:0.89))</code> at least when using <a target="_blank" rel="ugc" href="https://civitai.com/models/55036?modelVersionId=70989">fitCorderMixV2.1 </a>as my checkpoint. (NOTE: <code>((alanah_pearce_face:0.89))</code> also works and provides slightly different results, try it out. Both are pretty touchy and like to either overburn, or look nothing like her. YMMV with other models. (<a rel="ugc" href="https://civitai.com/models/4884?modelVersionId=5618">GalaxyTimeMachineV3</a> also produced some decent results)</p><p>The negative embedding is optional, it may help with some models, and it may hinder you with others. Try with and without it, and try modifying the strength of the negative embed in contrast with the strength of the positive embedding until something comes together decently.</p><p>This was trained on a set of 32 images pulled from public sources (Reddit, Instagram, YouTube) using A1111's "Train" tab for embeddings. I unfortunately don't recall the specific settings used, but there's definitely still room for improvement on this one.</p>