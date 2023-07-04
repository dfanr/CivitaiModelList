## Figma Anime Figures
### 一、模型概述

- 标签：`anime`, `figurines`, `action figure`, `figma`
- 下载数：18501
- 收藏人数：4547
- 评论人数：13
- 评分人数：35
- 评分：4.89

### 二、下载地址（共3个版本）

#### [版本3/共3个版本] figma

- 统计数据
  - 发布时间：2023-02-11T13:05:43.327Z
  - 原始模型：SD 1.5
  - 下载数：17808
  - 评分人数：30
  - 评分：4.87
- 下载地址
  - [figma.safetensors](https://civitai.com/api/download/models/9413)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ed907efe-71df-4bfb-f7da-fc97420a8a00/width=450/90635.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1541e722-b857-4892-6960-13bba4c9a800/width=450/90636.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/83a32549-85bb-4757-b46f-71ea6a59ff00/width=450/90943.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e19d7c34-42a9-4d2b-3300-34926e44ca00/width=450/90710.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本2/共3个版本] figma [alpha16]

- 统计数据
  - 发布时间：2023-02-11T13:05:43.327Z
  - 原始模型：SD 1.5
  - 下载数：397
  - 评分人数：4
  - 评分：5
- 下载地址
  - [figma [alpha16].safetensors](https://civitai.com/api/download/models/9414)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c135c971-2600-4467-0fa8-ddad86b2e900/width=450/90745.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8b5b2952-8a22-41a5-0ee1-255559a4de00/width=450/90744.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1beaaebc-4528-4495-38b9-1aff8d39b400/width=450/90501.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/99560e2b-35e7-4818-5484-63d32a867100/width=450/90500.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共3个版本] figma [7e-5]

- 统计数据
  - 发布时间：2023-02-11T13:05:43.327Z
  - 原始模型：SD 1.5
  - 下载数：296
  - 评分人数：1
  - 评分：5
- 下载地址
  - [figma [7e-5].safetensors](https://civitai.com/api/download/models/9415)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/10afaf60-e3a3-4edb-f7c5-70c68a89f600/width=450/90796.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5eb5ed3a-44a5-435a-1b61-f0f3317e4c00/width=450/90795.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a93ce27f-048d-4bd4-a8fe-e415ed9e9400/width=450/90794.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/61ee6a2f-9410-469e-a9bb-ed60d6a50000/width=450/90512.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p><strong>Note</strong>: I did not train these LoRA models myself. Original source: <a target="_blank" rel="ugc" href="https://huggingface.co/stma/lora-dump">https://huggingface.co/stma/lora-dump</a></p><h2><strong>Recommended settings</strong></h2><p><strong>Quick start</strong></p><ul><li><p>Model: <a target="_blank" rel="ugc" href="https://civitai.com/models/4437/abyssorangemix2-sfw">AbyssOrangeMix2</a></p></li><li><p>LoRA weight: 0.6 (UNet: 0.6, TEnc: 0.25)</p></li><li><p><code>[realistic], [3d], (3dcg), ((octane render)), [fisheye]</code> in positive prompt for realism</p></li><li><p><code>simple background, grey background</code> in negative prompt</p></li><li><p>CLIP skip: 2</p></li><li><p>Sampler: DPM++ SDE Karras (Euler a recommended for other models)</p></li><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/datasets/gsdf/EasyNegative">EasyNegative </a>in negative prompt</p></li></ul><p><strong>Usable</strong></p><ul><li><p>LoRA weight range: 0.2 - 1.15 (UNet: 0.35 - 1.15 TEnc: 0.2 - 1.0)</p></li></ul><p>UNet is required for the style. UNet over 0.65 will look like an anime figure product. Too high UNet weight will melt details.</p><p>Lower TEnc weight will improve generalization. High TEnc will affect composition to look more like an anime figure product photo. Too high will fry the details.</p><p>Start with lower weight and increase as necessary. Requires more weight when mixed with TI embeddings and other LoRAs.</p><h2><strong>Figma</strong></h2><p>Trained on 5,746 images scraped from GoodSmile's international catalogue, including the discontinued products. All images were tagged with <code>figma</code> first and the product name with <code>figma</code> stripped out second, so an image from a product named "figma Hatsune Miku" would be tagged <code>figma, hatsune miku</code>. All other tags came from the WD1.4 tagger. <code>3d</code> and <code>realistic</code> tags seem to work well with it.</p><p>The alpha16 version is better at generalizing, while the 7e-5 version is better at capturing the figure-with-transparent-stand look.</p><h2><strong>Example images</strong></h2><h3>Model</h3><ul><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/gsdf/Counterfeit-V2.5">Counterfeit-V2.5 </a>(TODO: update example images to <a target="_blank" rel="ugc" href="https://civitai.com/models/4437/abyssorangemix2-sfw">AbyssOrangeMix2</a>)</p></li></ul><h3>Textual inversion</h3><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/4972/roxy-migurdia-ti">Roxy Migurdia</a> (character) <code>roxy-migurdia</code></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/5537/megumin-ti">Megumin</a> (character) <code>megumin_1000</code></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/3036/charturner-character-turnaround-helper">Char Turner </a>(composition) <code>chartuner</code></p></li><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/datasets/gsdf/EasyNegative">EasyNegative </a><code>EasyNegative</code></p></li><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/datasets/Nerfgun3/bad_prompt">Bad Prompt </a><code>bad_prompt</code></p></li></ul><h3>Additional LoRA</h3><ul><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/4831/yelan-lora-collection-of-trauters">Yelan</a> (charater) <code>yelan \(genshin impact\)</code></p></li><li><p><a target="_blank" rel="ugc" href="https://civitai.com/models/5126/torino-aqua-style-lora">Torino Aqua</a> (style) <code>torino aqua</code></p></li></ul>