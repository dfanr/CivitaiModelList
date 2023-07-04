## Lilac
### 一、模型概述

- 标签：`comic book`, `anime`, `comics`, `style`, `graphic novel`, `cartoonish`, `childrens books`, `children`, `kid`, `children's book`, `cartoons`, `childbook`
- 下载数：191
- 收藏人数：64
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0 (novae)

- 统计数据
  - 发布时间：2023-06-19T06:16:42.536Z
  - 原始模型：SD 1.5
  - 下载数：155
  - 评分人数：0
  - 评分：0
- 下载地址
  - [lilac_v10Novae.safetensors](https://civitai.com/api/download/models/99243)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/507cad12-c14c-4ddb-8671-3b3a77276b1e/width=450/1299996.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ccd9525-fb5d-4387-b71f-f1c9652863a1/width=450/1202752.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bd06d321-3e47-4325-921d-74a40fabf154/width=450/1202784.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ae985dc2-471e-4855-9242-e173aa578096/width=450/1202783.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0 (inpainting)

- 统计数据
  - 发布时间：2023-06-19T06:16:42.536Z
  - 原始模型：SD 1.5
  - 下载数：36
  - 评分人数：0
  - 评分：0
- 下载地址
  - [lilac_v10-inpainting.safetensors](https://civitai.com/api/download/models/99257)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/25570aee-1fde-488a-82f4-4938e1ad1198/width=450/1203004.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/16379a2b-de16-4955-951d-be810010a3c2/width=450/1202991.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0f1eea4a-d893-4692-ae01-356b408fd52b/width=450/1203005.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/54ebac1f-2245-4ca0-850b-bd0feedf8974/width=450/1203002.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2 id="heading-402">What is Lilac?</h2><p><strong>Lilac</strong> is a cartoonish anime style model primarily designed in creating images for children's books, graphic novels, comics, kids' illustrations and promotional arts. It has its own unique aesthetics compared to my other model <a rel="ugc" href="https://civitai.com/models/90986/plum">Plum</a>.<span> </span> I personally use this model for my works, which is well suited on one of my styles. Regarding text prompts, just be versatile and let your imagination flow.<span> </span> And, just like most models it also has few issues with the hands, which can be easily mitigated with this model's inpainting (download separately) or some embeddings. (I still have other models, for some specific arts, yet to be released. <a rel="ugc" href="https://ko-fi.com/kiddyyep">Your support will go a long way, and a cup of coffee will keep me awake for many nights.</a> Thank you in advance!)</p><p></p><p>This version of Lilac does not include a <strong>VAE</strong> because the goal is for art versatility, wherein, you can use any VAE you like to produce unique aesthetics. Below are the recommended VAEs that you can use with this model to tweak a unique output.</p><p></p><h3 id="heading-403">Popular Variable Auto Encoder (VAE)</h3><p><a rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt">kl-f8-anime2 VAE (for anime)</a></p><p><a rel="ugc" href="https://huggingface.co/ckpt/anything-v3.0/blob/main/Anything-V3.0.vae.pt">anything VAE aka orangemix VAE (for anime)</a></p><p><a rel="ugc" href="https://huggingface.co/NoCrypt/blessed_vae/blob/main/blessed2.vae.pt">blessed VAE (for anime)</a></p><p><a rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.safetensors">vae-ft-mse-840000-ema-pruned (for realism)</a></p><p></p><p>Sample images above were created with simple text prompts around default settings. More detailed prompts will produce much better results. As for text prompts, just let your imagination flow. One thing to take note, adding keywords like realistic, realism, photorealism, photorealistic, hyperrealism, hyper realistic etc. will make the image more real, and not including any word with real on them will make it look cartoonish or anime-ish.</p><p></p><h3 id="heading-404">Settings:</h3><p>Sampling Method: Euler (realistic) or Euler A (anime)</p><p>Sampling Steps: 20 to 30</p><p>Resolution: 512x512, 512x768, 768x512</p><p>CFG Scale: 4 to 7</p><p></p><h3 id="heading-405">Popular Embeddings Used</h3><p><a rel="ugc" href="https://civitai.com/models/7808/easynegative">Easy Negative</a></p><p><a rel="ugc" href="https://civitai.com/models/4629?modelVersionId=5637">Deep Negative</a></p><p><a rel="ugc" href="https://civitai.com/models/5224?modelVersionId=6056">Bad artist Negative embedding</a></p><p><a rel="ugc" href="https://civitai.com/models/11772?modelVersionId=25820">veryBadImageNegative</a></p><p><a rel="ugc" href="https://civitai.com/models/55700?modelVersionId=60095">bad_prompt Negative Embedding</a></p><p><a rel="ugc" href="https://civitai.com/models/56519?modelVersionId=60938">negative_hand Negative Embedding</a></p><p><a rel="ugc" href="https://civitai.com/models/47085?modelVersionId=55199">EnvyBetterHands LoCon</a></p><p><a rel="ugc" href="https://civitai.com/models/58390?modelVersionId=62833">Detail Tweaker LoRA</a></p><p><a rel="ugc" href="https://civitai.com/models/19992?modelVersionId=23741">SXZ Vivid Darkness</a></p><p><a rel="ugc" href="https://civitai.com/models/8765?modelVersionId=10350">Theovercomer8's Contrast Fix</a></p><p></p><h3 id="heading-406">Limitations:</h3><p>Do use this model within the boundaries of legalities; do not use it to harm people and entities, or any illegal matters. Using this model means that you alone are responsible for any forms of consequences good or bad, and the author has no liabilities. We all know that AI models can produce both safe and unsafe images for work, so be very responsible.<span> </span> For all other matters do read the <a rel="ugc" href="https://huggingface.co/spaces/CompVis/stable-diffusion-license">CreativeML-OpenRail-M</a> license Other than that, enjoy using this model and I hope this will help you in your endeavours as an artist.</p><p></p><h3 id="heading-407">Support:</h3><p>First of all, thank you for patronizing this model; it means my efforts didn't go to waste. My goal is to produce more free tools not just for myself and my work, but for others too. <a rel="ugc" href="https://ko-fi.com/kiddyyep">Your generosity will go more than a mile. Also, as an artist, writer, programmer, and overall freelancer, I accept commission job.</a> Thank you so much for your support!</p>