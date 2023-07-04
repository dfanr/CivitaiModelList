## Hentai Manga Style Concept
### 一、模型概述

- 标签：`anime`, `lineart`, `sexy`, `porn`, `manga`, `monochrome`, `manga art style`, `style`, `illustration`, `hentai`, `comic`, `nsfw`, `comics style`
- 下载数：6700
- 收藏人数：1394
- 评论人数：20
- 评分人数：11
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2.0

- 统计数据
  - 发布时间：2023-05-29T00:25:05.371Z
  - 原始模型：SD 1.5
  - 下载数：5387
  - 评分人数：8
  - 评分：5
- 下载地址
  - [MangaHentaiStyleConceptv2.pt](https://civitai.com/api/download/models/84156)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7ae8fe42-c8b5-4206-a578-9753a313b0dc/width=450/949983.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/07866807-db7e-43b2-aefe-e39ac6ef38a2/width=450/950256.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da32b8bb-dd78-4256-9159-1dfb5b5531bc/width=450/949963.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/82b85379-308d-4a11-a03b-5dd5d4f2e201/width=450/949986.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-05-29T00:10:49.598Z
  - 原始模型：SD 1.5
  - 下载数：1313
  - 评分人数：3
  - 评分：5
- 下载地址
  - [MangaHentaiStyleConcept.pt](https://civitai.com/api/download/models/79692)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/40e4c5e8-0700-4638-87fb-6607d97513f5/width=450/894496.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/864fa5f3-e7f3-4545-9a77-e634ecb4a0a1/width=450/894222.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/967b827f-84fe-459a-9cf2-3381f4bc7f53/width=450/894223.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cc57fba9-fe9f-4d98-834d-2c2190fa7288/width=450/894217.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1>Hentai Manga Style</h1><p>This is a embedding i trained on just hentai images. Therefore you will get a lot of open mouths, ahegao, sweating, saliva etc.. from just using the embedding.</p><p></p><p>There is no <strong><em><u>Trigger word</u></em></strong></p><p></p><p>All training images were nsfw so even if you try to go for something SFW you have to properly build your prompt. The lineart gets weaker the longer your prompt is. In other words, the longer the prompt is, the weaker the 2D style gets. You can reinforce the embedding with prompts like:</p><p></p><p><strong>monochrome, lineart, comic, cross-section,</strong></p><p></p><p>If you want to keep the embedding relative simple use the above tags, but if you want to get the manga panels etc.. then use:</p><p></p><p><strong>monochrome, lineart, comic, cross-section, manga \(object\), left-to-right manga,</strong></p><p></p><p>A good <strong><em>negative</em></strong> prompt is:</p><p></p><p><strong>(worst quality, low quality:1.4), zombie, watermark, username, patreon username, patreon logo, (extra fingers, deformed hands, polydactyl:1.5), censored, bar censor, child, loli,</strong></p><p></p><p>This embedding is a hit or miss. As i said earlier, you have to build your prompt properly if you want to get something specific, else it will throw random NSFW stuff at you.</p><p></p><p>The example images were not all first generations. Some are <strong><em>inpainted</em></strong>, some just went through <strong><em>hires fix</em></strong>, and some just <strong><em>img2img</em></strong>.</p><p></p><h1><strong>Here is my recommended setup:</strong></h1><p>First of all USE a VAE!!! I have gotten comments from people telling me that they are getting washed out colors and artifacts when using my models, that is because you are NOT using a VAE.</p><p>Two of my favorite VAEs are:</p><p>ft-mse: <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt">https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt</a></p><p>kl-f8-anime: <a target="_blank" rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt">https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt</a></p><p>Download one or both, put the file in your <strong>stable diffusion folder</strong> -&gt; <strong>models</strong> -&gt; <strong>VAE</strong></p><p>Then go to the webui and <strong>settings</strong> -&gt; <strong>stable diffusion</strong> -&gt; <strong>SD VAE</strong> and choose the VAE from the drop down. Some models have integrated VAE, my <a target="_blank" rel="ugc" href="https://civitai.com/models/53215/darkrevpikas">DarkRevPikas</a> model does not, so you have to use one. The "Automatic" option does not work.</p><p></p><p>You should also consider using <a target="_blank" rel="ugc" href="https://github.com/mcmonkeyprojects/sd-dynamic-thresholding"><em>Stable Diffusion Dynamic Thresholding (CFG Scale Fix)</em></a><em> </em>extension<em>, </em>if you wanna use higher CFG scale without getting artifacts.</p><p></p><h3><strong>Txt2img:</strong></h3><p><strong>512x768</strong> or <strong>768x512 </strong>or<strong> 512x512</strong></p><p>steps: <strong>30-60</strong></p><p>CFG: <strong>10-12</strong> With <a target="_blank" rel="ugc" href="https://github.com/mcmonkeyprojects/sd-dynamic-thresholding">CFG scale fix</a> set mimic CFG scale <strong>6</strong></p><p>Without the extension use CFG <strong>6-8</strong></p><p></p><h3><strong>Img2img</strong></h3><p>Basically whatever your pc can generate, i use:</p><p><strong>896x1344</strong> or <strong>1344x896</strong> or <strong>1024x1024</strong></p><p>steps: <strong>30-60</strong></p><p>CFG: <strong>10-12</strong> With <a target="_blank" rel="ugc" href="https://github.com/mcmonkeyprojects/sd-dynamic-thresholding">CFG scale fix</a> set mimic CFG scale <strong>6</strong></p><p>Without the extension use CFG <strong>6-8</strong></p><p>Denoise strength:<strong> 0.5</strong></p><p></p><h3><strong><em>Hires fix:</em></strong></h3><p>Hires steps: <strong>10-20</strong></p><p>Denoising Strength: <strong>0.3-0.45</strong></p><p>Upscale by: <strong>1.5-2</strong></p>