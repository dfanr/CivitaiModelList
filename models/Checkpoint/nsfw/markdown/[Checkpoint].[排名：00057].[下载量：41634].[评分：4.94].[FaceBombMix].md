## FaceBombMix
### 一、模型概述

- 标签：`anime`, `style`, `portraits`
- 下载数：41634
- 收藏人数：10478
- 评论人数：51
- 评分人数：126
- 评分：4.94

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1_bakedVAE

- 统计数据
  - 发布时间：2023-03-20T04:50:03.570Z
  - 原始模型：SD 1.5
  - 下载数：24600
  - 评分人数：67
  - 评分：4.93
- 下载地址
  - [facebombmix_v1Bakedvae.safetensors](https://civitai.com/api/download/models/25993)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/306d833f-6fb0-4afe-7114-964a7b2bdb00/width=450/285805.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1f34eef9-f44f-4aff-bee2-64e442cfce00/width=450/285824.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/58eaff7e-7a75-41dc-67b4-56c08b722d00/width=450/285823.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f0028b28-5659-47af-2565-634679d7ad00/width=450/285822.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1

- 统计数据
  - 发布时间：2023-03-20T04:50:03.570Z
  - 原始模型：SD 1.5
  - 下载数：17034
  - 评分人数：59
  - 评分：4.97
- 下载地址
  - [facebombmix_v1.safetensors](https://civitai.com/api/download/models/8411)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/306d833f-6fb0-4afe-7114-964a7b2bdb00/width=450/79815.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1f34eef9-f44f-4aff-bee2-64e442cfce00/width=450/80311.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/58eaff7e-7a75-41dc-67b4-56c08b722d00/width=450/80313.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f0028b28-5659-47af-2565-634679d7ad00/width=450/80312.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>FaceBomb : Covers from anime to 2.5D style. Suited for general use.</p><p></p><p>More info : <a target="_blank" rel="ugc" href="https://huggingface.co/mocker/KaBoom">https://huggingface.co/mocker/KaBoom</a></p><p></p><p>EDIT 1</p><p>If the color is washed out, try applying VAE.</p><p><a target="_blank" rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt">https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt</a></p><p></p><p>EDIT 2</p><ul><li><p>Positive : <code>(masterpiece, sidelighting, finely detailed beautiful eyes: 1.2), masterpiece*portrait, realistic, 3d face, lustrous skin,</code></p></li><li><p>Negative : <code>(worst quality, low quality:1.4), watermark, logo,</code></p></li></ul><p></p><p>If the sample prompt doen't generate the image you desire, try adding <code>upper body</code> to positive prompt. That 2.5D style best applies to portrait of upper body. It's not necessary but may save you from extra *click.</p><p></p><p>Here's my configuration for duplicating first image. Sorry for inconvenience.</p><p>I use xformers so some detail(e.g. necklass) may change every time.</p><p></p><p>Below is just an example and you can/should change configuration to your liking. It's recommended but not limited.</p><p></p><p>Model : FaceBombMix-fp16-no-ema.safetensors</p><p>SD VAE : kl-f8-anime2.ckpt</p><p>Clip skip : 2</p><p>Sampling method : DPM++ SDE Karras</p><p>Sampling steps : 32 (24 ~ 32, as you like)</p><p>Upscaler : R-ESRGAN 4x+ Anime6B</p><p>Hires steps : 14 (in my case, 7 ~ 14 weren't really different for R-ESRGAN 4x+ Anime6B)</p><p>Denoising strength : 0.5 (I change around 0.45 ~ 0.55)</p><p>Upscale by : 2</p><p>CFG Scale : 9 (7 ~ 9, as you like)</p><p>(Settings &gt; Sampler parameters &gt; Eta noise seed delta) is set to `31337` unsure if it matters though.</p><p></p><p>(Sorry, I dont know hot to upload higher resolution image to description.)</p><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/210f4348-b837-49ea-b7ff-405886de7400/width=525" /><p></p><p>EDIT 3(Not needed if you use bakedVAE version)</p><p>How to apply VAE</p><ol><li><p>Download VAE from EDIT 1 and copy to 'stable-diffusion-webui/models/VAE'.</p></li><li><p>Start the webui and go to 'Settings &gt; User interface &gt; Quicksettings list' and add 'sd_vae' without quotation mark.</p></li><li><p>Click 'Apply settings' and 'Reload UI'. They are orange buttons on top.</p></li><li><p>You should see SD_VAE dropdown menu on top of your main screen. Select 'kl-f8-anime2'.</p></li></ol><img src="https://imagecache.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1e56f1a4-8fce-41a0-093b-5d5f1398ca00/width=525/1e56f1a4-8fce-41a0-093b-5d5f1398ca00" /><p></p>