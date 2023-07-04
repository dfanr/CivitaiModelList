## 【Art Style】Saburou Style
### 一、模型概述

- 标签：`anime`, `style`, `girls`, `hentai`
- 下载数：800
- 收藏人数：215
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-18T15:51:40.030Z
  - 原始模型：SD 1.5
  - 下载数：800
  - 评分人数：0
  - 评分：0
- 下载地址
  - [saburou-v1-lora-any-5ep-resize.safetensors](https://civitai.com/api/download/models/98864)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d4e4d5f9-85e7-48cd-bad3-10dc39141fd2/width=450/1195433.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fdd258f0-06be-49f7-9321-be0a9303c12f/width=450/1195436.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a4b1bb22-9779-40e1-acb6-d7b000c0b073/width=450/1195435.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/236a1501-f0fa-4544-95f6-b501e5d84a4d/width=450/1195434.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1 id="heading-43">Introduction</h1><p><span style="color:rgb(0, 0, 0)">A LoRA model trained with images illustrated by </span><a rel="ugc" href="https://www.pixiv.net/users/911893"><strong><span style="color:rgb(34, 139, 230)">Saburou</span></strong></a><span style="color:rgb(0, 0, 0)">. </span><strong>The trigger tag is 'saburou'.</strong><span style="color:rgb(0, 0, 0)"> 0.6 ~ 0.8 weights are good. </span><strong><span style="color:rgb(37, 38, 43)">The preview images are generated using 1.6 version, 2.0 version </span></strong><a target="_blank" rel="ugc" href="https://civitai.com/models/9139/checkpointyesmix"><strong><span style="color:rgb(34, 139, 230)">Yesmix</span></strong></a><strong><span style="color:rgb(37, 38, 43)"> and </span></strong><a target="_blank" rel="ugc" href="https://civitai.com/models/7240/meinamix"><strong><span style="color:rgb(34, 139, 230)">MeinaMix</span></strong></a><strong><span style="color:rgb(37, 38, 43)"> to verify the compatibility of this LoRA model on different base models.</span></strong></p><p></p><h1 id="heading-538">Cautions (Must Read)</h1><h2 id="heading-539"><strong>For anime model,</strong></h2><h2 id="heading-540"><strong>pls disable 'face restoration' during generating.</strong></h2><h2 id="heading-541"><strong>pls disable 'face restoration' during generating.</strong></h2><h2 id="heading-542"><strong>pls disable 'face restoration' during generating.</strong></h2><ul><li><p>Some preview images are generated using 'Hires Fix' and upscaled using 'SD Upscale'. Thus, <strong>if you wanna generate the preview images, pls download the original preview images and analyze them using 'PNG INFO' in webui to get all generating information.</strong></p><p></p></li></ul><h3 id="heading-543"><strong><u>BTW, make sure set this option in 'Stable Diffusion' settings to 'CPU' to successfully regenerate the preview images with the same seed.</u></strong></h3><p><img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c1e77cab-093f-44e5-803b-1afcf2d42df4/width=525/c1e77cab-093f-44e5-803b-1afcf2d42df4.jpeg" /></p><p></p><ul><li><p><strong>The training resolution of this model is 1024x1024, so generating resolution must not exceed this range. </strong>Try to use 'hires fix' to prevent this problem and help to generate higher-resolution images.</p><p></p></li><li><p>For 784mb VAEs (NovelAI, Anythingv3, Orangemix, Counterfeit) users, <strong>make sure add '--no-half-vae' in command line of webui to prevent generating black images.</strong> See <a target="_blank" rel="ugc" href="https://rentry.org/voldy"><strong>voldy's log</strong></a> for the details of edit method. <strong>For high-performance GPU, make sure 'medvram' and 'lowvram' mode are disabled.</strong></p></li></ul>