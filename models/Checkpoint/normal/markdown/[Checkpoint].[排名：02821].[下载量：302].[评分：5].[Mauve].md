## Mauve
### 一、模型概述

- 标签：`cgi`, `style`, `realistic`, `semi-realistic`, `characters`, `cg art`, `styles`
- 下载数：302
- 收藏人数：113
- 评论人数：0
- 评分人数：2
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0 (novae)

- 统计数据
  - 发布时间：2023-06-13T22:25:29.639Z
  - 原始模型：SD 1.5
  - 下载数：248
  - 评分人数：2
  - 评分：5
- 下载地址
  - [mauve_v10Novae.safetensors](https://civitai.com/api/download/models/95472)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/60606c09-84a1-4167-a027-62d6141b4b3d/width=450/1299769.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/547b3854-8d96-4f65-9ade-76fadd0b7d00/width=450/1135975.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dd30d919-207b-44ba-ac0c-42bcb859da2a/width=450/1135965.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a7c9a47e-dfd1-4712-85de-ce3df854a6f4/width=450/1135972.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0 (Inpainting)

- 统计数据
  - 发布时间：2023-06-13T22:25:29.639Z
  - 原始模型：SD 1.5
  - 下载数：54
  - 评分人数：0
  - 评分：0
- 下载地址
  - [mauve_v10-inpainting.safetensors](https://civitai.com/api/download/models/95478)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f5ddb5cb-225d-4b22-bfaf-9a7cc5a759bc/width=450/1136088.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/10fe1d03-3dfb-4cc2-91e5-ccb214ddfc44/width=450/1136750.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cf23eeff-687c-4cac-a907-d37c0c9d337c/width=450/1136079.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bb6de24f-8326-44ac-a8a3-2aa718224e63/width=450/1136752.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2 id="heading-2562">What is Mauve?</h2><p>Mauve is intended to be <strong>semi-realistic</strong> or <strong>CG-like</strong> as its base, so that you can use Loras and embeddings to easily make it <strong>photorealistic</strong> or <strong>anime-ish</strong>; it is the best of both worlds. This model is so versatile and can easily generate any awesome arts and images from general or common text prompts. A great artist assistant just like many models in this site. And, just like most models it also has some issues with the hands, which can be easily mitigated with this model's inpainting (download separately) or some embeddings. (I still have other models, for some specific arts, yet to be released. <a rel="ugc" href="https://ko-fi.com/kiddyyep"><strong>Your support will go a long way, and a cup of coffee will keep me awake for many nights.</strong></a> Thank you in advance!)</p><p></p><p>This version of Mauve does not include a <strong>VAE</strong> because the goal is for art versatility, wherein, you can use any VAE you like to produce unique aesthetics. Below are the recommended VAEs that you can use with this model to tweak a unique output.</p><p></p><p><a rel="ugc" href="https://huggingface.co/hakurei/waifu-diffusion-v1-4/blob/main/vae/kl-f8-anime2.ckpt">kl-f8-anime2 VAE (for anime)</a></p><p><a rel="ugc" href="https://huggingface.co/ckpt/anything-v3.0/blob/main/Anything-V3.0.vae.pt">anything VAE aka orangemix VAE (for anime)</a></p><p><a rel="ugc" href="https://huggingface.co/NoCrypt/blessed_vae/blob/main/blessed2.vae.pt">blessed VAE (for anime)</a></p><p><a rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.safetensors">vae-ft-mse-840000-ema-pruned (for realism)</a></p><p></p><p>Sample images above were created with simple text prompts around default settings. More detailed prompts will produce much better results. As for text prompts, just let your imagination flow. One thing to take note, adding keywords like <strong>realistic, realism, photorealism, photorealistic, hyperrealism, hyper-realistic</strong> etc., will make the image more real, and not including any word with <strong>real</strong> on them will make it look anime-ish.</p><p></p><h3 id="heading-2563">Settings:</h3><p>Sampling Method: Euler (realistic) or Euler A (anime)</p><p>Sampling Steps: 20 to 30</p><p>Resolution: 512x512, 512x768, 768x512</p><p>CFG Scale: 4 to 7</p><p></p><h3 id="heading-2564">Popular Embeddings Used:</h3><p><a rel="ugc" href="https://civitai.com/models/7808/easynegative">Easy Negative</a></p><p><a rel="ugc" href="https://civitai.com/models/4629?modelVersionId=5637">Deep Negative</a></p><p><a rel="ugc" href="https://civitai.com/models/5224?modelVersionId=6056">Bad artist Negative embedding</a></p><p><a rel="ugc" href="https://civitai.com/models/11772?modelVersionId=25820">veryBadImageNegative</a></p><p><a rel="ugc" href="https://civitai.com/models/55700?modelVersionId=60095">bad_prompt Negative Embedding</a></p><p><a rel="ugc" href="https://civitai.com/models/56519?modelVersionId=60938">negative_hand Negative Embedding</a></p><p><a rel="ugc" href="https://civitai.com/models/47085?modelVersionId=55199">EnvyBetterHands LoCon</a></p><p><a rel="ugc" href="https://civitai.com/models/58390?modelVersionId=62833">Detail Tweaker LoRA</a></p><p><a rel="ugc" href="https://civitai.com/models/19992?modelVersionId=23741">SXZ Vivid Darkness</a></p><p><a rel="ugc" href="https://civitai.com/models/8765?modelVersionId=10350">Theovercomer8's Contrast Fix</a></p><p></p><h3 id="heading-2565">Limitations:</h3><p>Do use this model within the boundaries of legalities; do not use it to harm people and entities, or any illegal matters. Using this model means that you alone are responsible for any forms of consequences good or bad, and the author has no liabilities. We all know that AI models can produce both safe and unsafe images for work, so be very responsible. For all other matters do read the <a rel="ugc" href="https://huggingface.co/spaces/CompVis/stable-diffusion-license">CreativeML-OpenRail-M</a> license. Other than that, enjoy using this model and I hope this will help you in your endeavors as an artist.</p><p></p><h3 id="heading-2566">Support:</h3><p>First of all, thank you for patronizing this model; it means my efforts didn't go to waste. My goal is to produce more free tools not just for myself and my work, but for others too. <a rel="ugc" href="https://ko-fi.com/kiddyyep">Your generosity will go more than a mile. Also, as an artist, writer, programmer, and overall freelancer, I accept commission job</a>. Thank you so much for your support!</p>