## Cogecha 焦茶 style LoRA
### 一、模型概述

- 标签：`anime`, `style`, `art style`
- 下载数：1268
- 收藏人数：402
- 评论人数：0
- 评分人数：1
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] CogechaV1

- 统计数据
  - 发布时间：2023-03-18T00:27:52.309Z
  - 原始模型：Other
  - 下载数：1268
  - 评分人数：1
  - 评分：5
- 下载地址
  - [Cogecha.safetensors](https://civitai.com/api/download/models/24836)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ccaf8b29-2a08-484b-cdf2-006f1b980500/width=450/271542.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a1d2c35c-797a-4f3e-1def-7e12f7cdbd00/width=450/271551.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8fe9e3fb-25e3-4773-313a-5b515558d200/width=450/271550.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/80ca1e8a-244a-4d89-499a-f907e46dfd00/width=450/271549.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>This is a loRA trained on the style of Cogecha's art</p><p></p><h3>Features</h3><ul><li><p>Is easily composable with character loras</p></li><li><p>Can generate both landscape and characters, <strong>though landscape will require the keyword "scenery"</strong>, and will occasionally have people pop up randomly.</p></li></ul><p></p><h3>Compatibility</h3><p>Trained on the NAI model, and is therefore compatible with any anime-styled model such as Anything, Counterfeit, AOM, and PastelMix, etc.</p><p></p><h3>Recommended Weight</h3><p>I recommend you use the lora at weight = 1.0. <strong>If the image fries when composed with another lora at weight = 1.0, it is most likely the fault of the other lora.</strong></p><p></p><h3>How do I prevent frying the image</h3><p>If your other loRA causes your image to fry, you can prevent this by downloading <a target="_blank" rel="ugc" href="https://github.com/mcmonkeyprojects/sd-dynamic-thresholding">https://github.com/mcmonkeyprojects/sd-dynamic-thresholding</a> and:</p><ul><li><p>enable dynamic thresholding</p></li><li><p>set your mimic CFG scale to some low number like 5 or 6</p></li><li><p>open up dynamic thresholding advanced options</p></li><li><p>select cosine down as the CFG scale scheduler</p></li></ul>