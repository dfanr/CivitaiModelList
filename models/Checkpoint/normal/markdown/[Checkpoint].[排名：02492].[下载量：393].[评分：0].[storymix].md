## storymix
### 一、模型概述

- 标签：`base model`, `tutorial`, `elf`, `monster girls`, `fight`, `fantasy`, `realistic`, `rpg`
- 下载数：393
- 收藏人数：147
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-30T14:49:31.366Z
  - 原始模型：SD 1.5
  - 下载数：393
  - 评分人数：0
  - 评分：0
- 下载地址
  - [storymix_v10.safetensors](https://civitai.com/api/download/models/75814)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/aa1530c5-0ce3-468b-85e7-b1517dfa96de/width=450/892292.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/47f8d577-7bb1-4db0-b79d-7bc5dd3af7b3/width=450/916507.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/66083907-7a24-4060-8089-8238c58d9abc/width=450/894859.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/854aae79-9ccf-4e15-9753-7646a982607a/width=450/934239.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="overview">Overview</h1><p>The goal of StoryMix is where the boundaries between fantasy and reality merge. With a humble start by discovering its current capabilities and flaws. Future updates will be focusing on improve the model and make it easier to use.<br /></p><p>Positive Prompt: <code>best quality, masterpiece, ultra high res, (photorealistic:1.4), raw photo, sharp focus, HDR, detailed skin</code></p><p>Negative Prompt: <code>Anime, cartoon, ng_deepnegative_v1_75t, (badhandv4:1.2), (worst quality:2), (low quality:2), (normal quality:2), lowres, bad anatomy, bad hands, normal quality, (monochrome), (grayscale) watermark.</code></p><p><br /><strong>Merge Based On:</strong></p><ol><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/8124/a-zovya-rpg-artist-tools"><strong><u>https://civitai.com/models/8124/a-zovya-rpg-artist-tools</u></strong></a></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/47130?modelVersionId=70157"><strong><u>https://civitai.com/models/47130?modelVersionId=70157</u></strong></a></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/43331/majicmix-realistic"><strong><u>https://civitai.com/models/43331/majicmix-realistic</u></strong></a></p></li></ol><p></p><p><strong>(Optional) Recommended VAE</strong><br />to get a better high quality result, please use this VAE:</p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/76118/vae-ft-mse-840000-ema-pruned">https://civitai.com/models/76118/vae-ft-mse-840000-ema-pruned</a></p></li></ul><p><strong>(Optional) Recommended Textual-inversion</strong></p><p>to prevent bad hands and ugly results please use these textual-inversions:</p><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/16993/badhandv4-animeillustdiffusion">https://civitai.com/models/16993/badhandv4-animeillustdiffusion</a></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/4629/deep-negative-v1x">https://civitai.com/models/4629/deep-negative-v1x</a></p></li></ul><p></p><p></p><p><strong>Steps used when I generate images using this model</strong></p><ol><li><p>Start prompt engineering</p><ol><li><p>Using 'txt-2-img',<br />or 'img-2-img' using existing images &amp; prompts if you want</p></li><li><p>Start simple without <a target="_blank" rel="ugc" href="https://github.com/Bing-su/adetailer">After Detailer Extension</a></p></li><li><p>Settings:</p><ol><li><p>Sampling method = Euler a / DPM++2MKarras</p></li><li><p>Sampling steps = 20-60</p></li><li><p>CFG = 5-7 for more creativity, 10-15 to be strict</p></li><li><p>Size: 920 x 512 px (portrait)<br />- Or 512x920 landscape mode that tend to generate more characters<br />- Or 512x512 if you prefer to use the result for training</p></li><li><p>Start with batch count = 1-4</p></li></ol></li><li><p>Edit the prompts until reaching the intended results</p><ul><li><p>(Recommended) Ask chatGPT to generate text-to-image prompts suitable for Stable Diffusion according your requirements</p></li></ul></li></ol></li><li><p>Polish the Details (if needed)</p><ol><li><p>Keep using 'txt-2-img' with the config in step 1</p><ul><li><p>or choose the image you like and 'Send to ImgToImg' if you want it to be very similar</p></li></ul></li><li><p>Reuse seed from the previous image<br />(Useful when we want to keep some major details like faces)</p></li><li><p>Use the <a target="_blank" rel="ugc" href="https://github.com/Bing-su/adetailer">After Detailer Extension</a></p><ol><li><p>ADetailer Model = yolov_8n</p><ol><li><p>For most cases, first detailer is for face</p></li><li><p>Second detailer is for hands</p></li><li><p>Set Confidence = above 65 to avoid false detection</p></li></ol></li></ol></li><li><p>Settings:</p><ol><li><p>Sampling method = Euler a / DPM++2MKarras</p></li><li><p>Sampling steps = 40-100 for a better quality</p></li></ol></li><li><p>(optional) Use DeepBoru to improve prompts but be careful to also check missing prompts not covered by DeepBoru</p></li><li><p>(optional) Fix minor flaws with inpainting/sketch/control-net or other tools</p><ol><li><p>Inpainting:</p><ol><li><p>Erase area to improve</p></li><li><p>Then generate with high resolution</p></li></ol></li><li><p>Sketch/Control-net: rarely used, but can be useful to improve minor flaws:</p><ol><li><p>Bad hands can be fixed with control-net depth map</p></li><li><p>Bad pose with control-net OpenPose</p></li><li><p>When prompt is hard, minor tweaks can be improved with sketch, e.g. adding missing legs or characters</p></li></ol></li></ol></li></ol></li><li><p>Send to Extras</p><ol><li><p>Scale to = 1080 x 1920 / 1920x1080</p></li><li><p>Upscaler1 = SwinIR_4x or other 4X scaler</p></li><li><p>GFPGAN visibility = 0.95 </p></li><li><p>(If it needs cropping) Crop to fit = checked</p></li></ol></li></ol><p></p>