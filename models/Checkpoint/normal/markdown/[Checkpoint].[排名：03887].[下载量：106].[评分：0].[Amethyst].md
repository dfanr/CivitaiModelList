## Amethyst
### 一、模型概述

- 标签：`anime`, `manga`, `cg`, `scenery`, `comics`, `style`, `illustrations`, `semirealistic`, `backgrounds`
- 下载数：106
- 收藏人数：56
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0 (novae)

- 统计数据
  - 发布时间：2023-06-25T21:56:53.786Z
  - 原始模型：SD 1.5
  - 下载数：87
  - 评分人数：0
  - 评分：0
- 下载地址
  - [amethyst_v10Novae.safetensors](https://civitai.com/api/download/models/104089)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8c62ceb2-1a66-48ec-9e1b-69bc9a48dee7/width=450/1299143.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/65311dd7-e19a-44f9-ac6b-386f0b2dc308/width=450/1289373.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4d0a0d07-24f9-421c-95e6-471a90bf65de/width=450/1289371.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9d883bff-210b-46d7-b8e3-24595724dee9/width=450/1289372.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0 (inpainting)

- 统计数据
  - 发布时间：2023-06-25T21:56:53.786Z
  - 原始模型：SD 1.5
  - 下载数：19
  - 评分人数：0
  - 评分：0
- 下载地址
  - [amethyst_v10-inpainting.safetensors](https://civitai.com/api/download/models/104096)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6c6856fb-ec30-451e-8a2d-b623e0697dda/width=450/1289479.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/850fec9f-7ff6-43d8-bf59-f723a4c66f28/width=450/1289475.jpeg" /> |
| ---- | ---- |


### 三、详情
<h2 id="heading-335">What is Amethyst?</h2><p><strong>Amethyst</strong> is an anime-cg style art for illustrations, manga, comics, and more. I personally use this model for my works, which is well suited on one of my styles. Regarding text prompts, just be versatile and let your imagination flow.<span> </span> And, just like most models it also has few issues with the hands, which can be easily mitigated with this model's inpainting (download separately) or some embeddings. (I still have other models, for some specific arts, yet to be released. <a rel="ugc" href="https://ko-fi.com/kiddyyep">Your support will go a long way, and a cup of coffee will keep me awake for many nights.</a> Thank you in advance!)</p><p></p><p>This version of <strong>Amethyst</strong> does not include a <strong>VAE</strong> because the goal is for art versatility, wherein, you can use any VAE you like to produce unique aesthetics. Below are the recommended VAEs that you can use with this model to tweak a unique output.</p><p></p><h3 id="heading-336">Popular Variable Auto Encoder (VAE)</h3><p><a rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt">kl-f8-anime2 VAE (for anime)</a></p><p><a rel="ugc" href="https://huggingface.co/ckpt/anything-v3.0/blob/main/Anything-V3.0.vae.pt">anything VAE aka orangemix VAE (for anime)</a></p><p><a rel="ugc" href="https://huggingface.co/NoCrypt/blessed_vae/blob/main/blessed2.vae.pt">blessed VAE (for anime)</a></p><p><a rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.safetensors">vae-ft-mse-840000-ema-pruned (for realism)</a></p><p></p><p>Sample images above were created with simple text prompts around default settings. More detailed prompts will produce much better results. As for text prompts, just let your imagination flow. One thing to take note, adding keywords like realistic, realism, photorealism, photorealistic, hyperrealism, hyper realistic etc. will make the image more real, and not including any word with real on them will make it look anime-ish.</p><p></p><h3 id="heading-337">Settings:</h3><p>Sampling Method: Euler (realistic) or Euler A (anime)</p><p>Sampling Steps: 20 to 30</p><p>Resolution: 512x512, 512x768, 768x512</p><p>CFG Scale: 4 to 7</p><p></p><h3 id="heading-338">Popular Embeddings Used</h3><p><a rel="ugc" href="https://civitai.com/models/7808/easynegative">Easy Negative</a></p><p><a rel="ugc" href="https://civitai.com/models/4629?modelVersionId=5637">Deep Negative</a></p><p><a rel="ugc" href="https://civitai.com/models/5224?modelVersionId=6056">Bad artist Negative embedding</a></p><p><a rel="ugc" href="https://civitai.com/models/11772?modelVersionId=25820">veryBadImageNegative</a></p><p><a rel="ugc" href="https://civitai.com/models/55700?modelVersionId=60095">bad_prompt Negative Embedding</a></p><p><a rel="ugc" href="https://civitai.com/models/56519?modelVersionId=60938">negative_hand Negative Embedding</a></p><p><a rel="ugc" href="https://civitai.com/models/47085?modelVersionId=55199">EnvyBetterHands LoCon</a></p><p><a rel="ugc" href="https://civitai.com/models/58390?modelVersionId=62833">Detail Tweaker LoRA</a></p><p><a rel="ugc" href="https://civitai.com/models/19992?modelVersionId=23741">SXZ Vivid Darkness</a></p><p><a rel="ugc" href="https://civitai.com/models/8765?modelVersionId=10350">Theovercomer8's Contrast Fix</a></p><p></p><h3 id="heading-339">Limitations:</h3><p>Do use this model within the boundaries of legalities; do not use it to harm people and entities, or any illegal matters. Using this model means that you alone is responsible for any forms of consequences good or bad, and the author has no liabilities. We all know that AI models can produce both safe and unsafe images for work, so be very responsible.<span> </span> For all other matters do read the <a rel="ugc" href="https://huggingface.co/spaces/CompVis/stable-diffusion-license">CreativeML-OpenRail-M</a> license Other than that, enjoy using this model and I hope this will help you in your endeavours as an artist.</p><p></p><h3 id="heading-340">Support:</h3><p>First of all, thank you for patronizing this model; it means my efforts didn't go to waste. My goal is to produce more free tools not just for myself and my work, but for others too. <a rel="ugc" href="https://ko-fi.com/kiddyyep">Your generosity will go more than a mile. Also, as an artist, writer, programmer, and overall freelancer, I accept commission job.</a> Thank you so much for your support!</p>