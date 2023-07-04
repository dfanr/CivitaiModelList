## CamelliaMIx_2.5D
### 一、模型概述

- 标签：`anime`, `sexy`, `female`, `base model`, `woman`, `girls`, `semirealistic`
- 下载数：16233
- 收藏人数：3743
- 评论人数：25
- 评分人数：33
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] V2

- 统计数据
  - 发布时间：2023-05-23T14:56:24.345Z
  - 原始模型：SD 1.5
  - 下载数：15659
  - 评分人数：27
  - 评分：5
- 下载地址
  - [camelliamix25D_v2.safetensors](https://civitai.com/api/download/models/48859)
  - [vae-ft-mse-840000-ema-pruned.safetensors](https://civitai.com/api/download/models/48859?type=VAE&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e5c9ccde-ac2c-4b49-fa90-a55896e07d00/width=450/533875.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d693ef0d-8c3f-4a65-c056-e33a5b121300/width=450/533874.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/297cbcc8-fc11-452f-87d0-16a8f715b800/width=450/524614.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a18769e8-8355-4040-f0b8-692446e26e00/width=450/524607.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] V1

- 统计数据
  - 发布时间：2023-05-23T15:01:15.559Z
  - 原始模型：SD 1.5
  - 下载数：574
  - 评分人数：6
  - 评分：5
- 下载地址
  - [camelliamix25D_v1.safetensors](https://civitai.com/api/download/models/78938)
  - [camelliamix25D_v1.safetensors](https://civitai.com/api/download/models/78938?type=Model&format=SafeTensor&size=full&fp=fp32)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9dcd2307-4964-4b67-835e-360241bde325/width=450/884786.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8827a19d-9e98-4a60-a8c2-61997503a808/width=450/884797.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a56fd936-1cba-4fab-8fc4-07682358ad79/width=450/884784.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/64b5f605-8725-43ac-97d4-6368b579c889/width=450/884785.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>[Add V1 page for convenience of future updates. Will be an update soon]</strong></p><p></p><p>V2 is closer to 3D than V1<br />Shape of eyes and face have been changed</p><p>V2 is a slightly different style from V1</p><p></p><h2><strong>Merge model</strong></h2><p><a target="_blank" rel="ugc" href="https://civitai.com/models/44185/camelliamix25d">CamelliaMix_2.5D</a></p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/44315/camelliamixnsfw">CamelliaMIx_NSFW_V1.1</a></p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/4451/abyssorangemix2-hardcore">AbyssOrangeMix2_hard</a></p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/7371?modelVersionId=19575">revAnimated_v11</a></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/nuigurumi/basil_mix">Basil mix</a></p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/21133?modelVersionId=25739">sakimichanStyle_v15 LoRA</a></p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/14171/cutegirlmix4">cuteGirlMix4_v10 LoRA</a></p><p></p><h1>Process</h1><p>0.5(AbyssOrangeMix2_hard) + 0.5(revAnimated_v11) = A </p><p>0.6(CamelliaMIx_NSFW_V1.1) + 0.4 (A) = B</p><p>0.8(B) + 0.2(Basil mix) = C</p><p>C + 0.1(sakimichanStyle_v15) + 0.1(cuteGirlMix4_v10) = D</p><p>0.5(CamelliaMix_2.5D) + 0.5(D) = CamelliaMIx_2.5D_V2</p><p></p><h2><strong>Recommended setting</strong></h2><p>Sampling method : DPM++ SDE Karras</p><p>Clip skip : 2 </p><p>Hires steps : 13</p><p>Hires.fix upscaler : R-ESRGAN 4x+Anime6B </p><p>CFG Scale : 7~10</p><p>VAE : ft-mse-840000</p><p></p><h2><strong>Recommended prompt</strong></h2><p>Prompt : (masterpiece:1.2, best quality), (real picture, intricate details)</p><p>Negative : (worst quality, low quality:1.4), negative_hand-neg, verybadimagenegative</p><p><strong>Textual Inversion : </strong><a target="_blank" rel="ugc" href="https://civitai.com/models/56519/negativehand-negative-embedding">negative_hand-neg</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/11772?modelVersionId=25820">verybadimagenegative</a></p>