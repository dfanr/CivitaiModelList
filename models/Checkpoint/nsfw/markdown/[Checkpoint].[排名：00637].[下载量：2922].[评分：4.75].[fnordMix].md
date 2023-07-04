## fnordMix
### 一、模型概述

- 标签：`girl`, `sexy`, `nudes`, `fantasy`, `realistic`, `women`
- 下载数：2922
- 收藏人数：1195
- 评论人数：10
- 评分人数：16
- 评分：4.75

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-03-11T06:43:29.799Z
  - 原始模型：SD 1.5
  - 下载数：2922
  - 评分人数：16
  - 评分：4.75
- 下载地址
  - [fnordmix_v10.safetensors](https://civitai.com/api/download/models/21484)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/75e70dbe-bfa2-4f30-d581-7a0714989e00/width=450/228160.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e022139f-1202-46e0-f1a0-712a9cd7e700/width=450/228179.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/98d2905f-99cf-4ca4-78b2-949496efaf00/width=450/228178.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/02295a4c-6d2e-431c-f69e-98fb6efed600/width=450/228177.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This mix was originally inspired by the Perfect World technique - a simple 50/50 mix of a super-responsive anime-like base - the incredible <a target="_blank" rel="ugc" href="https://civitai.com/models/7371/rev-animated">Rev v1 - </a>with the realism of Basilmix, and was since extended rather haphazardly with the aim of realistic skin tones, diversity and trying to achieve a more natural facial structure than the somewhat stylised one available with Rev.</p><p>The exact recipe is lost to the sands of time, but includes greater or lesser quantities of:</p><ol><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/7371/rev-animated">Rev v1</a> - <a target="_blank" rel="ugc" href="https://huggingface.co/nuigurumi/basil_mix">Basilmix</a> 50/50</p></li><li><p>some <a target="_blank" rel="ugc" href="https://civitai.com/models/6424/chilloutmix">Chilloutmix</a></p></li><li><p>a dash of <a target="_blank" rel="ugc" href="https://civitai.com/models/4481/pov-skin-texture-dreamlike-r34">PoV Skin Texture - Dreamlike r34</a></p></li></ol><p>And a few others, not sure what anymore. But I like it and thought perhaps you might too. </p><p>The sample images aren't touched up in any way other than hires-fix, and aren't really cherry-picked for quality, just a sample of pics I like to represent the range.</p><ul><li><p>I pretty much always add the default <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt">stability 84000 VAE</a> but it doesn't really mind if you want to try something different.</p></li><li><p>It takes LORAs and embeddings very well, and is capable of some significant diversity of characters.</p></li><li><p>Hands and feet aren't perfect, but usually turn out alright. Faces can be a little dodgy at distance, but isn't that always the way?</p></li><li><p>Reasonably forgiving of high canvas sizes, doesn't care too much about dimensions - seems equally happy square or 2/3 or 3/2, 640x640 is a nice spot for square aspect ratio. 512x768 is the natural sweetspot but it even remains coherent at 640x960.</p></li><li><p>2GB safetensor is the only option for now, it's pruned to bf16 and ema-only.  If there's overwhelming interest I'll try to recreate the recipe via some form of trail and error and then we'll be able to generate submixes and alternate formats.</p></li><li><p>VERY HORNY model, be warned</p></li></ul><p>Kinda 2.9D out of the box.  For max photorealism, it helps to add pre-prompts such as: </p><p>(8k, RAW photo, highest quality, best quality, masterpiece, ultra-detailed, hires, absurdres, sharp focus:1.2), (photorealistic, hyper-realistic:1.37),</p><p>Go easy on the negative prompts, I tend to stick with something like</p><p>EasyNegative, (worst quality, low quality:1.4), (malformed hands, poorly drawn hands, mutated fingers:1.4)</p>