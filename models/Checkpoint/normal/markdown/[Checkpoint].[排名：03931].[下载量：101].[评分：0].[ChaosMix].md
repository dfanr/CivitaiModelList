## ChaosMix
### 一、模型概述

- 标签：`anime`, `manga`, `base model`, `semi-realistic`
- 下载数：101
- 收藏人数：15
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] V1

- 统计数据
  - 发布时间：2023-02-19T12:15:42.480Z
  - 原始模型：SD 2.1 768
  - 下载数：101
  - 评分人数：0
  - 评分：0
- 下载地址
  - [chaosmix_v1.ckpt](https://civitai.com/api/download/models/12572)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6c4ab45a-6e2a-4493-41f6-ab9cd2122500/width=450/121161.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2af6350b-1a31-494b-fd01-d5d0ba1f7a00/width=450/121171.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/12e76bcd-de13-454c-8fa7-e859a1693500/width=450/121170.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d484d4de-9dc5-4edd-2256-56634f635900/width=450/121169.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>A mixture of <a rel="ugc" href="https://huggingface.co/waifu-diffusion/wd-1-5-beta">Waifu Diffusion 1.5 (WD)</a>, <a rel="ugc" href="https://huggingface.co/alfredplpl/picasso-diffusion-1-1">Picasso Diffusion 1.1 (PiD)</a>, and <a rel="ugc" href="https://huggingface.co/IlluminatiAI/Illuminati_Diffusion_v1.0">Illuminati Diffusion 1.0 (ID)</a>.</p><p>I have first merged WD and PiD with the ratio of 0.6 : 0,4, and then block merged ID with the following weights: 0.7,0.65,0.6,0.55,0.5,0.45,0.45,0.4,0.4,0.4,0.4,0.4,0,0.45,0.4,0.35,0.25,0.25,0.25,0.25,0.3,0.4,0.6,0.65,0.7.</p><p>I didn't upload a yaml because it's no longer necessary when using webUI. If you need one, just download and rename it from somewhere.</p>