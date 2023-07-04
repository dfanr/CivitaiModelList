## Nicki Minaj
### 一、模型概述

- 标签：`person`, `rapper`, `woman`
- 下载数：976
- 收藏人数：118
- 评论人数：0
- 评分人数：1
- 评分：3

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] NickiMinaj

- 统计数据
  - 发布时间：2023-02-11T01:09:02.241Z
  - 原始模型：SD 1.5
  - 下载数：976
  - 评分人数：1
  - 评分：3
- 下载地址
  - [NickiMinajV2.safetensors](https://civitai.com/api/download/models/9349)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/175fc04b-e738-4b36-7884-ca88a3d62200/width=450/89815.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/733a1438-286d-4862-60ff-37e40b17a800/width=450/89820.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/87684894-7965-425c-f037-1fdc2ec04300/width=450/89819.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8cd1ad97-9431-4fbf-e010-3c61cff6a700/width=450/89818.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>SD almost sorta kinda recognizes Nicki Minaj which has actually made getting a LoRA that'll produce a good facial likeness pretty difficult. I've adjusted my training data and tried this a few times with LoRA and Textual Inversion training. I've also tried it as a custom token vs. having the LoRA ride "on top" of the default SD data for her. It's still a little finicky but I think this version is good enough to release.</p><p></p><p>Since it's operating on top of SD's own understanding of Nicki Minaj it tends to like high-ish step counts (40+) and low-ish strength (under .5) but mostly it's just a bit of a moving target depending on the rest of the prompt. There's almost always some strength that gets you a good likeness but it sometimes requires some experimentation to get there. My suggestion would be to start around .4 strength and fiddle with it from there.</p><p></p><p>Last wrinkle is that it can also produce very light skin especially when combined with other LoRAs or strong embeddings. Use "black woman" or "African American woman" to combat that.</p>