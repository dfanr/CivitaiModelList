## 【Art Style】Yoongonji Style
### 一、模型概述

- 标签：`style`, `art style`, `korean girl`, `anime girl`
- 下载数：1950
- 收藏人数：568
- 评论人数：7
- 评分人数：5
- 评分：5

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-03T13:24:59.382Z
  - 原始模型：SD 1.5
  - 下载数：1950
  - 评分人数：5
  - 评分：5
- 下载地址
  - [yoongonji-v1-lora-naivae-enc-4ep.safetensors](https://civitai.com/api/download/models/88398)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c7924008-0743-4b81-95bd-17f5da672af3/width=450/1017471.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c301e946-2d7c-4dfb-a6e4-910a19e006dd/width=450/1017464.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7c2bd824-eda0-4a7b-9477-29f78a121db6/width=450/1017466.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/55c30465-a44b-4278-920b-1a77c63ae11f/width=450/1017477.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-211">Introduction</h1><p>A LoRA model trained with images illustrated by <a rel="ugc" href="https://twitter.com/yoongonji?lang=en"><strong>Yoongonji</strong></a>. <strong>The trigger tag is 'yoongnoji'.</strong><span style="color:rgb(0, 0, 0)"> The 784mb VAEs (NovelAI, Anythingv3, </span><a target="_blank" rel="ugc" href="https://huggingface.co/WarriorMama777/OrangeMixs"><strong>Orangemix</strong></a><span style="color:rgb(0, 0, 0)">, </span><a target="_blank" rel="ugc" href="https://civitai.com/models/4468/counterfeit-v25"><strong>Counterfeit</strong></a><span style="color:rgb(0, 0, 0)">) are recommended. 0.6 ~ 0.8 weights are good. </span><strong>The preview images are generated using 1.6 version (original) </strong><a target="_blank" rel="ugc" href="https://civitai.com/models/9139/yesmix"><strong><u>YesMix.</u></strong></a></p><p></p><h3 id="heading-212"><span style="color:#fa5252">Due to the use of dropout during training to reduce overfitting and enhance generalization ability, the generated results may not be too similar to the original images.</span></h3><p></p><h1 id="heading-202">Cautions (Must Read)</h1><h2 id="heading-203"><strong>For anime model,</strong></h2><h2 id="heading-204"><strong>pls disable 'face restoration' during generating.</strong></h2><h2 id="heading-205"><strong>pls disable 'face restoration' during generating.</strong></h2><h2 id="heading-206"><strong>pls disable 'face restoration' during generating.</strong></h2><ul><li><p>Some preview images are generated using 'Hires Fix' and upscaled using 'SD Upscale'. Thus, <strong>if you wanna generate the preview images, pls download the original preview images and analyze them using 'PNG INFO' in webui to get all generating information.</strong></p><p></p></li></ul><h3 id="heading-207"><strong><u>BTW, make sure set this option in 'Stable Diffusion' settings to 'CPU' to successfully regenerate the preview images with the same seed.</u></strong></h3><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c1e77cab-093f-44e5-803b-1afcf2d42df4/width=525/c1e77cab-093f-44e5-803b-1afcf2d42df4.jpeg" /></p><p></p><ul><li><p><strong>The training resolution of this model is 1024x1024, so generating resolution must not exceed this range. </strong>Try to use 'hires fix' to prevent this problem and help to generate higher-resolution images.</p><p></p></li><li><p>For 784mb VAEs (NovelAI, Anythingv3, Orangemix, Counterfeit) users, <strong>make sure add '--no-half-vae' in command line of webui to prevent generating black images.</strong> See <a target="_blank" rel="ugc" href="https://rentry.org/voldy"><strong>voldy's log</strong></a> for the details of edit method. <strong>For high-performance GPU, make sure 'medvram' and 'lowvram' mode are disabled.</strong></p></li></ul>