## Final Fantasy VII Remake Style (Unreal Engine 4) LoRA
### 一、模型概述

- 标签：`3d`, `3d render`, `ff7`, `unreal engine`, `final fantasy vii remake`, `unreal engine 4`, `style`, `game character`, `semi-realistic`, `video game`
- 下载数：7058
- 收藏人数：1313
- 评论人数：16
- 评分人数：10
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] NED offset

- 统计数据
  - 发布时间：2023-05-02T23:42:19.926Z
  - 原始模型：SD 1.5
  - 下载数：3589
  - 评分人数：7
  - 评分：5
- 下载地址
  - [ff7r_style_ned_offset.safetensors](https://civitai.com/api/download/models/60948)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1319c5b7-501d-4e25-b106-ea6b3b87f6c3/width=450/667928.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a9a8ec6e-7764-4606-98a2-3de15e4fea13/width=450/801106.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/17070101-b836-4cbc-8dfd-ac8d6eb51e20/width=450/667938.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/58cac222-2861-4ab1-8a95-12f65a58a6f2/width=450/667936.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1

- 统计数据
  - 发布时间：2023-05-02T23:36:40.375Z
  - 原始模型：SD 1.5
  - 下载数：3469
  - 评分人数：3
  - 评分：5
- 下载地址
  - [ff7.safetensors](https://civitai.com/api/download/models/8493)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fd43b665-c32b-4e39-97ce-05bf23f30400/width=450/80654.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a7ff539c-f782-483d-afe8-89a43f035300/width=450/80657.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2ed0a9b6-128a-4d44-7b27-387707a68100/width=450/80642.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a5b36d10-dda3-4c69-ff4b-9d71b1d29e00/width=450/80656.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2>Final Fantasy VII Remake style (UE4) LoRA</h2><p><strong>Making models can be expensive. Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong></p><p><br /><strong>UPDATE: Retrained on NED.</strong></p><ul><li><p>For v1 a<strong> weight around 0.65</strong> works fine from my tests. Triggers with <code>ff7r style</code>.</p></li><li><p>For <strong>NED version</strong> use weight 1 on <a target="_blank" rel="ugc" href="https://civitai.com/models/10028/neverending-dream-ned?modelVersionId=11925">Never Ending Dream (v1.0)</a>. Triggers with <code>ff7r style</code>.  I'll maybe train another one on NED 1.22 to make it accurate on that one too. </p></li></ul><p>Also this came up kind of biased towards FF7 characters, so while this is mainly a style LoRA, it could replicate characters from the main cast of the game fairly well without embeddings or additional LoRA.</p><p></p><p><strong>V1 original description: </strong><br />This is kind of experimental. I wanted to see if I could finetune an anime model to replicate the style of a game in Unreal Engine. I think this was kind of a success. It works on <strong>AbyssOrangeMixV2 </strong>with a normal negative prompt, or on <strong>AnyLoRA with my usual negative prompt</strong> <strong>with</strong> <strong>negative embeddings</strong> (but don't mix them up, as that neg prompt doesn't work well on AOM with this LoRA). See the examples for the various comparisons.</p><p><br /><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight</strong> (by default it's <code>:1</code> which is usually too high)</p></li></ul>