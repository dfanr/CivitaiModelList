## RatnikaMetaMixV2
### 一、模型概述

- 标签：`anime`, `base model`
- 下载数：1611
- 收藏人数：393
- 评论人数：17
- 评分人数：5
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] V2

- 统计数据
  - 发布时间：2023-03-18T00:33:16.406Z
  - 原始模型：SD 1.5
  - 下载数：1143
  - 评分人数：4
  - 评分：5
- 下载地址
  - [ratnikametamixv2_v2.safetensors](https://civitai.com/api/download/models/6718)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2c76efd3-b438-4fe1-a03c-c6b20140eb00/width=450/147747.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d0c4bfab-563a-4568-0f9e-995a5a7fcb00/width=450/147746.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/529c344c-23b5-4cdb-ba93-874beb86c100/width=450/147745.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/27c20de1-d102-45cf-f09c-a71117f65100/width=450/147744.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] 1.0

- 统计数据
  - 发布时间：2023-03-18T00:33:16.406Z
  - 原始模型：SD 1.5
  - 下载数：468
  - 评分人数：1
  - 评分：5
- 下载地址
  - [ratnikametamixv2_10.safetensors](https://civitai.com/api/download/models/6134)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/006b4ea0-25a3-46d4-b45f-9f3fe9299000/width=450/53374.jpeg" /> |
| ---- |


### 三、详情
<p>General use model for realistic anime style.<br /><br />Variation of RatnikaMix mixed from Anything V4 instead of V3 and F222 instead of F111, and Bstaberpro53robo instead of bstaber.</p><p></p><p>Realistic anime-style, good for creative clothing and NSFW content.<br /><br />Recommended Prompt:</p><p>masterpiece, highres, intricate, high quality, Detailed face and eyes, best quality</p><p>Negative prompt:<br />extra digits, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, deformed, bad anatomy, mutation, ugly, broken leg, fat, extra legs, extra ears,</p><p></p><p>Link to VAE used for previews: <a target="_blank" rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt">https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt</a></p><p></p><p>It is recommended to always gen at resolutions below 512px (preview images were generated at 256x512). Use the hires fix to upscale it to something greater (I used denoise strength 0.5). Preview images has been upscaled by 3.5x (4x for the full nude). Turn off "Restore Faces". Experiment with clipskip 1-2.</p><p></p><p>My startup arguments for genning at high resolution with higher speeds:<br />set COMMANDLINE_ARGS= --autolaunch --xformers --opt-split-attention --medvram</p><p></p><p>I recommend getting an upscaler like 4x_BS_DevianceMIP_82000_G, 4x_foolhardy_Remacri or 4x-UltraSharp. Put it into the \models\ESRGAN, restart and select it in your hires fix upscaler. download: <a target="_blank" rel="ugc" href="https://upscale.wiki/wiki/Model_Database">https://upscale.wiki/wiki/Model_Database</a></p>