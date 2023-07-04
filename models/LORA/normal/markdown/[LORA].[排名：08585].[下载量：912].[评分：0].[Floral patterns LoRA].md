## Floral patterns LoRA
### 一、模型概述

- 标签：`art`, `floral`, `design`, `pattern`, `style`, `graphic design`, `flower`
- 下载数：912
- 收藏人数：272
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-07T21:50:14.232Z
  - 原始模型：Other
  - 下载数：912
  - 评分人数：0
  - 评分：0
- 下载地址
  - [floral_lora.safetensors](https://civitai.com/api/download/models/39468)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/63c72334-7ae5-4014-1066-9743fdc6a700/width=450/437134.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/62b5f595-165c-4343-74d9-b36ad894c200/width=450/437133.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4db1bf81-a8af-4b3e-fd7a-48d995517500/width=450/437132.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/57664579-4dca-4739-ed07-0f6696232600/width=450/437127.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Trained similarly to full model for floral patterns: <a target="_blank" rel="ugc" href="https://civitai.com/models/26295/floral-patterns">https://civitai.com/models/26295/floral-patterns</a><br /><br />Join our <a target="_blank" rel="ugc" href="https://discord.gg/BuEEtKnfUK"><u>Discord</u></a> for any questions or feedback!<br /></p><p><strong><u>Training process</u></strong></p><p>First attempt at training a LoRA, so any feedback would be appreciated. LoRA was trained using Kohya’s Dreambooth Lora Colab on top of AnyLora and an anime VAE. <br /></p><p>LoRA is best used with weight ~0.8 - weights that are too high can lead to an overcooked look. Due to size, it seems the Lora is less able to handle complex details. Images generated using it will generally look more simplistic than the full model.<br /><br /><strong><u>Prompting</u></strong></p><p>Use the word "pattern" to trigger the style. You can also use negative prompt to get rid of unwanted colors if the positive prompt isn't providing enough control.<br /><br />For best results, use the following pattern - a [COLOR1] pattern with [SUBJECT] on a [COLOR2] background<br /></p><p>Example prompts</p><ul><li><p>A pattern with lilacs and birds on a pink background</p></li><li><p>A black and white pattern with butterflies</p></li><li><p>A blue and yellow pattern with flowers</p><p></p></li></ul><p><strong><u>Settings</u></strong></p><p>Resolution <strong><u>must be</u></strong> 768 x 768 for best results</p><p>Sample images were generated with CFG = 11 and 75 inference steps. </p><p>Inference settings otherwise shouldn’t matter too much.</p>