## Lula Cipher
### 一、模型概述

- 标签：`character`, `female`, `consistent character`, `nobody`, `woman`, `cipher`
- 下载数：490
- 收藏人数：49
- 评论人数：0
- 评分人数：4
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-16T03:26:06.937Z
  - 原始模型：SD 1.5
  - 下载数：490
  - 评分人数：4
  - 评分：5
- 下载地址
  - [LulaCipher.bin](https://civitai.com/api/download/models/71913)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/527b5825-02b7-4584-81fd-708ae9b3cbd4/width=450/803215.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bfd0662a-00fe-4fe4-8d76-61080819f67a/width=450/803219.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d617a8f5-afb3-4089-be2e-d3294b93b000/width=450/803221.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2f81a9c0-3394-406f-a8a2-44331df66f1c/width=450/803216.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Lula Cipher is a person who doesn't exist. You can use her if you need a <a target="_blank" rel="ugc" href="https://civitai.com/tag/consistent%20character">consistent character</a>. She has a tendency to wear hoop earrings (because her creator forgot to caption them!), so you may need to stick "earrings" in your negative prompt. I might re-train to remove them in future. </p><p>Please have a look at other <a target="_blank" rel="ugc" href="https://civitai.com/tag/nobody">Nobody </a>models for contributions by other folks including those created with the <a target="_blank" rel="ugc" href="https://civitai.com/tag/lastname">LastName </a>and <a target="_blank" rel="ugc" href="https://civitai.com/tag/NBDY">NBDY </a>tags.</p><p>Follow me if you'd like to be notified of future models!</p><h3>Installation</h3><p>To install, download the <code>.bin</code> file and then place in the <code>stable-diffusion-webui/embeddings/</code> folder. Then you'll either need to restart WebUI or tap the Refresh button in the Textual Inversions tab in the Extra Networks tab.</p><h3>To Use</h3><p>The trigger word is <code>LulaCipher</code> which you can use in your prompt. See the gallery below for some examples.</p><h3>A note about what I use to generate images</h3><ul><li><p>My main go-to photorealistic model is <a target="_blank" rel="ugc" href="https://civitai.com/models/13020/avalon-truvision">Avalon TRUVision V2</a> but I also might use <a target="_blank" rel="ugc" href="https://civitai.com/models/4201/realistic-vision-v20">RealisticVision 2.0</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/4398/protogen-infinity-official-release">Protogen Infinity</a>, or <a target="_blank" rel="ugc" href="https://civitai.com/models/6431/hardblend">HARDBlend</a></p></li><li><p>Many of the images in the gallery use TRUVision for the initial <strong>txt2img</strong> and then RealisticVision/Protogen for a quick <strong>img2img</strong> pass with denoising set to .10 - .15 to add some additional skin texture. Unfortunately that first generation information isn't embedded into the PNG.</p></li><li><p>I always use the <strong>vae-ft-mse-840000</strong> as my VAE. <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/resolve/main/vae-ft-mse-840000-ema-pruned.safetensors">You can find it at HuggingFace</a>. You can enable the VAE dropdown menu in WebUI by going to Settings -&gt; User Interface -&gt; Quicksettings list and adding "<strong>sd_vae</strong>"</p></li><li><p>When I use Hires Fix to upscale I usually use<a target="_blank" rel="ugc" href="https://upscale.wiki/wiki/Model_Database"> 4x-UltraSharp</a> for the Upscaler and enable Tiled VAE which is part of the<a target="_blank" rel="ugc" href="https://github.com/pkuliyi2015/multidiffusion-upscaler-for-automatic1111"> Multidiffusion Upscaler package</a></p></li><li><p>If I upscale even further in <code>img2img</code> I'll use a combination of <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=EmA0RwWv-os">ControlNet 1.1's </a><code>tile_resample</code><a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=EmA0RwWv-os">/tile</a> model and Ultimate SD Upscaler</p></li></ul>