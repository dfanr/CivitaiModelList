## MysticTurducken
### 一、模型概述

- 标签：`anime`, `sexy`, `style`, `nsfw`, `2.5d`
- 下载数：283
- 收藏人数：90
- 评论人数：1
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-09T05:50:44.845Z
  - 原始模型：SD 1.5
  - 下载数：283
  - 评分人数：2
  - 评分：5
- 下载地址
  - [mysticturducken_v10.safetensors](https://civitai.com/api/download/models/62473)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5af53275-f742-4e5e-b81b-571dcc63076f/width=450/688132.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b7b49c60-d2d0-47d3-988a-23149dd0a935/width=450/688134.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/35e02b96-a390-449c-9f7c-466610b3367f/width=450/688136.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9d33bba1-8dd1-402a-91c3-054fdf10c05a/width=450/688332.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is a merge of, well, merges. It consists of several models provided by the Unstable Diffusion community, as well as one of my own. It was pretty much a yolo merge on my part to see what would come of it, but I've been happy with the results and received a lot of good feedback on it, so I'm posting it here for others to get a chance to play with it.</p><p>It has a slight human bias (consider the source; it's milder than I expected,) and it excels at abstract themes, backgrounds, somehow pixel art, and of course nsfw stuff. I haven't thoroughly explored the potential of this merge, as it's existed for just over a day now.</p><p></p><p><strong>Known limitations:</strong></p><ul><li><p>Eyes are pretty messy when faces get to about the distance of a full-body shot. This is one of those models that needs a little hand-holding there, be it through highresfix, Ddetailer, or Adetailer.</p></li><li><p>Pixel art is surprisingly fantastic with this, but the effect tends to break down around the face where the model goes into a sort of tryhard mode and returns to its 2.5d roots. Adetailer or Ddetailer can be used to improve this case by using "pixelated" or "pixel art" in the prompt for either along with the usual face details you'd typically use with either tool.</p></li><li><p>Truly SFW content featuring women. While it is very possible to gen fully-clothed characters with this merge, you'll probably have to fight with the model to avoid things like excessive cleavage. While I tagged this model for mature themes only, it is entirely possible to use this solely for SFW purposes. You'll likely just find that harder to achieve than in other models that likely fit the task better.</p></li><li><p>Cats. You can get good cats on CLIP skip 2 and 3, but you probably won't be able to do so using a minimalist prompt without. Unfortunately, most of the style knowledge is in the outer layer, so that might be a pretty unadorned cat if you go that deep for it.</p></li></ul><p></p><p><strong>Components:</strong></p><ul><li><p>Senzubean's SenzusHolyshit merge (components unknown)</p></li><li><p>WildKeeper's WildsMix (components unknown)</p></li><li><p>My own HDDarkmode, which consists of</p><ul><li><p>Hentai Diffusion epoch 17</p></li><li><p>JWST Deep Space Diffusion</p></li><li><p>Double Exposure Diffusion</p></li><li><p>Noise Offset For True Darkness in SD</p></li><li><p>My Kan Liu LoRA merged in at a low weight</p><ul><li><p>Many of the components were added through block weighted merging early on, before things like recipe logging were added, so the exact details were lost to time like a day after I whammed the first parts of that together back in November.</p></li></ul></li></ul></li></ul>