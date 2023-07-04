## Pyra + Mythra + Pneuma (Xenoblade) LoRA
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `sexy`, `female`, `manga`, `pneuma`, `mythra`, `pyra`, `xenoblade chronicles 2`, `xenoblade`, `woman`, `cute`, `fantasy`, `game character`, `girls`, `video game`, `women`
- 下载数：10411
- 收藏人数：2115
- 评论人数：23
- 评分人数：26
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] hard

- 统计数据
  - 发布时间：2023-05-21T20:44:10.701Z
  - 原始模型：SD 1.5
  - 下载数：10275
  - 评分人数：26
  - 评分：5
- 下载地址
  - [mythra_pyra_pneuma-000050.safetensors](https://civitai.com/api/download/models/6009)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b66ea5b1-1ecc-4b49-d76a-c03ad668bc00/width=450/51393.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/54e69c36-8650-49bc-3d1a-f83877328000/width=450/51346.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/29490a8e-71cc-4dbc-89e4-2bfbd9e80724/width=450/866133.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6ece3b90-c7a6-4406-a523-34a22a30b300/width=450/51349.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] soft

- 统计数据
  - 发布时间：2023-05-21T20:44:20.395Z
  - 原始模型：SD 1.5
  - 下载数：136
  - 评分人数：0
  - 评分：0
- 下载地址
  - [mythra_pyra_pneuma-000042.safetensors](https://civitai.com/api/download/models/6013)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7a900563-dfac-4c49-1944-c001febe3e00/width=450/51392.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ececb975-d98e-4886-d240-7274178d7b00/width=450/51391.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0b5f9127-4cab-45e7-89c7-7219ee81f700/width=450/51390.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<h2>Pyra + Mythra + Pneuma (Xenoblade) LoRA</h2><p><strong>Making models can be expensive. Do you like what I do? Consider supporting me on </strong><a target="_blank" rel="ugc" href="https://www.patreon.com/Lykon275"><strong>Patreon</strong></a><strong> 🅿️ or feel free to </strong><a target="_blank" rel="ugc" href="https://snipfeed.co/lykon"><strong>buy me a coffee</strong></a><strong> ☕</strong></p><p>This was requested by a user, but it was already in my backlog so I just bumped the priority. Came out pretty good. Didn't expect to get also Pneuma, as it was just in maybe 10% of the dataset (and she is definitely less accurate than the other 2, who came out perfectly).<br /><br />Triggers are <code>pyra \(xenoblade\)</code>, <code>mythra \(xenoblade\)</code>, and <code>pneuma \(xenoblade\)</code>. As for the <strong>weight</strong>, I don't think it's wise to go over <strong>0.5</strong> (check the matrix at the end of the gallery), sweet spots seems to be <strong>between 0.4 and 0.6</strong>.<br /></p><p>I could also make this work with latent couple and controlnet to get both girls in the same image: <a target="_blank" rel="ugc" href="https://imgur.com/a/XMIYH2I">https://imgur.com/a/XMIYH2I</a> (pnginfo: <a target="_blank" rel="ugc" href="https://pastebin.com/qmd8xP0q">https://pastebin.com/qmd8xP0q</a>).<br /><br />I'm also uploading the 42 epoch version because it rarely gave better results, so why not. <strong>I've added comparisons in the v42 tab</strong>. <br /><br /><strong>How to use LoRA's in auto1111:</strong></p><ul><li><p>Update webui (use <code>git pull</code> <a target="_blank" rel="ugc" href="https://www.youtube.com/embed/mn8fMF10XN4?start=31&amp;end=60">like here</a> or redownload it)</p></li><li><p>Copy the file to <code>stable-diffusion-webui/models/lora</code></p></li><li><p>Select your LoRA like in <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=-bMeyXOZwN0">this video</a></p></li><li><p><strong>Make sure to change the weight</strong> (by default it's <code>:1</code> which is usually too high)</p></li></ul>