## ForgeSaga Landscape
### 一、模型概述

- 标签：`background`
- 下载数：1699
- 收藏人数：415
- 评论人数：8
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-05T02:49:25.708Z
  - 原始模型：SD 1.5
  - 下载数：1699
  - 评分人数：2
  - 评分：5
- 下载地址
  - [forgesagaLandscape_v10.safetensors](https://civitai.com/api/download/models/89497)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/74b4bec2-81c1-4328-957c-6cc19c9d58d1/width=450/1035488.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5566c1d1-7bc1-430c-8247-66f46353ebe3/width=450/1035228.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/23a4c522-ab51-4d2b-b992-eb38ae8a3a23/width=450/1035230.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b76f976a-2430-4eef-bc6c-469c708ca62c/width=450/1035231.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>I've been using this model to generate background images for my AI driven Text-based RPG game at <a target="_blank" rel="ugc" href="http://www.forgesaga.com">www.forgesaga.com</a> and enjoyed the results so much I had to share it with the community too.</p><p>Sample Prompt with a bunch of loras to get the results I am getting:<br /><br />POSITIVE:</p><p>painting of ..., late night, dusk, night, dark, starlit, fantasy, medieval, loading screen art, &lt;lora:epiNoiseoffset_v2:0.2&gt;, &lt;lora:howlbgsv3:0.5&gt;, &lt;lora:artbytokiame:0.5&gt;, &lt;lora:add_detail:0.3&gt;, ink outlines, wallpaper, vignette, matte painting by (Kazimir Malevich:1.1), simple lighting, dynamic shading, complementary colors, HDR, absurdres, cinematic, muted colors, limited color pallete, (masterpiece:1.2), (best quality:1.1)<br /><br />NEGATIVE:<br />realistic, character, people, photograph, 3d render, blurry, grayscale, oversaturated, bad-hands-5, easynegative, photozoov15, structurezoov15, verybadimagenegative_v1.3, cropped, (watermark, logo, signature, text, signature:1.4)<br /><br />Settings:<br /> "cfg_scale": 7, "sampler_name": "Euler a", "steps": 40<br /><br />To get the results above, I personally run my generations through a second img2img pass at 0.45 noise with the same settings and a canny controlnet of 0.3 to keep the general shapes intact.<br /><br />I then do a final upscale to final resolution.</p><p>Enjoy!</p>