## 【Art Style】Maidoll Style
### 一、模型概述

- 标签：`style`, `artstyle`, `hentai`, `mature female`
- 下载数：3070
- 收藏人数：694
- 评论人数：8
- 评分人数：8
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.0 (Fix)

- 统计数据
  - 发布时间：2023-03-30T15:59:38.105Z
  - 原始模型：SD 1.5
  - 下载数：2086
  - 评分人数：3
  - 评分：5
- 下载地址
  - [maidoll-v1fix-lora-32dim-10ep-novae-newcraft.safetensors](https://civitai.com/api/download/models/32028)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b6dc9893-4fbd-4005-1c36-22a3729c8100/width=450/364300.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1eeaca5a-2c04-4f18-dd01-4818bd345800/width=450/364299.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0e39b850-80f9-4b4c-81ac-fb1c5ac99b00/width=450/364298.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a669c46c-1ce8-41de-3bcc-62d5654aae00/width=450/364297.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-03-30T15:59:38.105Z
  - 原始模型：SD 1.5
  - 下载数：984
  - 评分人数：5
  - 评分：5
- 下载地址
  - [maidoll-lora-v1-128dim-8ep-naivae.safetensors](https://civitai.com/api/download/models/29499)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/145b5ec0-bc77-46ef-5e3b-d3c651467d00/width=450/333742.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/86ed47ed-4f11-46ea-2cc5-6ca637bc7b00/width=450/333757.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fb7bad3b-8a98-4259-b2eb-255bbc51d700/width=450/333756.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9b6696f1-e4c1-4a83-d53c-78c27af2be00/width=450/333755.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3>2023/3/30 update</h3><p>Fix the compatibility problem of non-NAI-based checkpoints. Now arbitrary anime model with NAI's VAE or kl-f8-anime2 VAE can also generate good results using this LoRA, theoretically. Adjust rank to 32 to balance file size and quality.</p><h1>Introduction</h1><p><strong>A conventional LoRA model</strong> trained with ~130 images by <a target="_blank" rel="ugc" href="https://www.pixiv.net/users/554800"><strong>Maidoll</strong></a>. <strong>The trigger tag is ‘maidoll’.</strong> The 784mb VAEs (NovelAI, Anythingv3, <a target="_blank" rel="ugc" href="https://huggingface.co/WarriorMama777/OrangeMixs"><strong>Orangemix</strong></a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/4468/counterfeit-v25"><strong>Counterfeit</strong></a>) are recommended. 0.6 ~ 0.8 weights are good. <strong>The preview images are generated using 1.6 version (original) </strong><a target="_blank" rel="ugc" href="https://civitai.com/models/9139/yesmix"><strong>YesMix.</strong></a></p><h1>Cautions (Must Read)</h1><ul><li><p>Some preview images are generated using hires fix. Thus, <strong>if you wanna generate the preview images, pls download the original preview images and analyze them using 'PNG INFO' in webui to get all generating information.</strong></p><p></p></li><li><p><strong>The maximum of generating resolution should not exceed 1024 theoretically, otherwise extra/deformed head/limbs will be waiting for you :). </strong>Try to use 'hires fix' to prevent this problem and help to generate higher-resolution images.</p><p></p></li><li><p>For 784mb VAEs (NovelAI, Anythingv3, Orangemix, Counterfeit) users, <strong>make sure add '--no-half-vae' in command line of webui to prevent generating black images.</strong> See <a target="_blank" rel="ugc" href="https://rentry.org/voldy"><strong>voldy's log</strong></a> for the details of edit method. <strong>For high-performance GPU, make sure 'medvram' and 'lowvram' mode are disabled.</strong></p></li></ul>