## Lavender
### 一、模型概述

- 标签：`dark`, `style`, `semirealistic`, `contrast`, `offset noise`
- 下载数：124
- 收藏人数：23
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0 (novae)

- 统计数据
  - 发布时间：2023-06-21T02:57:17.962Z
  - 原始模型：SD 1.5
  - 下载数：95
  - 评分人数：0
  - 评分：0
- 下载地址
  - [lavender_v10Novae.safetensors](https://civitai.com/api/download/models/100642)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e8dc3c1c-df82-4880-a598-344b5ab06ef0/width=450/1299679.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/67f859c6-744d-44d7-95d3-8807fd498740/width=450/1226994.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ff01c655-4e31-42cb-bf54-8e8b9286d4c3/width=450/1227001.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/12182a9e-55d7-4a83-b8f1-482b9749f3f9/width=450/1226990.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0 (inpainting)

- 统计数据
  - 发布时间：2023-06-21T02:57:17.962Z
  - 原始模型：SD 1.5
  - 下载数：29
  - 评分人数：0
  - 评分：0
- 下载地址
  - [lavender_v10-inpainting.safetensors](https://civitai.com/api/download/models/100654)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c1a3210f-479a-490d-80ad-088c0c7412a7/width=450/1227167.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5bc664fa-d698-4944-9603-3840ad957261/width=450/1227165.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5c8413df-0240-4092-bbee-0966f3bb116b/width=450/1227169.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b838fced-5bdd-46ee-a95c-c45a580d1f0d/width=450/1227168.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2 id="heading-345">What is Lavender?</h2><p><strong>Lavender</strong> is a semi-realistic model with dark offset compared to <a rel="ugc" href="https://civitai.com/models/89682/mauve">Mauve</a>, meaning it is best for images with lights and effects, but also good for general use. It has its own unique aesthetics, and I usually use this if I want a dark-themed or dimmer image. Regarding text prompts, just be versatile and let your imagination flow.<span> </span> And, just like most models it also has few issues with the hands, which can be easily mitigated with this model's inpainting (download separately) or some embeddings. (I still have other models, for some specific arts, yet to be released. <a rel="ugc" href="https://ko-fi.com/kiddyyep">Your support will go a long way, and a cup of coffee will keep me awake for many nights.</a> Thank you in advance!)</p><p></p><p>This version of Lavender does not include a <strong>VAE</strong> because the goal is for art versatility, wherein, you can use any VAE you like to produce unique aesthetics. Below are the recommended VAEs that you can use with this model to tweak a unique output.</p><p></p><h3 id="heading-346">Popular Variable Auto Encoder (VAE)</h3><p><a rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt">kl-f8-anime2 VAE (for anime)</a></p><p><a rel="ugc" href="https://huggingface.co/ckpt/anything-v3.0/blob/main/Anything-V3.0.vae.pt">anything VAE aka orangemix VAE (for anime)</a></p><p><a rel="ugc" href="https://huggingface.co/NoCrypt/blessed_vae/blob/main/blessed2.vae.pt">blessed VAE (for anime)</a></p><p><a rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.safetensors">vae-ft-mse-840000-ema-pruned (for realism)</a></p><p></p><p>Sample images above were created with simple text prompts around default settings. More detailed prompts will produce much better results. As for text prompts, just let your imagination flow. One thing to take note, adding keywords like realistic, realism, photorealism, photorealistic, hyperrealism, hyper realistic etc. will make the image more real, and not including any word with real on them will make it look anime-ish.</p><p></p><h3 id="heading-347">Settings:</h3><p>Sampling Method: Euler (realistic) or Euler A (anime)</p><p>Sampling Steps: 20 to 30</p><p>Resolution: 512x512, 512x768, 768x512</p><p>CFG Scale: 4 to 7</p><p></p><h3 id="heading-348">Popular Embeddings Used:</h3><p><a rel="ugc" href="https://civitai.com/models/7808/easynegative">Easy Negative</a></p><p><a rel="ugc" href="https://civitai.com/models/4629?modelVersionId=5637">Deep Negative</a></p><p><a rel="ugc" href="https://civitai.com/models/5224?modelVersionId=6056">Bad artist Negative embedding</a></p><p><a rel="ugc" href="https://civitai.com/models/11772?modelVersionId=25820">veryBadImageNegative</a></p><p><a rel="ugc" href="https://civitai.com/models/55700?modelVersionId=60095">bad_prompt Negative Embedding</a></p><p><a rel="ugc" href="https://civitai.com/models/56519?modelVersionId=60938">negative_hand Negative Embedding</a></p><p><a rel="ugc" href="https://civitai.com/models/47085?modelVersionId=55199">EnvyBetterHands LoCon</a></p><p><a rel="ugc" href="https://civitai.com/models/58390?modelVersionId=62833">Detail Tweaker LoRA</a></p><p><a rel="ugc" href="https://civitai.com/models/19992?modelVersionId=23741">SXZ Vivid Darkness</a></p><p><a rel="ugc" href="https://civitai.com/models/8765?modelVersionId=10350">Theovercomer8's Contrast Fix</a></p><p></p><h3 id="heading-349">Limitations:</h3><p>Do use this model within the boundaries of legalities; do not use it to harm people and entities, or any illegal matters. Using this model means that you alone is responsible for any forms of consequences good or bad, and the author has no liabilities. We all know that AI models can produce both safe and unsafe images for work, so be very responsible.<span> </span> For all other matters do read the <a rel="ugc" href="https://huggingface.co/spaces/CompVis/stable-diffusion-license">CreativeML-OpenRail-M</a> license Other than that, enjoy using this model and I hope this will help you in your endeavours as an artist.</p><p></p><h3 id="heading-350">Support:</h3><p>First of all, thank you for patronizing this model; it means my efforts didn't go to waste. My goal is to produce more free tools not just for myself and my work, but for others too. <a rel="ugc" href="https://ko-fi.com/kiddyyep">Your generosity will go more than a mile. Also, as an artist, writer, programmer, and overall freelancer, I accept commission job.</a> Thank you so much for your support!</p>