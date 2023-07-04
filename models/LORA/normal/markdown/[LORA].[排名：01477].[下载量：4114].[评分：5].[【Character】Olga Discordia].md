## 【Character】Olga Discordia
### 一、模型概述

- 标签：`anime`, `character`, `girl`, `anime character`, `game character`, `hentai`
- 下载数：4114
- 收藏人数：1215
- 评论人数：3
- 评分人数：10
- 评分：5

### 二、下载地址（共2个版本）

#### [版本2/共2个版本] v1.1

- 统计数据
  - 发布时间：2023-03-28T12:52:16.286Z
  - 原始模型：SD 1.5
  - 下载数：3585
  - 评分人数：7
  - 评分：5
- 下载地址
  - [olga-lora-v1.1-128dim-8ep-niavae-5gamma.safetensors](https://civitai.com/api/download/models/30671)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/61a855f8-dd1f-4abf-80e1-bd0287d9a800/width=450/348366.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/61ddb3f9-27be-45d1-2f05-ff950e6f8600/width=450/348365.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1858e6b9-eb8a-498e-62ec-0a8e01143300/width=450/348364.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/11e3861b-419e-4d7e-fe5a-869a08708b00/width=450/348363.jpeg" /> |
| ---- | ---- | ---- | ---- |

#### [版本1/共2个版本] v1.0

- 统计数据
  - 发布时间：2023-03-28T12:52:16.286Z
  - 原始模型：SD 1.5
  - 下载数：529
  - 评分人数：3
  - 评分：5
- 下载地址
  - [olga-lora-v1-128dim-5ep-naivae.safetensors](https://civitai.com/api/download/models/30086)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8fa03fd2-4e8b-4777-e644-cc9329be8900/width=450/341255.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c7314680-de21-4bb4-517d-9fd4d1c92a00/width=450/341267.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f93f0d69-9588-4b67-5614-1bb2f7abd700/width=450/341266.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3b449a77-962a-4e7e-a8d6-cb91bc1b0400/width=450/341265.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h3>2023/3/28 update</h3><p>Use <strong>Min-SNR Weighting Strategy</strong> to control loss and accelerate convergence.</p><h1>Introduction</h1><p><strong>A conventional LoRA model</strong> trained with ~90 images of Olga Discordia from Kuroinu. 0.6 ~ 0.8 weights are good. <strong>The preview images are generated using 1.6 version (original) </strong><a target="_blank" rel="ugc" href="https://civitai.com/models/9139/yesmix"><strong>YesMix</strong></a><strong>. </strong>Now she can play with <a target="_blank" rel="ugc" href="https://civitai.com/models/9489/celestine-lucullus"><strong>Celestine Lucullus</strong></a>.</p><h1>Cautions (Must Read)</h1><ul><li><p>Some preview images are generated using hires fix. Thus, <strong>if you wanna generate the preview images, pls download the original preview images and analyze them using 'PNG INFO' in webui to get all generating information.</strong></p><p></p></li><li><p><strong>The maximum of generating resolution should not exceed 1024 theoretically, otherwise extra/deformed head/limbs will be waiting for you :). </strong>Try to use 'hires fix' to prevent this problem and help to generate higher-resolution images.</p><p></p></li><li><p>For 784mb VAEs (NovelAI, Anythingv3, Orangemix, Counterfeit) users, <strong>make sure add '--no-half-vae' in command line of webui to prevent generating black images.</strong> See <a target="_blank" rel="ugc" href="https://rentry.org/voldy"><strong>voldy's log</strong></a> for the details of edit method. <strong>For high-performance GPU, make sure 'medvram' and 'lowvram' mode are disabled.</strong></p></li></ul>