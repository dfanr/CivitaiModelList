## djz Junglepunk V21
### 一、模型概述

- 标签：`junglepunk`, `style`
- 下载数：229
- 收藏人数：83
- 评论人数：0
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] 0

- 统计数据
  - 发布时间：2023-01-07T00:29:28.966Z
  - 原始模型：SD 2.1 768
  - 下载数：229
  - 评分人数：1
  - 评分：5
- 下载地址
  - [djzJunglepunkV21_0.safetensors](https://civitai.com/api/download/models/4458)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7a7b0585-35df-4882-d839-9cabf0a92800/width=450/30285.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9ea0eade-0da6-4e3a-b378-158e72ffaf00/width=450/30720.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8de9f80f-efa8-4ad5-4866-f958b77eaf00/width=450/30284.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0bc7e080-9bde-4dbc-ef09-d85535a03c00/width=450/30719.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>An example of a good merged result using <a rel="ugc" href="https://civitai.com/models/4043/djz-airlock-v21">djzAirlockV21</a> &amp; <a rel="ugc" href="https://civitai.com/models/3410/rick-roll-style">Rick-Roll</a>:</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/43314448-2eb4-4602-bed0-9dfd0dec5800/width=525" /><p>source: <a rel="ugc" href="https://civitai.com/user/DriftJohnson">DriftJohnson</a></p><p>but how was that achieved?</p><ul><li><p><strong>rick-roll+airlock 0.5</strong></p></li><li><p><strong>rick-roll+junglepunk 0.5</strong></p></li><li><p>Then combine the two resulting models at 0.5<br /></p></li></ul><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e648f3ad-506d-42e7-f082-62b5507f8d00/width=525" /><p>special thanks to: <a rel="ugc" href="https://civitai.com/user/RickInversion">RickInversion</a><br /></p><p>These "strong style" Models are intended to be merged with each other and any model for Stable Diffusion 2.1</p><p>I recommend merging with 0.5 (50/50 blend) then using prompt weighting to control the Aesthetic gradient.</p><p>example merged model prompt with automatic1111:</p><p><strong>(Junglepunk:1.2) (yourmodeltoken:0.8)</strong></p><p>if you drop the "djz" and the "V21" what remains is the token you need to call up the concept in the model. All examples shown were the Raw Token, no other words. Tokens are case sensitive and in almost all models it will match the filename.</p><p>It is possible to merge these models with each other using a different value. It is possible to pair models and then merge those resulting models. In this way we can blend abstract concepts together and then weight the tokens to achieve the result we may wish to create. Of course to eliminate all those tokens, you can simply train a new custom model from the outputs, which means you are back to a single token.</p><p>A video explanation will follow, but for now the above explanation should do. We are focused on getting as many style/aesthetic models into artist hands to enhance the creativity already at their finger tips.</p><p>Art Freedom for all!!</p><p>[all original artwork used for training with <a target="_blank" rel="ugc" href="https://twitter.com/MushroomFleet/status/1609633158864961539">full permission from Drift Johnson</a>]</p><p></p>