## djz Weather Control
### 一、模型概述

- 标签：`style`, `weather`, `control`, `djz`
- 下载数：49
- 收藏人数：12
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v21

- 统计数据
  - 发布时间：2023-03-31T10:58:29.410Z
  - 原始模型：SD 2.1 768
  - 下载数：49
  - 评分人数：0
  - 评分：0
- 下载地址
  - [djzWeatherControl_v21.safetensors](https://civitai.com/api/download/models/32260)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cb0c1303-be4f-42c3-8a9f-4e1ad1638f00/width=450/367351.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/43c65149-9242-45fd-a961-5df9673c2900/width=450/367360.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ad974169-0d14-4685-c93e-9272a7b31000/width=450/367359.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9affd298-8e4a-42df-46ac-1387d0e8c000/width=450/367358.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Demo images use <a target="_blank" rel="ugc" href="https://civitai.com/models/20517/danger-zoo-johnsons-negative-embeddings-helper-collection">Danger Zoo ~ Johnsons Negative TI Collection ~</a><br />Lora: <a target="_blank" rel="ugc" href="https://civitai.com/models/19814">djzWeatherControl</a><br /><br />These "strong style" Models are intended to be merged with each other and any model for Stable Diffusion 2.1</p><p>I recommend merging with 0.5 (50/50 blend) then using prompt weighting to control the Aesthetic gradient.</p><p>example merged model prompt with automatic1111:</p><p><strong>(weathercontrol:1) (othermodeltoken:1)</strong></p><p>if you drop the "djz" and the "V21" what remains is the token you need to call up the concept in the model. All examples shown were the Raw Token, no other words. Tokens are case sensitive and in almost all models it will match the filename.</p><p>It is possible to merge these models with each other using a different value. It is possible to pair models and then merge those resulting models. In this way we can blend abstract concepts together and then weight the tokens to achieve the result we may wish to create. Of course to eliminate all those tokens, you can simply train a new custom model from the outputs, which means you are back to a single token.</p>