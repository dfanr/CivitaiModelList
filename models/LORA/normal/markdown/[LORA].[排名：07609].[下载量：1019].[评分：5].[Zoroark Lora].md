## Zoroark Lora
### 一、模型概述

- 标签：`character`, `nintendo`, `video game character`, `furry`, `pokemon`, `video game`, `pokemon legends`, `hisuian zoroark`, `zoroark`
- 下载数：1019
- 收藏人数：173
- 评论人数：1
- 评分人数：1
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] Zoroark Lora (Anything v3 Based)

- 统计数据
  - 发布时间：2023-03-29T04:59:22.740Z
  - 原始模型：SD 1.5
  - 下载数：906
  - 评分人数：1
  - 评分：5
- 下载地址
  - [zoroark_AT3.safetensors](https://civitai.com/api/download/models/30509)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ac56e068-13eb-4ae1-cdb8-81e1beb73100/width=450/346432.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6cb86b0e-388a-4bfa-3e4c-51e691471400/width=450/346433.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2cc19f71-a478-409b-a58f-8a875fbacf00/width=450/346430.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d48a39a4-95b7-42cb-a98c-889efa744500/width=450/346435.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] Zoroark Lora (AbyssOrangeMix3 Based)

- 统计数据
  - 发布时间：2023-03-29T04:59:22.740Z
  - 原始模型：SD 1.5
  - 下载数：113
  - 评分人数：0
  - 评分：0
- 下载地址
  - [zoroark_AOM3.safetensors](https://civitai.com/api/download/models/30510)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f9b16132-1c68-448c-13ce-2dae309b4700/width=450/346436.jpeg" /> |
| ---- |


### 三、详情
<p>Hey there, this is a somewhat-complete Lora for the Pokémon zoroark and its edgy ancestor hisuian zoroark. I say semi-complete as it works well but I feel that it could use some tweaking since it's my first Lora training. I ran 32 hand-captioned images from Pixiv, Gelbooru, and e621 (24 normal, 8 hisuian). The best part is that there's no hardcore rule34 in here. It was <em>extremely</em> difficult to pull that off, but now it's (marginally) unlikely to do a silly and generate unprompted nsfw when using anatomical terms. It still can though, so negative prompt accordingly or the inherently-nsfw-generator gonna inherently-nsfw.</p><p></p><p>I've attached 2 versions: an Anything-v3 and AbyssOrangeMix3-based version. The AT3 is super compatible since most models use a mix with it or share some commonality. AOM3 is also widely used but I trust it less since I didn't test it as much over a super wide range and it's based on AOM3, which is super temperamental and mostly sucks. I've had good results with Anything v4.5 and incredible ones with SevensMix, which is highly compatible with most Lora's. <strong><em>Both should be used at around 0.7-0.8 strength.</em></strong></p><p></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/andite/anything-v4.0/tree/main">Anything v4.5</a></p><p>Seven's Mix [civitai links are not allowed on civitai, just search it]</p><p></p><p><strong>Issues, grievances, and nitpicks:</strong></p><p>I'd like to call this a work-in-progress for now since I have plans to up the training from 768x768 to 1024x1024 images by using CPU and a lot of RAM, however that may take literal weeks so I'd like to hear from you people if the quality has any issues. I also need to grab full-res versions of the images since some of the ones I'm using are high-res but a tad compressed. Two issues currently are that hisuian zoroarks' eyes are hit-or-miss, likely because their microscopic pupils are lost in image compression; and occasionally a little pedestal appears at the base of the subject due to a single image of 3D model I found. This can be annoying but occasionally does some really cool stuff (see image #2) and I'd like to make it either go away or be controllable, preferably the latter.</p>