## Something
### 一、模型概述

- 标签：`anime`, `character`
- 下载数：645
- 收藏人数：103
- 评论人数：2
- 评分人数：9
- 评分：4.89

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v2.2

- 统计数据
  - 发布时间：2023-05-04T05:02:36.760Z
  - 原始模型：SD 1.5
  - 下载数：645
  - 评分人数：9
  - 评分：4.89
- 下载地址
  - [something_v22.safetensors](https://civitai.com/api/download/models/61780)
  - [blessed2.vae.pt](https://civitai.com/api/download/models/61780?type=VAE&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4f467449-f2bd-46ae-8f28-92fab2e47bc5/width=450/679932.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/723ef10b-5eef-4c0a-84fb-b6c53725aa73/width=450/679934.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d78e3e03-7d9d-40ea-9c1c-6468d51376b4/width=450/679951.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/471b725a-5dfa-4c84-ab20-78cc7acf9e56/width=450/679991.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>all rights and congratulations to: <a target="_blank" rel="ugc" href="https://huggingface.co/NoCrypt/SomethingV2_2">NoCrypt https://huggingface.co/NoCrypt/SomethingV2_2</a></p><h2></h2><img src="https://huggingface.co/NoCrypt/SomethingV2_2/resolve/main/images/Artboard%201.png" /><h1><strong>SomethingV2.2</strong></h1><p>Welcome to SomethingV2.2 - an improved anime latent diffusion model from <a target="_blank" rel="ugc" href="https://huggingface.co/NoCrypt/SomethingV2"><strong><u>SomethingV2</u></strong></a></p><p>A lot of things are being discovered lately, such as a way to merge model using mbw automatically, offset noise to get much darker result, and even VAE tuning. This model is intended to use all of those features as the improvements, here's some improvements that have been made:</p><p></p><img src="https://huggingface.co/NoCrypt/SomethingV2_2/resolve/main/images/Artboard%202.png" /><h2><strong>Can't trust the numbers? Here's some proof</strong></h2><h2>Recommended settings</h2><ul><li><p>VAE: None (Baked in model, <a target="_blank" rel="ugc" href="https://huggingface.co/NoCrypt/blessed_vae/blob/main/blessed2.vae.pt"><strong><u>blessed2</u></strong></a>)</p></li><li><p>Clip Skip: 2</p></li><li><p>Sampler: DPM++ 2M Karras</p></li><li><p>CFG Scale: 7 ± 5</p></li><li><p>Recommended Positive Prompt: masterpiece, best quality, negative space, (bioluminescence:1.2), darkness, dark background</p></li><li><p>Recommended Negative Prompt: <a target="_blank" rel="ugc" href="https://huggingface.co/datasets/gsdf/EasyNegative"><strong><u>EasyNegative</u></strong></a></p></li><li><p>For better results, using hires fix is a must.</p></li><li><p>Hires upscaler: Latent (any variant, such as nearest-exact)</p></li></ul><h2>Recipe</h2><p><em>Due to </em><a target="_blank" rel="ugc" href="https://huggingface.co/Xynon/SD-Silicon#terms-of-use"><strong><em><u>SD-Silicon's Terms of use</u></em></strong></a><em>. I must specify how the model was made</em></p><p><strong>Model AModel BInterpolation MethodWeightName</strong><a target="_blank" rel="ugc" href="https://huggingface.co/closertodeath/dpepmkmp/blob/main/dpepmkmp.safetensors"><strong><u>dpepmkmp</u></strong></a><a target="_blank" rel="ugc" href="https://huggingface.co/Xynon/SD-Silicon/blob/main/Silicon29/Silicon29-dark.safetensors"><strong><u>silicon29-dark</u></strong></a>MBWReverse Cosine<a target="_blank" rel="ugc" href="https://huggingface.co/un1xx/model_dump/blob/main/bw-merge-dpepmkmp-Silicon29-dark-0.ckpt"><strong><u>dpepsili</u></strong></a><a target="_blank" rel="ugc" href="https://huggingface.co/NoCrypt/SomethingV2/blob/main/somethingv2_1.safetensors"><strong><u>somethingV2_1</u></strong></a><a target="_blank" rel="ugc" href="https://huggingface.co/un1xx/model_dump/blob/main/bw-merge-dpepmkmp-Silicon29-dark-0.ckpt"><strong><u>dpepsili</u></strong></a>MBWCosineSomethingV2_2 rawSomethingV2_2 raw<a target="_blank" rel="ugc" href="https://huggingface.co/NoCrypt/blessed_vae/blob/main/blessed2.vae.pt"><strong><u>Blessed2 VAE</u></strong></a>Bake VAE-<a target="_blank" rel="ugc" href="https://huggingface.co/NoCrypt/SomethingV2_2/blob/main/SomethingV2_2.safetensors"><strong><u>SomethingV2_2</u></strong></a></p><h2>Why not call it SomethingV4?</h2><p>Since this model was based on SomethingV2 and there's not THAT much of improvements in some condition. Calling it V4 is just not right at the moment 😅</p>