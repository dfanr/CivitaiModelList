## djz Rainbow Fusion
### 一、模型概述

- 标签：`fusion`, `style`, `rainbow`, `djz`
- 下载数：65
- 收藏人数：9
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v21

- 统计数据
  - 发布时间：2023-03-31T10:52:46.217Z
  - 原始模型：SD 2.1 768
  - 下载数：65
  - 评分人数：0
  - 评分：0
- 下载地址
  - [djzRainbowFusion_v21.safetensors](https://civitai.com/api/download/models/32256)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8a5bf8c6-f6a1-4292-5d2c-8ededbc4ee00/width=450/367325.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/552d0ffa-c628-4e9a-2ead-f728a8b5d200/width=450/367332.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e05bf065-560f-43eb-083d-5de3e81cf900/width=450/367333.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ab4e8422-0aae-4ad1-3c94-88fca2dc9200/width=450/367331.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Demo images use <a target="_blank" rel="ugc" href="https://civitai.com/models/20517/danger-zoo-johnsons-negative-embeddings-helper-collection">Danger Zoo ~ Johnsons Negative TI Collection ~</a><br />Lora: <a target="_blank" rel="ugc" href="https://civitai.com/models/19884/djz-rainbow-fusion">djzRainbowFusion</a><br /><br />These "strong style" Models are intended to be merged with each other and any model for Stable Diffusion 2.1</p><p>I recommend merging with 0.5 (50/50 blend) then using prompt weighting to control the Aesthetic gradient.</p><p>example merged model prompt with automatic1111:</p><p><strong>(rainbowfusion:1) (othermodeltoken:1)</strong></p><p>if you drop the "djz" and the "V21" what remains is the token you need to call up the concept in the model. All examples shown were the Raw Token, no other words. Tokens are case sensitive and in almost all models it will match the filename.</p><p>It is possible to merge these models with each other using a different value. It is possible to pair models and then merge those resulting models. In this way we can blend abstract concepts together and then weight the tokens to achieve the result we may wish to create. Of course to eliminate all those tokens, you can simply train a new custom model from the outputs, which means you are back to a single token.</p>