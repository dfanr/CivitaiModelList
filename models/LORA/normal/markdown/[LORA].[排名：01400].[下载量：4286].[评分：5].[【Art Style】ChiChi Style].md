## 【Art Style】ChiChi Style
### 一、模型概述

- 标签：`girl`, `watercolor`, `style`, `art style`, `artstyle`, `beautiful`, `girls`
- 下载数：4286
- 收藏人数：1203
- 评论人数：0
- 评分人数：5
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0 (Fix)

- 统计数据
  - 发布时间：2023-03-30T16:02:54.119Z
  - 原始模型：SD 1.5
  - 下载数：2915
  - 评分人数：2
  - 评分：5
- 下载地址
  - [chichi-v1fix-lora-32dim-8ep-novae-newcraft.safetensors](https://civitai.com/api/download/models/32033)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b53eaf7b-fb77-415e-bd4d-f3688ea96b00/width=450/364335.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e4f0de4c-48da-47ec-3646-3fefbd904f00/width=450/364334.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/616728b2-9280-4104-5881-98ec3a47f500/width=450/364333.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/5dcf7227-1e02-4e9b-6c19-a7d4a410da00/width=450/364332.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-03-30T16:02:54.119Z
  - 原始模型：SD 1.5
  - 下载数：1371
  - 评分人数：3
  - 评分：5
- 下载地址
  - [chichi-lora-v1-128dim-10ep-naivae.safetensors](https://civitai.com/api/download/models/27459)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b2bacf43-785c-4254-6e12-264fceee1e00/width=450/302237.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/52d41b73-9a48-4a38-6bd7-e1015680da00/width=450/302250.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4d9d7feb-702f-4fa2-d598-bc452e9e5c00/width=450/302249.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/aaf0f259-b67b-438a-fde4-eef47225a300/width=450/302248.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3>2023/3/31 update</h3><p>Fix the compatibility problem of non-NAI-based checkpoints. Now arbitrary anime model with NAI's VAE or kl-f8-anime2 VAE can also generate good results using this LoRA, theoretically. Adjust rank to 32 to balance file size and quality.</p><h1>Introduction</h1><p>A LoRA model trained with ~190 images by <a target="_blank" rel="ugc" href="https://weibo.com/u/5748383382"><strong>ChiChi</strong></a>. <strong>The trigger tag is ‘chch-style’.</strong> The 784mb VAEs (NovelAI, Anythingv3, <a target="_blank" rel="ugc" href="https://huggingface.co/WarriorMama777/OrangeMixs"><strong>Orangemix</strong></a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/4468/counterfeit-v25"><strong>Counterfeit</strong></a>) are recommended. 0.6 ~ 0.8 weights are good. <strong>The preview images are generated using 1.6 version (original) </strong><a target="_blank" rel="ugc" href="https://civitai.com/models/9139/yesmix"><strong>YesMix.</strong></a></p><h1>Cautions (Must Read)</h1><ul><li><p>Some preview images are generated using hires fix. Thus, <strong>if you wanna generate the preview images, pls download the original preview images and analyze them using 'PNG INFO' in webui to get all generating information.</strong></p><p></p></li><li><p><strong>The maximum of generating resolution should not exceed 1024 theoretically, otherwise extra/deformed head/limbs will be waiting for you :). </strong>Try to use 'hires fix' to prevent this problem and help to generate higher-resolution images.</p><p></p></li><li><p>For 784mb VAEs (NovelAI, Anythingv3, Orangemix, Counterfeit) users, <strong>make sure add '--no-half-vae' in command line of webui to prevent generating black images.</strong> See <a target="_blank" rel="ugc" href="https://rentry.org/voldy"><strong>voldy's log</strong></a> for the details of edit method. <strong>For high-performance GPU, make sure 'medvram' and 'lowvram' mode are disabled.</strong></p></li></ul>