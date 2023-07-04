## AniMerge
### 一、模型概述

- 标签：`anime`, `base model`
- 下载数：684
- 收藏人数：160
- 评论人数：5
- 评分人数：1
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-02-19T18:06:04.529Z
  - 原始模型：SD 1.5
  - 下载数：607
  - 评分人数：1
  - 评分：5
- 下载地址
  - [animerge_v10.safetensors](https://civitai.com/api/download/models/8792)
  - [animerge_v10.safetensors](https://civitai.com/api/download/models/8792?type=Model&format=SafeTensor&size=full&fp=fp16)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/edd1bfab-b65e-44d1-fa21-c6d5ff4cbd00/width=450/122901.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f5b9df3b-2cec-4255-498e-175a81eb5400/width=450/122756.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fa9d53fe-512b-48c3-9032-7804ee086c00/width=450/84287.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6277bfbf-4757-4099-d4f3-8bde9addc800/width=450/84286.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0-inpainting

- 统计数据
  - 发布时间：2023-02-19T18:06:04.529Z
  - 原始模型：SD 1.5
  - 下载数：77
  - 评分人数：0
  - 评分：0
- 下载地址
  - [animerge_v10-inpainting.safetensors](https://civitai.com/api/download/models/9318)
  - [animerge_v10-inpainting.yaml](https://civitai.com/api/download/models/9318?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/48cf02e6-2035-4d86-116a-c288e01b2800/width=450/89407.jpeg" /> |
| ---- |


### 三、详情
<p>didn't check how the default vae that's included is. <a target="_blank" rel="ugc" href="https://huggingface.co/AdamOswald1/Anything-Preservation/tree/main/vae"><strong>use anythingv3 vae</strong></a> (or whatever vae you want, i'm not your mom). you also probably wanna use clip skip 2.</p><p></p><p>uses custom merge method I found on reddit that should keep the strength of each model. uses 9 models.</p><p></p><p>I chose as many models as I could that looked good. First step merge is using trained models, second step is trained and merged models, third step is merged models, and forth step is merging those together.</p><p></p><p>if you feel like sending me a tip you can do so here; <a target="_blank" rel="ugc" href="https://www.buymeacoffee.com/xzuyn">https://www.buymeacoffee.com/xzuyn</a>. although your money is probably better spent elsewhere.</p>