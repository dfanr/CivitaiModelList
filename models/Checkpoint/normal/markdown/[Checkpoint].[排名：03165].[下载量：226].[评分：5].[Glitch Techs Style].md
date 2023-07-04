## Glitch Techs Style
### 一、模型概述

- 标签：`animation`, `nickelodeon`, `glitch techs`, `style`, `netflix`
- 下载数：226
- 收藏人数：71
- 评论人数：2
- 评分人数：2
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] 1.0

- 统计数据
  - 发布时间：2023-01-23T20:56:04.931Z
  - 原始模型：SD 1.5
  - 下载数：226
  - 评分人数：2
  - 评分：5
- 下载地址
  - [glitchTechsStyle_10.ckpt](https://civitai.com/api/download/models/5858)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/243ab7e9-724f-458f-ca02-61c2d3397800/width=450/49132.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/df46c1b1-9a14-4690-da08-dfbee504a700/width=450/49149.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bf9d3506-aa6b-44f7-0dfa-a6ee7bd7f400/width=450/49148.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d2c68853-77ab-49ff-2f8b-81bbe7663f00/width=450/49147.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>this model was trained with almost 800 images of the Glitch Techs Netflix series artstyle.</p><p>to force the style you must use the prompt <strong><em>gtechstyle, art by gtechstyle, in the style of gtechstyle, cartoon (as prefix)</em></strong><em>.</em></p><p>training was done in 6000 steps with a learning rate 2e-6.</p><p>The text encoder was not trained. More than 6000 regularization images from the datasets <a target="_blank" rel="ugc" href="https://huggingface.co/datasets/waifu-research-department/regularization/tree/main">waifu-regularization-3.3k and </a><a target="_blank" rel="ugc" href="https://huggingface.co/datasets/waifu-research-department/regularization/blob/main/husbando-regularization-3.5k.zip">husbando-regularization-3.5k</a> were used.</p><p>the base model was the SD 1.5 with 512 x 512 images</p><p>all training was done on Google Colab free with a Tesla T4 and took about 1 hour.</p><p>the notebook used was the one from <a target="_blank" rel="ugc" href="https://colab.research.google.com/github/TheLastBen/fast-stable-diffusion/blob/main/fast-DreamBooth.ipynb">TheLastBen</a>.</p><p>Typical negative prompts:</p><p>Disfigured, bad art, amateur, poorly drawn, ugly, flat, deformed, poorly drawn, extra limbs, close up, b&amp;w, weird colors, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits , cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, ((((ugly)))), (((duplicate))), ((morbid)), ((mutilated)), out of frame, extra fingers, mutated hands, ((poorly drawn hands)), (( poorly drawn face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs )), cloned face, (((disfigured))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck)))</p>