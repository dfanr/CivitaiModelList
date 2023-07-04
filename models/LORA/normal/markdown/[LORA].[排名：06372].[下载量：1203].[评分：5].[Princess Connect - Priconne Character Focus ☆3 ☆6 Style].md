## Princess Connect - Priconne Character Focus ☆3/☆6 Style
### 一、模型概述

- 标签：`anime`, `highly detailed`, `social game`, `style`, `solo focus`, `art style`, `princess connect`, `mobile game`, `dynamic pose`, `プリコネ`, `composition`
- 下载数：1203
- 收藏人数：291
- 评论人数：0
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1-Counterfeit

- 统计数据
  - 发布时间：2023-03-23T18:58:42.238Z
  - 原始模型：SD 1.5
  - 下载数：1203
  - 评分人数：2
  - 评分：5
- 下载地址
  - [priconne_mypage_1-counterfeit-60.safetensors](https://civitai.com/api/download/models/19708)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cc04a985-1502-4669-d825-c99259509200/width=450/207441.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ea55100d-a2c6-49a8-2f99-631410b58a00/width=450/207445.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/add13efc-69e8-4012-f7dc-ca02fe622000/width=450/207444.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/406a2747-0a77-465e-2d6c-3b915e69b700/width=450/207443.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This LoRA model is a bit unique in that not only does it assist in imitating the Princess Connect! Re:Dive art style, but due to the relatively consistent composition and posing in the reference works it is very good at creating scenes with a centrally located character as the focus with high level of detail for and around the character.</p><p></p><h2>Main features</h2><ul><li><p>Good at wide aspect ratios</p></li><li><p>Good at keeping characters in frame ("feet out of frame", "thighs", etc. prompts won't cause super zoom in nearly as often)</p></li><li><p>Good at enhancing visual elements around the subject character</p></li><li><p>Priconne art style</p></li></ul><h3>Other features</h3><ul><li><p>Good for highres fix (all images bucket to 960x512, trained at 960 res)</p></li><li><p>A bit better than usual at background continuity across areas interrupted by foreground (just a little, don't expect miracles)</p></li><li><p>Helps somewhat with Counterfeit-V2.5 LoRA compatibility by reducing the multiple characters appearing issue.</p></li><li><p>Can assist with composing scenes for use with ControlNet, img2img to achieve detailed compositions of different styles</p></li></ul><p></p><h2>Use &amp; Prompting</h2><ul><li><p>No activation tokens are required.</p></li><li><p>(At the moment) For use with <a target="_blank" rel="ugc" href="https://civitai.com/models/4468/counterfeit-v25">Counterfeit-V2.5</a>. I can't guarantee it'll work well on any other model, as LoRA trained on Counterfeit-V2.5 tend to behave oddly when used elsewhere.</p></li><li><p>Weights between 0.6-1.0 recommended.</p><ul><li><p>If using with character LoRA, try starting on the lower end</p></li><li><p>Other style LoRAs will tend to clash. I recommend low or no weight of the accompanying LoRA for initial gen and then img2img afterwards</p></li></ul></li><li><p>Sometimes, faces will appear on the right side (due to ☆6 Rima...). Add (solo) or other such emphasis/negatives to suppress this.</p></li></ul><p></p><h2>Dataset</h2><p>All ☆3 and ☆6 character art up to Café Tamaki. Six star artworks were repeated 4x per epoch, three star 1x per.</p><p>Tagging was done via wd14-swinv2-v2 with threshold 0.15. All character tags were then removed.</p>