## HighRiseMix
### 一、模型概述

- 标签：`anime`, `mix`, `buildings`, `cityscape`, `mixed model`, `2d`
- 下载数：3051
- 收藏人数：877
- 评论人数：4
- 评分人数：6
- 评分：5

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] HighRiseMixV2.5

- 统计数据
  - 发布时间：2023-02-15T00:22:15.408Z
  - 原始模型：SD 1.5
  - 下载数：2083
  - 评分人数：3
  - 评分：5
- 下载地址
  - [highrisemix_v25.safetensors](https://civitai.com/api/download/models/10565)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/49ad73f5-6832-4fc9-14d4-9c416bca8700/width=450/102666.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/262f2166-cae0-43a3-a792-f6597cfe5100/width=450/102630.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6bfe816e-347b-4dc7-1468-a89f9d927c00/width=450/102629.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e6fe4881-5e82-4cd2-2f7f-45104e460900/width=450/102628.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] HighRiseMixV2

- 统计数据
  - 发布时间：2023-02-15T00:22:15.408Z
  - 原始模型：SD 1.5
  - 下载数：576
  - 评分人数：0
  - 评分：0
- 下载地址
  - [highrisemix_v2.safetensors](https://civitai.com/api/download/models/9616)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8e75d0c6-f437-4f44-fd0f-2bf9cd6ae100/width=450/92918.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7abde6b1-2555-449d-5bd4-2d9eabfb1400/width=450/92917.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/39776bf6-8a25-490f-c8be-f58817cdb300/width=450/92916.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c7fc8c3d-3633-48bf-4087-f9cbe7890200/width=450/92915.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] HighRiseMixV1

- 统计数据
  - 发布时间：2023-02-15T00:22:15.408Z
  - 原始模型：SD 1.5
  - 下载数：392
  - 评分人数：3
  - 评分：5
- 下载地址
  - [highrisemix_v1.safetensors](https://civitai.com/api/download/models/8744)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/21570102-7592-49cf-dc1c-98dbfada5d00/width=450/83270.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b324c526-cd83-4488-094d-98e50ba08a00/width=450/83277.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4b3424fd-730a-4c6d-24f2-499eb4c36800/width=450/83276.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0900aa3b-0413-4f0e-dc1d-ac3d4ac9d300/width=450/83275.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>U-Net mixed model <strong>specialized for city and skyscrapers background.</strong></p><p></p><p><strong>V1</strong> really focuses on drawing tall skyscrapers.</p><p></p><p><strong>V2 and V2.5</strong> focus more on details of interiors, and not try to draw many many skyscrapers than V1.</p><p></p><p><strong>FP16 Pruned version</strong>(No EMA).</p><p>(Quality change may occur in very small details on buildings' textures)</p><p></p><p><strong>Recommended prompts :</strong></p><p>(masterpiece, best quality, excellent quality), ((1girl, solo)), sky, city, (skyscrapers), trees, pavement, lens flare</p><p></p><p>EasyNegative, moss, phone, man, pedestrians, extras, border, outside border, white border</p><p></p><p>(EasyNegative is a negative embedding : <a target="_blank" rel="ugc" href="https://huggingface.co/datasets/gsdf/EasyNegative">https://huggingface.co/datasets/gsdf/EasyNegative</a>)</p><p></p><p><strong>Recommended settings :</strong></p><p>Sampler : DPM++ 2M Karras OR DPM++ SDE Karras</p><p>Sampling steps : 25 ~ 30</p><p>Resolution : 512x768 OR 768x512</p><p>CFG Scale : 9</p><p></p><p><strong>Upscale is a must-do!! </strong>Otherwise, you won't get great results.</p><p>Upscaler : Latent (nearest)</p><p>Hires steps : 0</p><p>Denoise : 0.6</p><p>Upscale 2x</p><p></p><p><strong>Mixed models :</strong></p><p>V1 : AbyssOrangeMix2_NSFW, AnythingV4.5, BasilMixFixed, CounterfeitV2.5, EerieOrangeMix2, PowercolorV2</p><p>V2 : V1 + AikimiXPv1.0, CounterfeitV2.0, pastelmix-better-vae</p><p>(Thanks to everyone who made above models!)</p><p>V2.5 : V2 + AikimiXCv1.5</p><p></p><p>This is my first mixed model being uploaded to public site, so feel free to give feedbacks as you wish, I'll try and work around with it.</p><p></p>