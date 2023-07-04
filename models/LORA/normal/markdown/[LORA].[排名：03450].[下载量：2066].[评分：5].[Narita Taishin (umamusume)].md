## Narita Taishin (umamusume)
### 一、模型概述

- 标签：`anime`, `character`, `umamusume`, `game character`
- 下载数：2066
- 收藏人数：220
- 评论人数：0
- 评分人数：6
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] V1.0

- 统计数据
  - 发布时间：2023-02-16T06:19:34.275Z
  - 原始模型：SD 1.5
  - 下载数：2066
  - 评分人数：6
  - 评分：5
- 下载地址
  - [narita_taishin_lora.safetensors](https://civitai.com/api/download/models/11081)
  - [img.zip](https://civitai.com/api/download/models/11081?type=Training%20Data)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4a6ec727-810b-41fb-e256-30bcadc99a00/width=450/106858.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9958b9b8-c650-475d-bcd8-3ed0a83ff300/width=450/106863.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b9cec798-8433-4a71-0649-029d3ef16700/width=450/106862.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/54604fe9-32f8-4d72-8bd5-0de815776f00/width=450/106861.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>LoRA of Narita Taishin (umamusume)</p><p></p><p>All of my works is free. If you'd like to support me, feel free to <a target="_blank" rel="ugc" href="https://www.buymeacoffee.com/mhtLoRA">buy me a coffee</a>. 👍</p><p></p><p>Recommend options</p><ul><li><p>LoRA weight 0.7~1.0</p></li><li><p>Trigger words</p><ul><li><p>base</p><ul><li><p>narita taishin \(umamusume\)</p></li><li><p>(optional)closed mouth, serious</p><ul><li><p>These tags make her kawaii.</p></li></ul></li></ul></li><li><p>Racing competition clothes :</p><ul><li><p>torn jeans, (asymmetrical clothes:1.1), belt, fur-trimmed jacket, jacket around waist, clothes around waist, midriff, long sleeves, tied shirt, open clothes, yellow shirt, mismatched footwear, asymmetrical footwear</p><ul><li><p>asymmetrical tags might be need higher weight. (It is challenging for AI)</p></li></ul></li></ul></li><li><p>Casual clothes :</p><ul><li><p>black headwear, white shirt, red jacket, long sleeves, open clothes, torn pants, denim, blue pants</p></li></ul></li><li><p>Steampunk costume :</p><ul><li><p>white shirt, long sleeves, center frills, frilled shirt, brown belt, corset, monocle, semi-rimless eyewear, fingerless gloves, official alternate costume, steampunk</p></li></ul></li></ul></li><li><p>Use animefull based model</p></li><li><p>Settings</p><ul><li><p>DPM++ Series(SDE Karras, 2M Karras, etc.)</p></li><li><p>about 20 steps, CFG scale 3.5~6.5</p></li><li><p>kl-f8-anime2.vae</p></li><li><p>CLIP skip = 1</p></li><li><p>If using highres</p><ul><li><p>Latent (bicubic antialiased)</p></li><li><p>Denoising strength 0.55~0.7</p></li></ul></li></ul></li></ul><p></p><p>LoRA training info</p><ul><li><p>based on Animefull-pruned</p></li><li><p>108 images of narita taishin</p><ul><li><p>8x low quality 32 images</p></li><li><p>16x medium quality 32 images</p></li><li><p>32x high quality 44 images</p></li><li><p>=&gt; 1 epoch = 2176 images</p></li></ul></li><li><p>replaced character feature tags with narita taishin \(umamusume\)</p><ul><li><p>horse girl, horse tail, brown hair, blue eyes, etc.</p></li></ul></li><li><p>using aspect ratio bucketing</p></li><li><p>resolution : 768x768</p></li><li><p>rank=alpha=16</p></li><li><p>using <a target="_blank" rel="ugc" href="https://github.com/facebookresearch/dadaptation">dadaptation</a></p></li><li><p>batch size = 4, 9 epochs trained</p></li><li><p>clip skip = 1</p></li></ul><p></p><p>This LoRA may be compatible with animefull-based models (ex. AbyssOrangeMix Series...)</p><p>All uploaded images are output of AbyssOrangeMix2-nsfw, kl-f8-anime2.vae</p>