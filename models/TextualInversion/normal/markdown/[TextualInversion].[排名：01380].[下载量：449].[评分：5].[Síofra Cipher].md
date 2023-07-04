## Síofra Cipher
### 一、模型概述

- 标签：`character`, `female`, `consistent character`, `nobody`, `woman`, `cipher`
- 下载数：449
- 收藏人数：54
- 评论人数：5
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-23T00:35:30.181Z
  - 原始模型：SD 1.5
  - 下载数：449
  - 评分人数：1
  - 评分：5
- 下载地址
  - [SiofraCipher.bin](https://civitai.com/api/download/models/101328)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/36ab6469-a3d9-472a-aa96-668cdd5b7540/width=450/1239636.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b140598b-a190-4426-a222-f44429ab5570/width=450/1239638.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cfad0cf8-5b6f-4eac-a2c8-90a6cdc264a4/width=450/1239632.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/54c76cd7-6a93-4ca8-9d7c-8564a9b8f8b3/width=450/1239639.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Síofra Cipher is a person who doesn't exist. You can use her if you need a <a target="_blank" rel="ugc" href="https://civitai.com/tag/consistent%20character">consistent character</a>.</p><p>Please have a look at other <a target="_blank" rel="ugc" href="https://civitai.com/tag/nobody">Nobody </a>models for contributions by other folks including those created with the <a target="_blank" rel="ugc" href="https://civitai.com/tag/lastname">LastName </a>and <a target="_blank" rel="ugc" href="https://civitai.com/tag/NBDY">NBDY </a>tags.</p><p>Follow me if you'd like to be notified of future models!</p><h3 id="heading-766">Freckles and Red Hair</h3><p>If you've ever tried to get freckles using Stable Diffusion you know they can be a challenge. A lot of times they simply look like a uniform pattern of dots or they don't work at all. You might see that with this model as well -- if you do I would suggest trying a different base model OR adding freckles to your negative prompt.</p><p>Red hair can also be tough sometimes for SD -- you might notice Síofra's hair generate <em>very</em> bright red. To mitigate this I would add a little bit more noise with something like LowRA ( see Suggested Resources below).</p><h3 id="heading-340">Installation</h3><p>To install, download the <code>.bin</code> file and then place in the <code>stable-diffusion-webui/embeddings/</code> folder. Then you'll either need to restart WebUI or tap the Refresh button in the Textual Inversions tab in the Extra Networks tab.</p><h3 id="heading-341">To Use</h3><p>The trigger word is <code>SiofraCipher</code> which you can use in your prompt. See the gallery below for some examples. For InvokeAI it should be <code>&lt;siofracipher&gt;</code></p><h3 id="heading-342">A note about what I use to generate images</h3><ul><li><p>My main go-to photorealistic models right now are <a target="_blank" rel="ugc" href="https://civitai.com/models/4201/realistic-vision-v20">RealisticVision 2.0</a> and <a target="_blank" rel="ugc" href="https://civitai.com/models/28059?modelVersionId=89464">ICBINP</a>.</p></li><li><p>I always use the <strong>vae-ft-mse-840000</strong> as my VAE. <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/resolve/main/vae-ft-mse-840000-ema-pruned.safetensors">You can find it at HuggingFace</a>. You can enable the VAE dropdown menu in WebUI by going to Settings -&gt; User Interface -&gt; Quicksettings list and adding "<strong>sd_vae</strong>"</p></li><li><p>To upscale I'll use a combination of <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=EmA0RwWv-os">ControlNet 1.1's </a><code>tile_resample</code><a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=EmA0RwWv-os">/tile</a> model and Ultimate SD Upscaler<br /></p></li></ul>