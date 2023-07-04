## Lunar Radiance (月光Mix)
### 一、模型概述

- 标签：`anime`, `lighting`, `scenery`, `background`, `caustics`, `bokeh`, `backgrounds`
- 下载数：582
- 收藏人数：144
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Lua's Light

- 统计数据
  - 发布时间：2023-06-13T02:42:15.682Z
  - 原始模型：SD 1.5
  - 下载数：582
  - 评分人数：0
  - 评分：0
- 下载地址
  - [lunarRadianceMix_luasLight.safetensors](https://civitai.com/api/download/models/94872)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f157d860-f90b-4513-8112-77f1ec1c7520/width=450/1125799.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5d3f423c-925b-4cb4-86fd-19bf11f68dc5/width=450/1125786.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d0cc23a3-8bab-4c75-adb2-d8d67130c2e8/width=450/1125787.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/83b3e8c7-7ab9-4001-b3cd-8f619a9b72f0/width=450/1125792.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><em>Dream... not of what you are, but of what you want to be.</em></p><p></p><p>A mix targeted at enhancing lighting effects. The base checkpoint is also CLIP expanded using the (now deleted) checkpoint ALunarDreamV2. Primarily it is good at achieve dynamism in lighting effects. It is not a very bright checkpoint by default, but it is extremely good at doing backlighting, bokeh, caustics, and glare. It ends up very strong in twilight or sunset scenes. In addition, because of the clip expansion, you can use artists trained by ALunarDream to alter the style of the model organically without having use LoRAs. A comparison grid has been uploaded as an example.</p><p></p><p>One thing you might want to be aware of is that the light diffusion tends to sometimes express itself as mist or other radiance effects around a backlit object or character. I've bundled it with blessed-vae which is specifically good at picking up on noise offset by default so the pictures that come out will end up pretty dark. If you're not a fan of that, you can use any other VAE. I recommend Waifu Diffusion's for bright pastel colors and clearvae for in-between.</p><p></p><p>HuggingFace: <a target="_blank" rel="ugc" href="https://huggingface.co/Jemnite/ALunarLight">https://huggingface.co/Jemnite/ALunarLight</a></p><p></p><p>My recommendation is to use the negative embeds for AuroraONE as they are the best at fixing your image while not changing the style IMO. If you notice, all of the images are generated with </p><pre><code>(worst quality, low quality:1.4), AuroraNegative, KHFB, negative_hands</code></pre><p>With AuroraNegative and KHFB being AuroraONE's negative embeddings and negative_hands being <a rel="ugc" href="https://civitai.com/models/56519/negativehand-negative-embedding">this one</a>.</p>