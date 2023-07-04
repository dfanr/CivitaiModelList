## Emotion-Puppeteer
### 一、模型概述

- 标签：`photorealistic`, `concept`, `expressions`, `photo`, `emotions`, `faces`, `photography`, `photorealism`
- 下载数：1031
- 收藏人数：242
- 评论人数：25
- 评分人数：1
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v2

- 统计数据
  - 发布时间：2023-02-23T07:30:26.818Z
  - 原始模型：SD 1.5
  - 下载数：726
  - 评分人数：1
  - 评分：5
- 下载地址
  - [emotionPuppeteer_v2.ckpt](https://civitai.com/api/download/models/10665)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bb25377e-29c3-4735-9630-cc308bdd0400/width=450/103456.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/14aaade3-17b8-45ab-fc79-35460dc3dc00/width=450/103455.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1c79bc55-9d60-4dcc-3f9b-674ab533af00/width=450/103454.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2bdabfbe-421d-4f7d-b77e-334889253c00/width=450/103453.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v0.1

- 统计数据
  - 发布时间：2023-02-23T07:30:26.818Z
  - 原始模型：SD 1.5
  - 下载数：305
  - 评分人数：0
  - 评分：0
- 下载地址
  - [emotionPuppeteer_v01.safetensors](https://civitai.com/api/download/models/5692)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ddbb4bdd-34e1-445b-fbb6-1e61ba1e3800/width=450/46479.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/76b11c9f-5e46-4e4a-633c-b9cc8d846900/width=450/46484.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/be556e02-90c6-4261-ecf3-e223ad119f00/width=450/46483.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8485eff1-3228-4958-cae5-29698da43700/width=450/46482.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2>🎭 Emotion Puppeteer 🎭</h2><p></p><p><strong>UPDATE:  </strong><a rel="ugc" href="https://civitai.com/models/11998/emotion-puppeteer-lora"><strong>Now available as a LoRA</strong></a><strong>.  Use with any model.</strong></p><p></p><ul><li><p>Photoreal faces with exact control of facial expressions</p></li><li><p>If you like the model, please post your generations!</p></li><li><p><a target="_blank" rel="ugc" href="https://huggingface.co/mattthew/emotion-puppeteer-v2">Safetensors and inpaint models</a> available on Huggingface, along with training details</p></li><li><p>These instruction apply to v2 only. There's no good reason to use v0.1.</p></li></ul><p></p><h3>Import Instructions</h3><p>To get what you want, you should read this.</p><p></p><p><strong>Use this prompt format for best results</strong></p><ul><li><p>"{<strong>A</strong>} face, {<strong>B</strong>} eyes, {<strong>C</strong>} mouth, {<strong>D</strong>}, {anything else}"</p></li><li><p>e.g. "plain face, seething eyes, screaming mouth, closeup portrait, looking away, old man with white hair"</p></li><li><p>CFG = 5 is recommended</p></li></ul><p></p><p><strong>A - Face keywords</strong></p><ul><li><p><strong>plain</strong>, unattractive face - my subjective opinion - biased towards extreme emotions</p></li><li><p><strong>cute</strong>, attractive face - my subjective opinion - biased towards pleasant emotions</p></li><li><p><strong>adorable</strong>, most attractive face - my subjective opinion - strongly biased towards pleasant emotions</p></li></ul><p></p><p><strong>B - Eye keywords</strong></p><ul><li><p><strong>seething</strong>, &gt;: shaped brows - scrunched brows</p></li><li><p><strong>grieving</strong>, &lt;: shaped brows - scrunched brows</p></li><li><p><strong>widening</strong>, eyelids raised very high - brows arched</p></li><li><p><strong>glaring</strong>, lowered brows - eyelids lowered</p></li><li><p><strong>pleasing</strong>, neutral brows - eyes crecent shaped and smile crinkled</p></li><li><p><strong>piercing</strong>, neutral brows - eyelids neutral</p></li><li><p><strong>squinting</strong>, lowered brows - eyelids squeezed closed or almost closed</p></li><li><p><strong>winking</strong>, right eye open, left eye closes</p></li></ul><p></p><p><strong>C - Mouth keywords</strong></p><ul><li><p><strong>breathing</strong>, mouth relaxed and slightly open</p></li><li><p><strong>resting</strong>, neutral or slight relaxed frown - lips together</p></li><li><p><strong>smiling</strong>, smiling with lips parted - teeth together or slightly apart</p></li><li><p><strong>screaming</strong>, mouth wide open - lower-teeth visible or chin scrunched</p></li><li><p><strong>sneering</strong>, nose scrunched - left upper-lip raised - upper-teeth not bared</p></li><li><p><strong>singing</strong>, mouth wide open and oval-shaped</p></li><li><p><strong>delighting</strong>, smiling with mouth wide open</p></li><li><p><strong>kissing</strong>, puckered lips</p></li><li><p><strong>gnashing</strong>, nose scrunched - upper-lip evenly raised - teeth together - lower-teeth bared</p></li><li><p><strong>gasping</strong>, mouth open and frowning-bean-shaped - chin relaxed</p></li><li><p><strong>relaxing</strong>, slight relaxed smile - lips together</p></li><li><p><strong>frowning</strong>, chin and or nose scrunched - lips together</p></li><li><p><strong>snarling</strong>, nose scrunched - upper-lip evenly raised - lower-teeth not bared</p></li><li><p><strong>pouting</strong>, slight frown - lower-lip extended</p></li><li><p><strong>grimacing</strong>, lips apart and stretched wide - lips apart - teeth may be visible</p></li></ul><p></p><p><strong>D - Other keywords</strong></p><ul><li><p><strong>extreme closeup portrait</strong>, cropped at neck or closer</p></li><li><p><strong>closeup portrait</strong>, cropped at shoulders</p></li><li><p><strong>looking straight</strong>, head facing forward and eyes looking into the camera</p></li><li><p><strong>lookway away</strong>, head turned to three-quarters, regardless of eye direction</p></li></ul>