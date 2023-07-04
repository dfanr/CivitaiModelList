## Taunimus Mix 
### 一、模型概述

- 标签：`base model`
- 下载数：594
- 收藏人数：134
- 评论人数：1
- 评分人数：2
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2.2-DDIM-pruned

- 统计数据
  - 发布时间：2023-06-17T16:53:19.574Z
  - 原始模型：SD 1.5
  - 下载数：481
  - 评分人数：2
  - 评分：5
- 下载地址
  - [taunimusMix_v22DDIMPruned.safetensors](https://civitai.com/api/download/models/97942)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/245ebf54-ec88-4075-ae91-183ca1de8097/width=450/1179350.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2ca3a422-ab64-423f-8b5b-7cf06b7ed77e/width=450/1179349.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da770dd9-a6b0-4d07-aacd-17f3561436df/width=450/1179342.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e046036f-3aae-410f-a3df-ae80c3df2309/width=450/1179341.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0-Karras-pruned

- 统计数据
  - 发布时间：2023-06-18T11:17:29.686Z
  - 原始模型：SD 1.5
  - 下载数：113
  - 评分人数：0
  - 评分：0
- 下载地址
  - [taunimusMix_v10KarrasPruned.safetensors](https://civitai.com/api/download/models/97954)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2809e65a-7093-48e3-bfa5-1d9e148635de/width=450/1188674.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dcac3431-18ff-445f-9a17-c11c12306459/width=450/1192442.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/588bf383-1fd3-4182-afdc-228c5ab49ecd/width=450/1188774.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/64928d55-9b18-433e-9444-b19a99019c7a/width=450/1189772.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-65">Welcome to Taunimus Mix!</h1><p>--</p><p>If you love my work you can buy me a coffee : <a target="_blank" rel="ugc" href="http://ko-fi.com/tauron">ko-fi.com/tauron</a> you dont have to, but if you do, it helps me stay awake until midnight (which is the only time im able to work on these stuff lol) -- or.. a like or a review wont hurt or takes you more than 1 mins, while it takes me hours, days or even week to make this - it helps the thread alive and afloat.</p><p>--</p><p>v1.0 is a legacy model moved from Tau's Hybrid Mix. this model is good for SDE sampler -- this version is better to create NSFW and vanilla anime style</p><p>v2.2 is a new model optimized for DDIM sampler -- this version is better for creating conceptual art style.</p><p>--</p><h3 id="heading-12372"><strong>Disclaimers:</strong></h3><ol><li><p><strong>tested mostly for txt2img, for other functions use at your own discretion.</strong></p></li><li><p><strong>a pruned model is not suitable to be merged.</strong></p></li></ol><p></p><h3 id="heading-12374"><strong>Prerequisite &amp; Resources</strong></h3><p><strong>These are the resources i use for my standard workflow :</strong></p><ol><li><p><strong>VAE-FT-MSE-84000 </strong></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt">vae-ft-mse-840000-ema-pruned.ckpt · stabilityai/sd-vae-ft-mse-original at main (</a><a target="_blank" rel="ugc" href="http://huggingface.co">huggingface.co</a><a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt">)</a></p></li><li><p><strong>ADetailer</strong></p><p><a target="_blank" rel="ugc" href="https://github.com/Bing-su/adetailer">GitHub - Bing-su/adetailer: Auto detecting, masking and inpainting with detection model.</a></p></li><li><p><strong>Negative Embeddings (Use 1 only)</strong></p><p></p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/4629/deep-negative-v1x">Deep Negative V1.x - V1 75T | Stable Diffusion Textual Inversion | Civitai</a></p><p>accurate prompt such as race, skin tone but smoothen the skin texture and has face bias (change result face), also sometimes misinterpret prompt position occassionally.</p></li></ul><p></p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative">EasyNegative - EasyNegative | Stable Diffusion Textual Inversion | Civitai</a></p><p>most accurate amongst other negative ti -- prompt such as race, skin tone, face, and texture is very accurate (90%), but sometimes misinterpret prompt position (ex. cum is supposed to be on body, but is on face instead)</p><p></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/17083?modelVersionId=20171">bad-picture negative embedding for ChilloutMix - 32 Vector Version | Stable Diffusion Textual Inversion | Civitai</a></p><p>most detailed amongst other negative ti -- this embedding (32v or 75v) pushes skin texture and facial detail to the top. however, it changes skin tone, color, and face significantly producing inaccurate result if you are trying to use lyco.</p></li></ul><p></p><p><strong><em>DO NOT COMBINE NEGATIVE - TI WITH SAME FUNCTIONS</em></strong></p><p></p></li><li><p><strong>Facial Enhancer Embeddings (optional)</strong></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/yesyeahvh/ulzzang-6500">yesyeahvh/ulzzang-6500 · Hugging Face</a></p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/4514/pure-eros-face">Pure Eros Face - PureErosFace_v1 | Stable Diffusion Textual Inversion | Civitai</a></p><p></p></li></ol><p>Credits to all creators above that helps the model achieve its sample images quality above.</p><p></p><h3 id="heading-12375"><strong>How To prompt this mix</strong></h3><p>You can follow your own prompting method, this guide only serves as a convention when you are having trouble producing similar results with my lora.</p><ol><li><p>Style —&gt; realistic , realistic details, detailed for realism / anime for anime / masterpiece , best illustration for conceptual art.</p></li><li><p>Subject —&gt; describe your subject can be anything. 1girl, solo, cute, beautiful, slender, etc. if you use my character lora this should be where you put trigger words of the character</p></li><li><p>Attire —&gt; describe the outfit of your subject. If you use my attire lora this is where you should put trigger words</p></li><li><p>Background / Context —&gt; describe the context or the scene</p></li><li><p>Textual Inversion &amp; LoRa brackets</p></li></ol><p></p><h3 id="heading-12376"><strong>How to maximize this mix?</strong></h3><p><strong>Sampler &amp; Steps</strong></p><ul><li><p>SDE Karras Sampler = 50 / 25 Denoise @ 0.32</p></li><li><p>DDIM Sampler = 128 / 8 Denoise @0.32 (Observed Fast like 2M, but with SDE Quality)</p></li><li><p><strong><s><u>Using negative embeddings is a must</u></s></strong><s> to create sample image quality. </s>Negative Ti is no longer needed to achieve sample image quality</p><p></p></li></ul><p><strong>CFG Scale</strong></p><ul><li><p><strong>CFG Scale (creative) 4 ----------- 10 (accurate) -- 12 (Max)</strong></p></li></ul><p></p><p><strong>Resolution &amp; Upscaling</strong></p><ul><li><p>Resolution: 512 x 768,</p></li><li><p>Upscaling = 4x_Ultrasharp <a target="_blank" rel="ugc" href="https://huggingface.co/lokCX/4x-Ultrasharp">lokCX/4x-Ultrasharp · Hugging Face</a></p></li><li><p>To get even better results: Use Lightroom to edit your result.</p><p></p></li></ul><p><strong>Utilizing ADetailer</strong></p><ul><li><p>Face = Noise 0.3</p></li><li><p>Hands = Noise 0.25-0.4</p></li><li><p>Body = Noise 0.3-0.5</p></li></ul><p></p><p><strong><u>The rule of thumb is that there are no constant equation</u></strong><u>,</u> you need to find one your own that suits what you are aiming, and sometimes you change these value on the fly depending on your goal. its better to know what these parameters do to your results rather than copying values from people's post.</p><p></p><p>--</p><p><strong><em>As an afterwords, i hope you enjoy using this model, a like or a review definitely helps, or if you find it distasteful, you don't have to use it. there are many models out there that produces similar or superior results.</em></strong></p>