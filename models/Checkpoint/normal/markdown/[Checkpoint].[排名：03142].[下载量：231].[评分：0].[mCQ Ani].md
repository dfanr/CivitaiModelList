## mCQ Ani
### 一、模型概述

- 标签：`character`, `general purpose`, `fantasy`, `2.5d`
- 下载数：231
- 收藏人数：73
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-05T05:30:30.400Z
  - 原始模型：SD 1.5
  - 下载数：231
  - 评分人数：0
  - 评分：0
- 下载地址
  - [mcqAni_v10.safetensors](https://civitai.com/api/download/models/36623?type=Model&format=SafeTensor&size=full&fp=fp32)
  - [mcqAni_v10.safetensors](https://civitai.com/api/download/models/36623)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/41339d04-a016-4d05-5ba8-0ace37ede700/width=450/426522.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8a06f0b1-bd65-4d70-b107-032c82244800/width=450/426521.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fabc6b7f-415c-42cc-c9ab-5a4b4fca7e00/width=450/426519.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/61eae1b6-1273-4e17-52c5-35ebb62dbc00/width=450/426518.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Non-photorealistic version of the <a target="_blank" rel="ugc" href="https://civitai.com/models/30296/mcq">mCQ</a> model.</p><p>I'll update the description if this goes anywhere, including the recipe.</p><p>I used <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt">vae-ft-mse-840000-ema-pruned.ckpt</a> for all image gens.</p><p><strong>Pruned Model fp16 has baked in VAE.</strong></p><p>Might be a good idea to include sfw/nsfw respectively into prompt/negative prompt depending on what you're looking for.</p><p>(note, I'm running macOS 13.3, python: 3.10.10, torch: 2.1.0.dev20230326 as of posting this)</p>