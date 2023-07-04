## Bulma Brief (Older versions: DBZ start, Namek, Cell, Buu, Super and Res of Freezer) - Dragon Ball Z and Super
### 一、模型概述

- 标签：`anime`, `character`, `dragon ball z`, `female`, `dragon ball super`, `woman`, `anythingv4.5`
- 下载数：861
- 收藏人数：138
- 评论人数：3
- 评分人数：1
- 评分：4

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-03-30T21:37:54.127Z
  - 原始模型：SD 1.5
  - 下载数：861
  - 评分人数：1
  - 评分：4
- 下载地址
  - [Buruma_Brief_older.safetensors](https://civitai.com/api/download/models/28485)
  - [data.zip](https://civitai.com/api/download/models/28485?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d5ea74ec-eda0-46bc-95a8-9871e75f0200/width=450/320772.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/20829a7c-3926-4d39-6ccf-e9b5d0950600/width=450/320776.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7a34be37-cb31-4d70-3b31-d8c07544a000/width=450/320778.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/76591830-1625-43ec-ce1e-edc9d918a500/width=450/320775.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Seems people wanted an older Bulma as it seems current LORAS are from <a target="_blank" rel="ugc" href="https://civitai.com/models/23401/young-bulma-brief-dragon-ball-or-lora">her pre DBZ self</a>.</p><p>You can see the different variants included in the XYZ graph.</p><p>I had ok-ish results in the .45 to .65 range. If you go too low you might be caught in the transition between the normal eye and Toriyama style eyes.</p><p></p><p>I had best results with: buruma_brief_older, &lt;insert one of the other Bulmas triggers here&gt;, large_breasts, blue_eyes, &lt;lora:Buruma_Brief_older:.5&gt;</p><p>Like this: buruma_brief_older, Buruma_Super_ResurrectionFreezer, large_breasts, blue_eyes, &lt;lora:Buruma_Brief_older:.5&gt;</p><p></p><p></p><p>The supported variations of bulma are:</p><ul><li><p>Buruma_DBZ_Start</p></li><li><p>Buruma_DBZ_Namek</p></li><li><p>Buruma_DBZ_Buu</p></li><li><p>Buruma_DBZ_Cell</p></li><li><p>Buruma_DBZ_FutureTimeline</p></li><li><p>Buruma_Super_start</p></li><li><p>Buruma_Super_ResurrectionFreezer</p></li><li><p>don't use any of them for a mixed style</p></li></ul><p></p><p>I added the tag summary inside the training data.</p><p></p><p>Creating this was annoying as hell, it came out overfit no matter what i did until i noticed that the noise(Saw a big honking watermark) wasn't from my training data. I cleaned it properly damn it!</p><p>Turns out the LORA was getting contaminated with the model's Bulma concept which is fugly and overtrained. This caused my LORA to be overfit from epoch 1.</p><p>Long story short after cleaning the dataset and tags and cooking it with different learning rates and coming up empty I found the watermark in the noise.</p><p>Finally "fixed" the issue by changing the triggers to the romanji spelling thus why they use Buruma. Also during one of the dataset shiftings ended up tagging everything by saga so you can more or less reliably make the LORA spit individual Bulmas from different story arcs.</p><p>Not my best work but one of the more annoying and time consuming, on the other hand it is flexible as hell.</p><p>It still seems a bit overfit but I am just a bit tired of it.</p><p></p>