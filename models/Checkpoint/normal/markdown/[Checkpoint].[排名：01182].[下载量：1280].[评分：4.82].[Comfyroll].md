## Comfyroll
### 一、模型概述

- 标签：`anime`, `hdr`, `style`, `illustration`, `semi-realistic`, `comfyui`, `nsfw`, `2.5d`
- 下载数：1280
- 收藏人数：413
- 评论人数：5
- 评分人数：11
- 评分：4.82

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0 Anime

- 统计数据
  - 发布时间：2023-05-15T14:49:26.633Z
  - 原始模型：SD 1.5
  - 下载数：958
  - 评分人数：7
  - 评分：4.71
- 下载地址
  - [comfyroll_v10Anime.safetensors](https://civitai.com/api/download/models/70926?type=Model&format=SafeTensor&size=pruned&fp=fp32)
  - [comfyroll_v10Anime.safetensors](https://civitai.com/api/download/models/70926)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1119787f-3b71-4789-99ca-1a1888f4dc07/width=450/809021.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c9e3b0f2-a120-4abd-a375-a69820df6392/width=450/795829.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a90fd3a9-25fd-4626-951d-e3f7f14b75d7/width=450/795672.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d0a69130-7ab4-46d1-b8d7-ed9f250a36df/width=450/792506.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-05-15T09:13:42.675Z
  - 原始模型：SD 1.5
  - 下载数：322
  - 评分人数：4
  - 评分：5
- 下载地址
  - [comfyroll_v10.safetensors](https://civitai.com/api/download/models/63154?type=Model&format=SafeTensor&size=pruned&fp=fp32)
  - [comfyroll_v10.safetensors](https://civitai.com/api/download/models/63154)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/39bbe45e-de21-45c8-8b1d-173b83bd16a6/width=450/720124.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/94c198cd-c11e-4075-88be-746bc51bda58/width=450/706780.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cf99d6a7-c47b-4d87-9f88-575ac7f45dea/width=450/706290.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6f0c23a4-57f9-427b-8279-f459b522847e/width=450/704106.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>The <strong>Comfyroll</strong> models were built for use with <strong>ComfyUI</strong>, but also produce good results on <strong>Auto1111</strong>. They currently comprises of a merge of 4 checkpoints.</p><p>The models can produce colorful high contrast images in a variety of illustration styles. A <strong>pseudo-HDR</strong> look can be easily produced using the template workflows provided for the models.</p><p>These checkpoint merges are particuarly good for:</p><ul><li><p><strong>semi-realistic styles </strong>(use <strong>Comyroll</strong>)</p></li><li><p><strong>stylized anime </strong>(use <strong>ComyrollAnime</strong>)</p></li><li><p><strong>illustration styles</strong></p></li><li><p><strong>2D, 2.5D</strong></p></li><li><p><strong>NSFW</strong></p></li></ul><p>These merges were not designed for creating NSFW and in general do not produce unsafe images unless you deliberately prompt for them.</p><p></p><h3><strong>Comfyroll workflow templates:</strong></h3><p>A collection of workflow templates has been designed for use with these models. The collection includes workflows for anime and illustration styles.</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/59806/comfyroll-template-workflows">https://civitai.com/models/59806/comfyroll-template-workflows</a></p><p>These templates were used to create the sample illustrations for the models. I have indicated in the comments on each image the template that was used and additional information such as the clip skip, noise masks and lora.</p><p>It is also planned to create example prompts for use in Auto1111.</p><p></p><h3>Recommended settings (Comfy):</h3><p>Sampler: dpmpp_2m karras, uni_pc normal</p><p>Steps: 10 steps for a contrasty manga-style look and 30+ steps for a smoother look</p><p>Clip Skip: both -1 and -2 both work well, -2 provides a good semi-realistic look, -1 is great for anime and illustration styles</p><p>Img2Img Denoise: usually between 0.85 to 0.95 (lower values are good for illustration styles)</p><p>VAE: vae-ft-mse-840000-ema-pruned (the models do not currently have baked VAE, so you will need a VAE loader node in your workflows)</p><p><em>These models work best when combined with noise masks in Img2Img or ControlNet. Please see the Comfyroll Template Workflows for examples of how to use noise. Recommended noise patterns include white noise, pink noise, dissolve noise and perlin noise.</em></p><p></p><h3>Recommended settings (Auto 1111):</h3><p>Hires fix is strongly recommended</p><p>Sampler: DPM++ 2M Karras, UniPC,</p><p>Steps: 20, Hires 30</p><p>Clip Skip: -2</p><p>VAE: vae-ft-mse-840000-ema-pruned</p><p></p><h3><strong>Prompting:</strong></h3><p>Here are some suggested keywords to use in prompts for these models:</p><ul><li><p>Semi-Realistic Style</p><ul><li><p><em>2.5D, semi-realistic,</em></p></li><li><p><em>highest quality, detailed,</em></p></li><li><p><em>depth of field, natural blur, bokeh, HDR,</em></p></li></ul></li><li><p>Anime Style (<strong>ComfyrollAnime</strong>)</p><ul><li><p><em>2D, 2.5D,</em></p></li><li><p><em>anime line-art, illustration,</em></p></li></ul></li><li><p>Illustration Styles</p><ul><li><p><em>2D, 2.5D,</em></p></li><li><p><em>detailed concept drawing, illustration, line-art, stylized,</em></p></li></ul></li><li><p>Lighting</p><ul><li><p><em>subsurface scattering, chromatic lighting,</em></p></li><li><p><em>neon lighting, moody lighting, cinematic lighting,</em></p></li></ul></li><li><p>Color</p><ul><li><p><em>colorized, flat colors, limited color palette</em></p></li></ul></li><li><p>Camera</p><ul><li><p><em>from-above, from-below, from-side, from-behind,</em></p></li><li><p><em>portrait, cowboy-shot, close-up, long-shot,</em></p></li></ul></li></ul><p></p><h3>Recommended <strong>LoRAs:</strong></h3><p><a target="_blank" rel="ugc" href="https://civitai.com/models/6308?modelVersionId=7393">ukiyo-e</a> 30% strength</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/42402?modelVersionId=47075">NijiV5style</a> with <strong>ComfyrollAnime</strong>, 50% strength</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/65474/loha-longan-style-with-multires-noise-version">Longan/竜眼 Style</a> with <strong>ComfyrollAnime</strong>, 70% strength</p><p></p><h3>Resources for this model:</h3><p><strong>Textual inversions:</strong></p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/7808/easynegative">https://civitai.com/models/7808/easynegative</a></p><p><a target="_blank" rel="ugc" href="https://huggingface.co/yesyeahvh/bad-hands-5">https://huggingface.co/yesyeahvh/bad-hands-5</a></p><p><strong>Upscalers:</strong></p><p><a target="_blank" rel="ugc" href="https://upscale.wiki/wiki/Model_Database">https://upscale.wiki/wiki/Model_Database</a></p><p></p><h3>Links:</h3><p><a target="_blank" rel="ugc" href="https://huggingface.co/Akatsuzi/Comfyroll">https://huggingface.co/Akatsuzi/Comfyroll</a></p><p><a target="_blank" rel="ugc" href="https://www.pixiv.net/en/users/17537676">https://www.pixiv.net/en/users/17537676</a></p><p><a target="_blank" rel="ugc" href="https://www.deviantart.com/akatsuzi">https://www.deviantart.com/akatsuzi</a></p><p><a target="_blank" rel="ugc" href="https://twitter.com/Akatsuzi_AI">https://twitter.com/Akatsuzi_AI</a></p>