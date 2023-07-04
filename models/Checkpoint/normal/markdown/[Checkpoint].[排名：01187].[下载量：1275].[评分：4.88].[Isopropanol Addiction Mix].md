## Isopropanol Addiction Mix
### 一、模型概述

- 标签：`anime`, `general purpose`, `highly detailed`, `base model`, `model`, `illustration`, `digital illustration`, `fantasy`, `photography`, `photorealism`, `semi-realistic`
- 下载数：1275
- 收藏人数：478
- 评论人数：7
- 评分人数：8
- 评分：4.88

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Version 1.0

- 统计数据
  - 发布时间：2023-03-22T19:20:01.325Z
  - 原始模型：SD 1.5
  - 下载数：1275
  - 评分人数：8
  - 评分：4.88
- 下载地址
  - [isopropanolAddiction_version10.safetensors](https://civitai.com/api/download/models/27329)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0cb2b481-fb37-4785-2aff-762fe9bbf500/width=450/300893.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d1de2bc9-bc80-4a44-945c-58478940c400/width=450/300908.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f67ca198-209a-4b4e-12c8-a65f1f9dab00/width=450/300907.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0a3d0921-1260-4417-1c8a-c43dae5e1800/width=450/300904.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>Introduction</strong></p><p>Isopropanol Addiction Mix (so named because of my ongoing struggles with drinking rubbing alcohol) is a semi-realistic merge of a few different models, mostly anime, that has resulted in a nice versatile model. It works surprisingly well with a lot of LoRAs, and produces very good close-up details. It is based, ultimately, on Anything v4.5 and BasilMix.</p><p></p><p><strong>Recommended Settings</strong></p><p>These are the settings that I use personally. Feel free to experiment.</p><ul><li><p>Sampler: DPM++ 2M Karras</p></li><li><p>CFG Scale: 7.5</p></li><li><p>Steps: 20</p></li><li><p>Clip Skip: 2</p></li><li><p><strong>Hires Upscale (best enjoyed with this):</strong> Either Latent (Nearest-Exact) or whatever your preferred upscaler is, such as <a target="_blank" rel="ugc" href="https://mega.nz/folder/qZRBmaIY#nIG8KyWFcGNTuMX_XNbJ_g">4x-UltraSharp</a>. The former should have a higher denoising strength (0.5 is the hard minimum, sometimes a bit higher than that is needed, I like 0.6), and the latter can have any denoising strength, but I recommend 0.3-0.4 for it. Again, up to you. If your VRAM keeps getting gobbled up, <a rel="ugc" href="https://github.com/Coyote-A/ultimate-upscale-for-automatic1111">try this extension.</a></p></li><li><p>VAE: <a target="_blank" rel="ugc" href="kl-f8-anime2.ckpt">kl-f8-anime2.ckpt</a>, also known as the Waifu Diffusion VAE, is good and my personal choice. You can also use <a target="_blank" rel="ugc" href="https://huggingface.co/NoCrypt/blessed_vae/tree/main">blessed2.vae.pt</a>.</p></li><li><p>Positive prompt: See the examples above. For a more realistic look, try adding "hyperrealistic" to your prompt. Equally "anime" may shift you in the other direction, but only so far.</p></li><li><p>Negative prompt: A lot of models seem to have a bit of an issue with earrings and ear piercings being disproportionately common. Try adding "(ear piercing, earrings:1.2)" or similar. Beyond this, I recommend <a target="_blank" rel="ugc" href="https://huggingface.co/datasets/gsdf/EasyNegative/tree/main">EasyNegative</a> and <a target="_blank" rel="ugc" href="https://huggingface.co/Xynon/models/tree/main/experimentals/TI">bad-image-v2-39000</a>. Try the negatives I use in the example images!</p></li><li><p>How Do I Get Darker Images Please Help: Behold! <a target="_blank" rel="ugc" href="https://huggingface.co/Aotsuyu/Kukicha/tree/main">DarkKukiv1.safetensors</a> at 0.3-0.4 LoRA strength. At least, that one is my favourite. You can try other offset noise LoRAs if you want.</p></li></ul><p></p><p>Feel free to share what it creates in a review.</p>