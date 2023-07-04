## oneThirdMix
### 一、模型概述

- 标签：`anime`, `character`, `male`, `boys`
- 下载数：100
- 收藏人数：22
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-28T12:58:08.585Z
  - 原始模型：SD 1.5
  - 下载数：100
  - 评分人数：0
  - 评分：0
- 下载地址
  - [onethirdmix_v10.safetensors](https://civitai.com/api/download/models/72834)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/12f4614a-dba7-49b5-8646-9b63f065c25e/width=450/1321038.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3a6d888d-2a52-4d10-a2a4-b064f4b0cd1c/width=450/1321053.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2520e7b9-efc7-4644-8ac5-b80766fbc024/width=450/1295393.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fa30a759-5ebf-48ae-b91d-f119a9dd3abc/width=450/1295392.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2 id="heading-2"><strong>日本語の説明はnoteをご覧ください。</strong></h2><p><a target="_blank" rel="ugc" href="https://note.com/sanb_noichi/n/n6d4a6a7becb9">https://note.com/sanb_noichi/n/n6d4a6a7becb9</a></p><p></p><h2 id="heading-26">Features:</h2><ul><li><p>its specifically tuned for generating boy characters</p></li><li><p>it excels in realistic situations but is somewhat unsuitable for fantasy situations</p></li><li><p>PHOTO-REALISTIC or NSFW outputs were not considered, and verified during the development</p></li></ul><p></p><h2 id="heading-27">Tutorial:</h2><p>shorter prompts tend to result in good outputs.</p><p><strong>recommended to use any VAE.</strong> I usually generate with the <a target="_blank" rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/tree/main/vae">kl-f8-anime2</a></p><pre><code>Sampling method   : DPM++2M Karras 
Sampling steps    : 40 - 100 
CFGScale          : 7 - 10 
Clip Skip         : 2

Hires.fix         : enabled
Upscaler          : SwinlR4×
Hires steps       : 40 - 100
Denoising strength: 0.1 - 0.3</code></pre><p><strong>DO NOT set the sampling steps value to smaller than 40.</strong></p><p>it makes poor elbows, knees, and anywhere.</p><p></p>