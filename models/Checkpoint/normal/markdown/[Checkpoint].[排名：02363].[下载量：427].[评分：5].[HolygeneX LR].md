## HolygeneX LR
### 一、模型概述

- 标签：`base model`, `holygenex`
- 下载数：427
- 收藏人数：127
- 评论人数：0
- 评分人数：1
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-04-29T00:34:48.043Z
  - 原始模型：SD 1.5
  - 下载数：387
  - 评分人数：1
  - 评分：5
- 下载地址
  - [holygenexLR_v10.safetensors](https://civitai.com/api/download/models/57586)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dda9ac7a-b288-4465-878d-5091d1f85fbf/width=450/696538.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2834c8f3-ac64-4e8f-a1a8-ccc0ad8d7f9d/width=450/696417.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6368d667-3ec5-4c5d-9795-3dd17919eebf/width=450/696420.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/48d1695f-3e47-4359-85e4-eae89278c8ac/width=450/696421.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] HolygeneX LR inpainting

- 统计数据
  - 发布时间：2023-04-29T00:34:48.043Z
  - 原始模型：SD 1.5
  - 下载数：40
  - 评分人数：0
  - 评分：0
- 下载地址
  - [holygenexLR_holygenexLR.safetensors](https://civitai.com/api/download/models/57747)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e2b693b2-fa45-4fe5-baf8-48da574f2200/width=450/627518.jpeg" /> |
| ---- |


### 三、详情
<p>I trained 10 LoRa's on 1300 realistic photos of very high quality at 1024x1024 resolution and mixed them with the <a target="_blank" rel="ugc" href="https://civitai.com/models/24345/holygenex">Holygenex</a> model, then combined the resulting model with the SD 1.5 base model.</p><p>The resulting Holygenex LR model can generate 768x768, 1024x768, 768x1024, even 1024x1024.</p><p>The task is to create a model which can generate high resolution images with excellent quality on the SD 1.5 engine.</p><p>From now on, you can say that SD 1.5 can generate images with 768x768 and 1024x1024 resolution.</p><p><strong>To get a good quality image you need to use Hires. fix. There is no other way!</strong></p><p>The images in the examples are generated at 90-150 steps and Hires. Fix with Denoising strength: 0.3 using Upscale by 2 with best upscaler 4x-UniScale-Balanced [72000g]. See the full picture descriptions in the examples. Click "Copy generation data", copy the text to notepad and see the full description.</p><p></p><ul><li><p>For panoramic images it is better to use a resolution of 1024x768</p></li><li><p>For portraits you can try 768x960 or 768x1024</p></li><li><p>For precise geometric objects 768x768</p></li></ul><p></p><p>If you have graphics cards with 8GB memory or more, use Hires. fix. The quality and detail of the image improves several times over.</p><p>If you have weak graphics cards, you can generate portraits without Hires. fix, use a resolution of 768x960 or 1024x1024 and check the Restore faces.</p><p></p><p>For best results use the VAE, vae-ft-mse-840000-ema-pruned <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/resolve/main/vae-ft-mse-840000-ema-pruned.ckpt">https://huggingface.co/stabilityai/sd-vae-ft-mse-original/resolve/main/vae-ft-mse-840000-ema-pruned.ckpt</a></p><p></p><p><u>This embeddings must be used in your NEGATIVE prompt:</u></p><p>bad-hands-5 <a target="_blank" rel="ugc" href="https://huggingface.co/nolanaatama/embeddings/blob/main/bad-hands-5.pt">https://huggingface.co/nolanaatama/embeddings/blob/main/bad-hands-5.pt</a></p><p><strong>EasyNegative </strong><a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative"><strong>https://civitai.com/models/7808/easynegative</strong></a></p><p></p><p><u>Negative Prompt for example:</u></p><p>EasyNegative, bad-hands-5, (((nude, naked,child, child face))), (out of frame:1.1), worst quality, low quality, jpeg artifacts, cgi, 3d, render, sketch, cartoon, drawing, ugly eyes, (out of frame:1.1), worst quality, low quality</p><p></p>