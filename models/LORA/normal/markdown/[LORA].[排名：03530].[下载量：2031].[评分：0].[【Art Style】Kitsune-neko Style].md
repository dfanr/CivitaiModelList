## 【Art Style】Kitsune-neko Style
### 一、模型概述

- 标签：`anime`, `style`, `art style`, `nsfw`
- 下载数：2031
- 收藏人数：450
- 评论人数：1
- 评分人数：0
- 评分：0

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0 (new craft)

- 统计数据
  - 发布时间：2023-05-31T09:23:51.706Z
  - 原始模型：SD 1.5
  - 下载数：913
  - 评分人数：0
  - 评分：0
- 下载地址
  - [kitsuneneko-v1-lora-naivae-newcraft-block-9ep.safetensors](https://civitai.com/api/download/models/86134)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d119a652-dbd6-4b16-8656-5642e47bbcb3/width=450/978923.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dd56a891-8b2e-41b9-976d-28cc9b299074/width=450/978916.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/59b2efce-c24a-4b4f-a443-f6db9ca97cbb/width=450/978918.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4bebc89e-a121-4f04-a5ab-4ab7ddf6f43d/width=450/978920.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-05-31T09:18:49.786Z
  - 原始模型：SD 1.5
  - 下载数：1118
  - 评分人数：0
  - 评分：0
- 下载地址
  - [kitsuneneko-v1-lora-naivae-64dim-5ep.safetensors](https://civitai.com/api/download/models/75759)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0ecac646-4f27-4c2e-8978-a980bf4b71be/width=450/847642.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/eef03618-7aed-4daa-962b-23df561286c2/width=450/847643.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6a1106a4-2467-49e7-88d4-d15bfafc949d/width=450/847641.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d3a51796-9ca5-49ed-bfcb-dd64410373d3/width=450/847634.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3 id="heading-200">2023/5/31 update</h3><p><span style="color:rgb(0, 0, 0)">Retrain the model using new craft. Reduce learning rate to mitigate overfitting.</span></p><h1 id="heading-201">Introduction</h1><p>A LoRA model trained with images illustrated by <a target="_blank" rel="ugc" href="https://www.pixiv.net/users/35363347"><strong>Kitsune-neko</strong></a>. <strong>The trigger tag is 'kitsune-neko'.</strong> <strong>The key features are 'shiny, shiny skin'.</strong> The 784mb VAEs (NovelAI, Anythingv3, <a target="_blank" rel="ugc" href="https://huggingface.co/WarriorMama777/OrangeMixs"><strong>Orangemix</strong></a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/4468/counterfeit-v25"><strong>Counterfeit</strong></a>) are recommended. 0.6 ~ 0.8 weights are good. <strong>The preview images are generated using 1.6 version (original) </strong><a target="_blank" rel="ugc" href="https://civitai.com/models/9139/yesmix"><strong>YesMix.</strong></a></p><p></p><h1 id="heading-202">Cautions (Must Read)</h1><h2 id="heading-203"><strong>For anime model,</strong></h2><h2 id="heading-204"><strong>pls disable 'face restoration' during generating.</strong></h2><h2 id="heading-205"><strong>pls disable 'face restoration' during generating.</strong></h2><h2 id="heading-206"><strong>pls disable 'face restoration' during generating.</strong></h2><ul><li><p>Some preview images are generated using 'Hires Fix' and upscaled using 'SD Upscale'. Thus, <strong>if you wanna generate the preview images, pls download the original preview images and analyze them using 'PNG INFO' in webui to get all generating information.</strong></p><p></p></li></ul><h3 id="heading-207"><strong><u>BTW, make sure set this option in 'Stable Diffusion' settings to 'CPU' to successfully regenerate the preview images with the same seed.</u></strong></h3><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c1e77cab-093f-44e5-803b-1afcf2d42df4/width=525/c1e77cab-093f-44e5-803b-1afcf2d42df4.jpeg" /><p></p><ul><li><p><strong>The training resolution of this model is 1024x1024, so generating resolution must not exceed this range. </strong>Try to use 'hires fix' to prevent this problem and help to generate higher-resolution images.</p><p></p></li><li><p>For 784mb VAEs (NovelAI, Anythingv3, Orangemix, Counterfeit) users, <strong>make sure add '--no-half-vae' in command line of webui to prevent generating black images.</strong> See <a target="_blank" rel="ugc" href="https://rentry.org/voldy"><strong>voldy's log</strong></a> for the details of edit method. <strong>For high-performance GPU, make sure 'medvram' and 'lowvram' mode are disabled.</strong></p></li></ul>