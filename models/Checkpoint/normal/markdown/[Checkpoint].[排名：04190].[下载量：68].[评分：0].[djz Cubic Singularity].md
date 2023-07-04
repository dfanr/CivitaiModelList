## djz Cubic Singularity
### 一、模型概述

- 标签：`style`, `singularity`, `cubic`, `djz`
- 下载数：68
- 收藏人数：16
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v21

- 统计数据
  - 发布时间：2023-03-31T11:03:12.011Z
  - 原始模型：SD 2.1 768
  - 下载数：68
  - 评分人数：0
  - 评分：0
- 下载地址
  - [djzCubicSingularity_v21.safetensors](https://civitai.com/api/download/models/32236)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/352811a8-bfe7-4bae-7a0a-61c3a9fc0600/width=450/367083.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c96246ac-33ce-46c7-ed72-d32ff4fd1200/width=450/367092.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7aef9905-4cbb-417d-2353-08c56725ad00/width=450/367091.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2b6225bf-a5fc-4967-206d-3e8206546100/width=450/367090.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Demo images use <a target="_blank" rel="ugc" href="https://civitai.com/models/20517/danger-zoo-johnsons-negative-embeddings-helper-collection">Danger Zoo ~ Johnsons Negative TI Collection ~</a><br />Lora: <a target="_blank" rel="ugc" href="https://civitai.com/models/20464">djzCubicSingularity</a><br /><br />These "strong style" Models are intended to be merged with each other and any model for Stable Diffusion 2.1</p><p>I recommend merging with 0.5 (50/50 blend) then using prompt weighting to control the Aesthetic gradient.</p><p>example merged model prompt with automatic1111:</p><p><strong>(cubicsingularity:1) (othermodeltoken:1)</strong></p><p>if you drop the "djz" and the "V21" what remains is the token you need to call up the concept in the model. All examples shown were the Raw Token, no other words. Tokens are case sensitive and in almost all models it will match the filename.</p><p>It is possible to merge these models with each other using a different value. It is possible to pair models and then merge those resulting models. In this way we can blend abstract concepts together and then weight the tokens to achieve the result we may wish to create. Of course to eliminate all those tokens, you can simply train a new custom model from the outputs, which means you are back to a single token.</p>