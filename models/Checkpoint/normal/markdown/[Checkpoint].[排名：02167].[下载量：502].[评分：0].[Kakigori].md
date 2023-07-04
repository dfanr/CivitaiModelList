## Kakigori
### 一、模型概述

- 标签：`anime`, `sexy`, `female`, `style`, `cute`, `girls`, `flatcolor`
- 下载数：502
- 收藏人数：243
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-30T23:54:48.045Z
  - 原始模型：SD 1.5
  - 下载数：502
  - 评分人数：0
  - 评分：0
- 下载地址
  - [kakigori_v10.safetensors](https://civitai.com/api/download/models/107578)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/46b5a676-88fe-4d5e-a88b-66b612912d67/width=450/1351500.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0d564112-ebe0-41ab-b9da-e1c5a04f1cf7/width=450/1351502.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dfd1c4c4-211a-4a42-87b1-1ce0f6315a44/width=450/1351663.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7d49cfb1-b9ee-48fb-9b98-07e6ecf4b334/width=450/1351681.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3 id="heading-4026">About the model:</h3><p>My goal with this mix was to create a mostly 2d anime style model that responds well to varied prompts, including a relatively wide range of existing characters without the need of additional LoRAs. NSFW was not a focus for this model, but it can still do it. I have done little testing on LoRA compatibility with this model because I primarily use style LoRAs and this model already has the style that I wanted it to have.</p><p></p><p>I'd love to see what you create with this model!<br /><br /><strong>Prompting:</strong></p><p>Kakigori responds best to booru style prompting, although it can handle some natural language prompting.</p><p>Example prompt: </p><pre><code>kirisame marisa, blonde hair, side braid, waist apron, witch hat, hat bow, yellow eyes, superb, looking down, splashing in a stream, nature, outdoors</code></pre><p>I find that a simple negative prompt without any negative embeddings has worked best for me.<br />Example negative prompt:</p><pre><code>(Worst Quality, Low Quality:1.2), border, nsfw, skimpy, grayscale, multiple_girls, (watermark:1.2)</code></pre><p>Recommended settings:</p><pre><code>Clip skip: 2

Base Resolution: ~512x768 or 768x512

Hires. fix: 4x_fatal_Anime_500000K_G / Upscale by: 1.5+ / Denoising strength: 0.48

Adetailer: face_yolov8n

Sampler: DPM++ 2M Karras/DPM++ 2M SDE Karras

CFG: 7.5 / Steps : 20</code></pre><p><strong>Credits:</strong></p><p>I would like to give thanks to the authors of the following models which were included in this merge. If you like my merge then I would encourage you to try these out as well.</p><p><a rel="ugc" href="https://civitai.com/models/40199?modelVersionId=45601">AuroraONE by Luna</a></p><p><a rel="ugc" href="https://civitai.com/models/92834?modelVersionId=98960">Toonyou - JP - Alpha 1 by Bradcatt </a></p><p><a rel="ugc" href="https://civitai.com/models/44150?modelVersionId=71779">ExpMix_Line - V3 by Mods13</a></p><p>(VAE) <a rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt">kl-f8-anime2 by hakurei</a></p><p></p><p><strong>Why baked VAE?:</strong></p><p>Because I see too many people using models without the correct VAE too often, the impact to file size is tiny, and I don't expect this model to be great for training from anyways. You can still load whichever VAE you would like in WebUI and if you're more than welcome to prune the VAE yourself if you'd prefer that. The VAE I used is a customized version of <a rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt">kl-f8-anime2</a> with lower contrast than the official version. If you would like a copy of the VAE baked into this model you can <a rel="ugc" href="https://huggingface.co/nubby/kl-f8-anime2-blessed">get WD1-4-kl-f8-anime2-bless09 here.</a></p><p></p><p><strong>This model may not be used on any paid generation services. You may not sell this model or any merges that contain it. This model is for personal/private use. Commercial use is not authorized. </strong></p><p></p><p><strong>You are more than welcome to include this model in merges as long as those merges adhere to the same license as this model. If you upload your merge all I ask is that you include a link to this model in the about section like I have done here.</strong></p>