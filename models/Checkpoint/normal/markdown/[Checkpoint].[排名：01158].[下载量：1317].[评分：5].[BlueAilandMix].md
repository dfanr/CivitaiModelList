## BlueAilandMix
### 一、模型概述

- 标签：`anime`, `anime screencap`, `style`, `アニメ塗り`
- 下载数：1317
- 收藏人数：271
- 评论人数：1
- 评分人数：3
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.1

- 统计数据
  - 发布时间：2023-06-10T18:56:58.167Z
  - 原始模型：SD 1.5
  - 下载数：636
  - 评分人数：0
  - 评分：0
- 下载地址
  - [blueailandmix_v11.safetensors](https://civitai.com/api/download/models/93256)
  - [blueailandmix_v11.safetensors](https://civitai.com/api/download/models/93256?type=Model&format=SafeTensor&size=full&fp=fp16)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/31e87e01-2292-486a-92b9-7a15f67641aa/width=450/1100026.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a34bd2f8-c7d3-4b0f-a760-d1793f3f4753/width=450/1100028.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/23bee355-becf-4662-a503-902ee38e7581/width=450/1100035.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6e408d7c-e4ed-4072-b832-7e0627dcde59/width=450/1100036.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-06-10T18:45:21.292Z
  - 原始模型：SD 1.5
  - 下载数：681
  - 评分人数：3
  - 评分：5
- 下载地址
  - [blueailandmix_v10.safetensors](https://civitai.com/api/download/models/76191?type=Model&format=SafeTensor&size=full&fp=fp16)
  - [blueailandmix_v10.safetensors](https://civitai.com/api/download/models/76191)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/57952db7-0351-4ec6-8405-13cfe8d8422a/width=450/852688.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5898deac-5642-4173-86a6-64578984111c/width=450/852671.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/432ee898-52a5-4d07-bc6e-4d654f8d8b54/width=450/852607.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3df25597-5f66-4fab-b195-2a5b617e49f8/width=450/852605.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>Noted Changes from 1.0:</strong></p><ul><li><p>Less illustrative shadows</p></li><li><p>flatter hair color</p></li><li><p>lighter coloring</p></li><li><p>lighter lines</p></li></ul><p>Issues:</p><ul><li><p>1.1 has a stronger bias towards female characters so if you want to make male characters put more emphasis on male keywords, and avoid using terms that could cause conceptbleed</p></li><li><p>I highly recommend using OUTD with the <a target="_blank" rel="ugc" href="https://github.com/hako-mikan/sd-webui-lora-block-weight">LoRA block weight extension </a>whenever you are using any kind of LoRA/Lycoris model. I found that are still some cases where the model is unstable with some LoRAs and will introduce a lot of artifacts to the image. You can probably use the mentioned extension to fix the issue. I'm not sure what causes it though.</p></li></ul><p>Mixed several lycoris from <a target="_blank" rel="ugc" href="https://civitai.com/models/86840?modelVersionId=93034">Cel Shaded Artist Styles [Screencap, Official/Promo Styles]</a> and <a target="_blank" rel="ugc" href="https://civitai.com/models/29215?modelVersionId=35038">Blue Archive Artstyle LoHA Model Released. </a>Again, I have absolutely no idea what I am doing but I noticed that mixing the Lycoris models together did give a noticeable impact so I'm updating it as a 1.1 minor update. The demo images were made by upscaling using AnimeSharp4x and adetailer.</p><p></p><p></p><p>Uploaded by request. Made in an attempt to have an anime-style shading closer to the cel-shading/flat color artstyle with softer lighting and colors. I don't understand how model-merging works so I am not able to fix any problems that arise.</p><p></p><p></p><h1 id="heading-2941">Recommended Settings</h1><p><strong>Sampler</strong>: Euler or DPM++ 2M Karras</p><p>Steps: 20</p><p><strong>CFG</strong>: 7</p><p><strong>VAE</strong>: ClearVAE or any anime based VAE works fine.</p><p><strong>Highres fix: </strong><em><u>Recommended </u></em>but is still possible to get good quality at lower resolution</p><p>CLIP skip : 2</p><p><strong>Face Restoraton: </strong><em><u>Disabled</u></em>. Make sure that Face restoration is not enabled otherwise you'll get realistic lips.</p><p><strong>Upscaler</strong>: AnimeSharp4x is what I normally use. I don't recommend using the latent upscaler.</p><p><strong>Upscale Denoise:</strong> 0.5 with AnimeSharp4x. Denoising strength varies for each upscaler.</p><p><strong>Negative Embeddings</strong>: <a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative">EasyNegative</a>, <a target="_blank" rel="ugc" href="https://huggingface.co/gsdf/Counterfeit-V3.0/tree/main/embedding">EasyNegativeV2</a>, <a target="_blank" rel="ugc" href="https://huggingface.co/SweetLuna/Aurora/tree/main/AuroraEmbeddings">AuroraNegative,KFHB</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/16993/badhandv4-animeillustdiffusion">badhandv4</a>, and <a target="_blank" rel="ugc" href="https://civitai.com/models/11772/verybadimagenegative">verybadimagenegative </a>seem to work fine. I haven't thoroughly tested what gives the best quality.</p><h1 id="heading-2942">Tips</h1><ol><li><p>Good quality can still be achieved at lower resolution but will require showing only limited portions of the body such as only the face view, or upperbody view.</p></li><li><p>For fullbody poses, hi-res fix with 2x to 4x upscale is recommended to reduce chances of distortion. I recommend using the <a target="_blank" rel="ugc" href="https://github.com/pkuliyi2015/multidiffusion-upscaler-for-automatic1111">MultiDiffusion extension</a> to help with producing large images</p></li><li><p>For Character LoRas, I recommend using the <a target="_blank" rel="ugc" href="https://github.com/hako-mikan/sd-webui-lora-block-weight">LoRA Block Weight extension</a> so the original artstyle from the LoRA does not heavily overwrite the model's artstyle. I normally use OUTD weight preset with my artworks but I found it's rather case by case for each LoRa and does not work all of the time. In those cases, you can try and use other style LoRAs such as the <a target="_blank" rel="ugc" href="https://civitai.com/models/22977/anime-style-lora-with-better-flat-color">アニメ塗り Anime Style</a> to help emphasize the coloring effect.</p></li><li><p>The flat color seems to be more affected by negative keywords such as ((worst quality:1.4,low_quality)) so adjust the weights as needed</p></li></ol><p></p><p></p><h1 id="heading-2943">Model Issues:</h1><ol><li><p>Eyes will get distorted</p></li><li><p>Hands</p></li><li><p>Multiple img2img passes causes final image to have a more purplish tint</p></li><li><p>Bias to younger looking characters</p></li></ol><p></p><p>Issues 1 can be fixed with inpainting. Hands will mostly be luck, editing, ControlNet, and inpainting.</p><p>Issue 3 can be somewhat fixed by using ControlNet LineArt with 1.4 or higher weight and image denoise 0.7. Try using canny instead if you want to keep the background intact. I can't test multi-controlnet with (tile,color-adapter,and line-art) due to vram issues.</p><p>Issue 4 might be solvable by adding words like loli, and loliface to the negative prompt with or without emaphasis.</p><p></p><h2 id="heading-2944">Recipe</h2><p>This is a rather straightforward mix of <a target="_blank" rel="ugc" href="https://civitai.com/models/23723/animix-anime-screenshot-like-style-mix-lora">AniMix</a>,<a target="_blank" rel="ugc" href="https://civitai.com/models/27806/anireality-mix">AniReality</a>, and <a target="_blank" rel="ugc" href="https://civitai.com/models/29764/bluemix">BlueMix</a></p><ol><li><p><a target="_blank" rel="ugc" href="https://github.com/Xerxemi/sdweb-auto-MBW">AutoMBW </a>(AniMix, AniReality) -&gt; AilandMix</p></li><li><p>AilandMix + 0.5 Weighted Sum BlueMix -&gt; BlueAilandMix</p></li></ol><p>V1.1</p><p><strong>Step 1.Lycoris Merged Model(Unreleased)</strong></p><ol><li><p>BlueAilandMixv1 + Cel Shaded Artist Styles [Screencap, Official/Promo Styles] - Eufoniuz 0.6 = Model 1</p></li><li><p>Model 1 + Cel Shaded Artist Styles [Screencap, Official/Promo Styles] Ishiseito 0.6 = Model 2</p></li><li><p>Model 2 + Blue Archive Artstyle LoHA Model Released v1.0-6 0.4 = Lycoris Merged Model</p></li></ol><p>Interestingly, this mix is rather unstable and I noticed that I lost about 2GB of data after merging. It tends have very oversaturated colors and doesn't play well with LoRAs. Interestingly after mixing it with some models, it began to stabilize.</p><p>Step 2.Triple Sum Merge(BlueMix,Ailand)</p><ol><li><p>Models: BlueMix2.5a,Lycoris Merged Model, AilandMix</p></li><li><p>Merge Weight: Alpha = 0.5; Beta = 0.5</p></li></ol><p>End Result: BlueMix 0.25 + Lycoris Merged Model 0.5 + AilandMix 0.25 = v1.1</p>