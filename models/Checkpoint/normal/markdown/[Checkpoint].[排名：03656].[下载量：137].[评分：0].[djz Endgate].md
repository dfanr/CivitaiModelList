## djz Endgate
### 一、模型概述

- 标签：`style`, `djz`, `endgate`
- 下载数：137
- 收藏人数：78
- 评论人数：2
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v21

- 统计数据
  - 发布时间：2023-04-09T15:29:09.456Z
  - 原始模型：SD 2.1 768
  - 下载数：137
  - 评分人数：0
  - 评分：0
- 下载地址
  - [djzEndgate_v21.safetensors](https://civitai.com/api/download/models/32635)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ac6ba790-6b9d-4854-5f91-34a235d7e300/width=450/371856.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a602aea3-64f4-4896-2a66-6772f9d40700/width=450/371855.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7b49f74f-eaa8-413f-91c8-9d1534173600/width=450/371854.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d67c9856-81dc-457d-801c-7241121c5900/width=450/371853.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Demo images use <a target="_blank" rel="ugc" href="https://civitai.com/models/20517/danger-zoo-johnsons-negative-embeddings-helper-collection">Danger Zoo ~ Johnsons Negative TI Collection ~</a><br />Lora version <a target="_blank" rel="ugc" href="https://civitai.com/models/19216/djz-end-gate">djzEndGate</a><br /><br />These "strong style" Models are intended to be merged with each other and any model for Stable Diffusion 2.1</p><p>I recommend merging with 0.5 (50/50 blend) then using prompt weighting to control the Aesthetic gradient.</p><p>example merged model prompt with automatic1111:</p><p><strong>(endgate:1) (othermodeltoken:1)</strong></p><p>if you drop the "djz" and the "V21" what remains is the token you need to call up the concept in the model. All examples shown were the Raw Token, no other words. Tokens are case sensitive and in almost all models it will match the filename.</p><p>It is possible to merge these models with each other using a different value. It is possible to pair models and then merge those resulting models. In this way we can blend abstract concepts together and then weight the tokens to achieve the result we may wish to create. Of course to eliminate all those tokens, you can simply train a new custom model from the outputs, which means you are back to a single token.</p>