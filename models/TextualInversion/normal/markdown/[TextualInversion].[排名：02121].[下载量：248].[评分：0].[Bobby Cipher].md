## Bobby Cipher
### 一、模型概述

- 标签：`character`, `consistent character`, `nobody`, `male`, `cipher`
- 下载数：248
- 收藏人数：12
- 评论人数：4
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-05-26T02:45:27.980Z
  - 原始模型：SD 1.5
  - 下载数：248
  - 评分人数：0
  - 评分：0
- 下载地址
  - [BobbyCipher.bin](https://civitai.com/api/download/models/81333)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3afe4e06-5802-4b84-afa5-b0b9c2a56773/width=450/913946.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/68186f73-7131-4a33-b14a-1800c1965cb8/width=450/913893.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1c016082-43c1-4eac-a777-72b496195bd1/width=450/913862.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d7016663-f106-4ec2-a061-d67f2c973d3f/width=450/913865.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Bobby Cipher is a person who doesn't exist. You can use him if you need a <a target="_blank" rel="ugc" href="https://civitai.com/tag/consistent%20character">consistent character</a>. Please have a look at other <a target="_blank" rel="ugc" href="https://civitai.com/tag/nobody">Nobody </a>models for contributions by other folks including those created with the <a target="_blank" rel="ugc" href="https://civitai.com/tag/lastname">LastName </a>and <a target="_blank" rel="ugc" href="https://civitai.com/tag/NBDY">NBDY </a>tags.</p><p>Follow me if you'd like to be notified of future models!</p><h3>Notes on Males</h3><ul><li><p>Turns out making a male character work is a bit more challenging than a female; all of the models I tried with this embedding seem to be <em>really</em> female-centric. Not surprising of course given how these models are mostly used 😊. But it does mean that randomly you'll get a female Bobby Cipher--no kidding--especially if your prompt even hints at a female subject (clothes, setting, etc). Prompting with “<strong>BobbyCipher, a man</strong>” can also help.</p></li><li><p>In my hours of trying to get good images with Bobby, it appears that a lot of men trained in the base models are classic squared-jawed (and sometimes muscly) actors or models. Not that you can't prompt away from those obviously. You also might need to prompt for color or put black and white in your negative prompt because Bobby looks a lot like classic actors from the 40s-60s.</p></li><li><p>I'm still exploring males, and have another embedding I'm working on, so stay tuned as I get better at doing them.</p></li></ul><h3>Installation</h3><p>To install, download the <code>.bin</code> file and then place in the <code>stable-diffusion-webui/embeddings/</code> folder. Then you'll either need to restart WebUI or tap the Refresh button in the Textual Inversions tab in the Extra Networks tab.</p><h3>To Use</h3><p>The trigger word for Automatic1111's webui is <code>BobbyCipher</code> which you can use in your prompt. (It should be <code>&lt;bobbycipher&gt;</code> for InvokeAI). See the gallery below for some examples.</p><h3>A note about what I use to generate images</h3><ul><li><p>My main go-to photorealistic model is <a target="_blank" rel="ugc" href="https://civitai.com/models/13020/avalon-truvision">Avalon TRUVision V2</a> but I also might use <a target="_blank" rel="ugc" href="https://civitai.com/models/4201/realistic-vision-v20">RealisticVision 2.0</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/4398/protogen-infinity-official-release">Protogen Infinity</a>, or <a target="_blank" rel="ugc" href="https://civitai.com/models/6431/hardblend">HARDBlend</a></p></li><li><p>Many of the images in the gallery use TRUVision for the initial <strong>txt2img</strong> and then RealisticVision/Protogen for a quick <strong>img2img</strong> pass with denoising set to .10 - .15 to add some additional skin texture. Unfortunately that first generation information isn't embedded into the PNG.</p></li><li><p>I always use the <strong>vae-ft-mse-840000</strong> as my VAE. <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/resolve/main/vae-ft-mse-840000-ema-pruned.safetensors">You can find it at HuggingFace</a>. You can enable the VAE dropdown menu in WebUI by going to Settings -&gt; User Interface -&gt; Quicksettings list and adding "<strong>sd_vae</strong>"</p></li><li><p>When I use Hires Fix to upscale I usually use<a target="_blank" rel="ugc" href="https://upscale.wiki/wiki/Model_Database"> 4x-UltraSharp</a> for the Upscaler and enable Tiled VAE which is part of the<a target="_blank" rel="ugc" href="https://github.com/pkuliyi2015/multidiffusion-upscaler-for-automatic1111"> Multidiffusion Upscaler package</a></p></li><li><p>If I upscale even further in <code>img2img</code> I'll use a combination of <a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=EmA0RwWv-os">ControlNet 1.1's </a><code>tile_resample</code><a target="_blank" rel="ugc" href="https://www.youtube.com/watch?v=EmA0RwWv-os">/tile</a> model and Ultimate SD Upscaler</p></li></ul>