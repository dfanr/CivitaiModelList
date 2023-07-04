## Gakki | Aragaki Yui | 新垣結衣
### 一、模型概述

- 标签：`stable diffusion`, `gakki`, `celebrity`, `realistic`, `real person`
- 下载数：16317
- 收藏人数：2232
- 评论人数：14
- 评分人数：20
- 评分：4.9

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2

- 统计数据
  - 发布时间：2023-02-19T18:53:37.878Z
  - 原始模型：Other
  - 下载数：15501
  - 评分人数：18
  - 评分：4.89
- 下载地址
  - [gakki-auto-height.safetensors](https://civitai.com/api/download/models/11250)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7f6ec60d-742a-45c4-9f48-9df175fde300/width=450/113491.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0e60af7d-7ec4-41ef-5178-39d9365e1500/width=450/123007.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/465ac4ae-165c-421c-ef88-031b63557400/width=450/108345.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8a7f49a8-1328-4b58-6049-b855e0a57300/width=450/113503.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-02-19T18:53:37.878Z
  - 原始模型：SD 1.5
  - 下载数：816
  - 评分人数：2
  - 评分：5
- 下载地址
  - [gakki-mix-768-basil.ckpt](https://civitai.com/api/download/models/9926)
  - [vae-ft-mse-840000-ema-pruned.ckpt](https://civitai.com/api/download/models/9926?type=VAE&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3f0d17aa-a725-40ee-643b-4664da121700/width=450/96623.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/990a7e49-1ab6-4b67-156f-c6136fb79700/width=450/96625.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a064957d-3293-4ed9-1ed9-f65782a94e00/width=450/96624.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d3d84e0d-8b9d-4fe6-2aae-ba0cf6e9e300/width=450/96742.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Please use this with ❤️ love</p><ul><li><p>V1: dataset includes 21 high res images to train with dreambooth</p><ul><li><p>best layout: portrait, close up shot,</p></li><li><p>can't lay down, full body shot ( of cause you can image to image to change the face)</p></li><li><p>best resolution: <code>512x768 or 512x960</code></p></li><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/Sa1i/gakki-mix-768">https://huggingface.co/Sa1i/gakki-mix-768</a></p></li></ul></li><li><p>V2: dataset includes 38 fixed and high res images to train with LoRA and dreambooth</p><ul><li><p>best layout: portrait and close up shot</p></li><li><p>good layout: lay down</p></li><li><p>0.6~0.9 is best range when using basil_mix related models</p></li><li><p>small size model : only <code>151M</code></p></li><li><p>base models could use with</p><ul><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/nuigurumi/basil_mix">https://huggingface.co/nuigurumi/basil_mix</a></p></li><li><p>or basil mix related models, of course you can use it with chilloutmix model</p></li></ul></li></ul></li></ul><h2>Lora Model Usage</h2><ol><li><p>place <code>gakki-auto-height.safetensors</code> file into stable-diffusion-webui/models/Lora</p></li><li><p>place <code>vae</code> file into stable-diffusion-webui/models/VAE/</p></li><li><p>prompt with <code>gakki</code> key word</p></li></ol><p></p><h2>CKPT Usage</h2><ol><li><p>place ckpt file into stable-diffusion-webui/models/Stable-diffusion/</p></li><li><p>place vae file into stable-diffusion-webui/models/VAE/</p></li><li><p>prompt with <code>gakki</code> key word</p></li></ol><p></p><h2>VAE</h2><p>Highly recommended for use with VAE</p><p>the sample images using</p><p><a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt">https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt</a></p><p></p><h2>Legal &amp; Risk</h2><p>It is prohibited to use this model for commercial purposes and any scenarios of illegal acts and purposes.</p><p></p><h2>Tips</h2><p></p><p>prompts:</p><pre><code>gakki,</code></pre><p></p><p>negative prompts:</p><pre><code>(((simple background))),monochrome ,lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, lowres, bad anatomy, bad hands, text, error, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, ugly,pregnant,vore,duplicate,morbid,mut ilated,tran nsexual, hermaphrodite,long neck,mutated hands,poorly drawn hands,poorly drawn face,mutation,deformed,blurry,bad anatomy,bad proportions,malformed limbs,extra limbs,cloned face,disfigured,gross proportions, (((missing arms))),(((missing legs))), (((extra arms))),(((extra legs))),pubic hair, plump,bad legs,error legs,username,blurry,bad feet</code></pre><p></p><h2>Next:</h2><h2>Needs more high resolution photo of Gakki</h2><p>Please leave the photos url in the comments. Thanks!</p>