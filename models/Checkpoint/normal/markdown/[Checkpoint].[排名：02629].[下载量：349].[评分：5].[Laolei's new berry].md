## Laolei's new berry
### 一、模型概述

- 标签：`anime`, `style`, `artist`, `portraits`
- 下载数：349
- 收藏人数：128
- 评论人数：2
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Laolei's new berry

- 统计数据
  - 发布时间：2023-01-21T19:02:15.755Z
  - 原始模型：SD 1.5
  - 下载数：349
  - 评分人数：1
  - 评分：5
- 下载地址
  - [laoleisNewBerry_laoleisNewBerry.ckpt](https://civitai.com/api/download/models/4164)
  - [laolei_new_berry.vae.pt](https://civitai.com/api/download/models/4164?type=VAE&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0230d43a-4dc8-4fac-bd87-7f2e7240d300/width=450/26927.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/caeef30e-f3f1-4a86-d234-2cc155e8e400/width=450/26924.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/14ed09b4-2eaf-4355-229e-338c451efa00/width=450/26917.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/75bf7a02-6dbe-4def-0051-8c771ac7d400/width=450/26921.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>It is based on a model trained with works of REI (laolei_style_v3.ckpt), who is featured by her oil painting skills, colorful compositions, dynamic postures and somewhat photorealistic style in her watercolor anime style digital art. It is also mixed with realEldenApocalypseA and R34 e4. </p><p></p><p>Model merging process:</p><p>1, add difference</p><p>(A) laolei_style_v3.ckpt</p><p>(B) realEldenApocalypseA_realEldenApocalypseA.safetensors</p><p>(C) sd-v1-4.ckpt</p><p>value: 1</p><p>-&gt; laolei_Elden.ckpt</p><p>2, weighted sum</p><p>(A) laolei_Elden.ckpt</p><p>(B) e34_e4.ckpt</p><p>-&gt;<strong> laolei_new_berry.ckpt &lt;-- this model</strong></p><p></p><p><strong>Note:</strong> please use a vae when using this model, or images of inverted colors or with weird colors will be generated. The vae of stable diffusion v1.5 (vae-ft-mse-840000-ema-pruned.ckpt) is okay. You can also use the vae file of the original laolei_style_v3.ckpt, which is also attached here.</p>