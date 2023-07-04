## Uzumaki Himawari (Boruto: Naruto Next Generations) LoRA
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `female`, `boruto: naruto next generations`, `uzumaki`, `himawari`
- 下载数：1231
- 收藏人数：225
- 评论人数：4
- 评分人数：3
- 评分：4.67

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-27T04:23:07.219Z
  - 原始模型：SD 1.5
  - 下载数：1231
  - 评分人数：3
  - 评分：4.67
- 下载地址
  - [UzumakiHimawari_v1.safetensors](https://civitai.com/api/download/models/56381)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/365b6e68-5724-47d3-4444-be29fb374500/width=450/610928.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f0149473-7bf2-457b-560c-d0714d4a1e00/width=450/610942.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a6cf8737-6e77-476f-792e-262a20d62c00/width=450/610946.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/944c2edd-f93d-455d-8df3-a36b0611a100/width=450/610959.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Trained on 41 images. You'll get decent results with any aspect ratio, though I mostly only used 512x512, 512x768, and 768x512.</p><p></p><p><strong>Strengths</strong></p><p>Produces consistently faithful recreations of the character when using the recommended settings below. This lora is also fairly flexible, allowing you to choose which aspects of the character you want to include or exclude in your image, as well as comfortably handling a wide variety of poses and situations.</p><p></p><p><strong>Shortcomings</strong></p><p>Struggles with hands and eyes in some situations, and doesn't seem to play nice with some of the more common checkpoints. Currently it also has trouble with Byakugan eyes, the shinobi outfit, and the white frills on the skirt, but I plan to make improvements to these areas in future versions.</p><p></p><p><strong>For best results I recommend:</strong></p><ul><li><p>Use uzumaki_himawari in the beginning of the positive prompt.</p></li><li><p>To prompt accurate character details use: (lines on face), short black hair, blunt bangs, blue eyes, ((yellow hoodie, pink skirt)), black thigh highs, red boots,</p></li><li><p>Using <a target="_blank" rel="ugc" href="https://civitai.com/models/15633/ametrine-blend">schneed's Ametrine Blend Checkpoint</a></p></li><li><p>Using this LoRA with <a target="_blank" rel="ugc" href="https://civitai.com/models/23723/animix-anime-screenshot-like-style-mix-lora">CyberAlchemist's Animix - Anime Screenshot-like Style Mix LoRA</a></p></li><li><p><strong>Use a lora weight around 0.5-0.7</strong>. Going over that seems to produce bad results.</p></li><li><p>Use Highres. fix with these settings</p><ul><li><p>R-ESRGAN 4X+ Anime6B</p></li><li><p>Hires steps 0</p></li><li><p>Denoising strength 0.7</p></li><li><p>Upscale 1.5</p></li></ul></li><li><p>Following <a target="_blank" rel="ugc" href="https://civitai.com/models/18840/no-more-color-contamination-read-description">DitamAI's No more color contamination guide</a> to make sure the colors of the clothing stay consistent. I only isolated yellow, pink, and black (for the hoodie, pleated skirt, and thigh highs).</p></li><li><p>Use Clip skip 2</p></li></ul><p></p><p>I plan to continue improving this LoRA with future versions.</p><p>If you have suggestions let me know.</p>