## M.OS Realistic Diffusion
### 一、模型概述

- 标签：`base model`
- 下载数：602
- 收藏人数：139
- 评论人数：1
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-06-08T21:56:38.222Z
  - 原始模型：SD 1.5
  - 下载数：602
  - 评分人数：0
  - 评分：0
- 下载地址
  - [mOSRealistic_v10.safetensors](https://civitai.com/api/download/models/92012?type=Model&format=SafeTensor&size=full&fp=fp16)
  - [mOSRealistic_v10.safetensors](https://civitai.com/api/download/models/92012)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/23876d8c-104b-45f3-b139-4b9244306908/width=450/1077913.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9ee772fc-b9c4-44f4-a214-d7b1e7241713/width=450/1077911.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ca2b706e-5594-4386-976e-4affdee5be8a/width=450/1077919.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/42f9c5ae-2ad4-460c-843b-b88602a2c9ad/width=450/1077912.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h2 id="heading-743">Motivation</h2><p>As a <a target="_blank" rel="ugc" href="https://instagram.com/mental.os">3D generalist and CGI artist</a>, I often find myself in the need of complex and specific moodboards, and, if you ever did one, you most certainly know that this is almost impossible. Pinterest, ArtStation, Behance, and general Google Search can get you only as far as someone already imagined - so the inspiration is either limited or unconsistent.</p><p>This makes my take on AI art too: a huge oasis of unlimited moodboards customized and fine-tuned my your own need. But for this tool to really do wonders and to be a trusty sidekick even in a production environment, a lot of tweaking is required.</p><p><a target="_blank" rel="ugc" href="https://civitai.com/models/86515">M.OS Realistic Diffusion</a> aims to be the fine-tuned model that can be used by artists of various industries to kickstart their creations even if they work in automotive, photography, game, fashion, or architecture.</p><h1 id="heading-744">The Model</h1><p>... is trained using <a target="_blank" rel="ugc" href="https://creativecommons.org/share-your-work/public-domain/cc0/">CC0</a> libraries, stock images, and <a target="_blank" rel="ugc" href="https://instagram.com/mental.os">my own copyrighted work</a>.</p><p><strong><span style="color:rgb(0, 225, 255)">Recommended settings:</span></strong></p><ul><li><p><span style="color:rgb(0, 225, 255)">Clip Skip 2;</span></p></li><li><p><span style="color:rgb(0, 225, 255)">VAE: </span><a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.safetensors"><span style="color:rgb(0, 225, 255)">StabilityAI ft-MSE 850000 EMA</span></a><em><span style="color:rgb(0, 225, 255)"> (</span></em><a target="_blank" rel="ugc" href="https://www.pcguide.com/apps/how-to/stable-diffusion-how-to-use-vae/"><em><span style="color:rgb(0, 225, 255)">How to</span></em></a><em><span style="color:rgb(0, 225, 255)">);</span></em></p></li><li><p><a target="_blank" rel="ugc" href="https://github.com/mcmonkeyprojects/sd-dynamic-thresholding"><span style="color:rgb(0, 225, 255)">Dynamic Thresholding</span></a><span style="color:rgb(0, 225, 255)"> </span><em><span style="color:rgb(0, 225, 255)">(more samples and details without clipping)</span></em><span style="color:rgb(0, 225, 255)">;</span></p></li><li><p><span style="color:rgb(0, 225, 255)">Hires. Fix </span><em><span style="color:rgb(0, 225, 255)">(for weird aspect ratios);</span></em></p></li><li><p><span style="color:rgb(0, 225, 255)">Optimized for 512px and 768px;</span></p></li><li><p><span style="color:rgb(0, 225, 255)">Sampler: DPM++ SDE Karras;</span></p></li><li><p><span style="color:rgb(0, 225, 255)">Soft / cinematic looks: 2-6 CFG + 10-20 Steps (fast);</span></p></li><li><p><span style="color:rgb(0, 225, 255)">Realistic looks: 6-10 CFG + 20-40 Steps (balanced);</span></p></li><li><p><span style="color:rgb(0, 225, 255)">Dramatic / high-detail looks: &gt;10 CFG + &gt;40 Steps (slower);</span></p></li></ul><p>Samplers <em>(based on no. of samples required to produce good images, in order - CFG 7)</em>:</p><ul><li><p>Fast (&lt;10 steps): DPM++ SDE Karras, Euler, Euler a, DPM ++ SDE, DDIM;</p></li><li><p>Balanced (&lt;20 steps): DPM++ 2M, DPM++ 2M Karras, Heun;</p></li><li><p>Slow (&lt;30 steps): DPM++ 2M SDE Karras, PLMS, LMS.</p></li></ul><p></p><p>Take a moment to <a target="_blank" rel="ugc" href="https://civitai.com/posts/create?modelId=86515&amp;modelVersionId=92012&amp;returnUrl=/models/86515&amp;reviewing=true"><strong>leave a rating</strong></a><strong> and fav.</strong> M.OS Realistic Diffusion. It will give me a greater chance to reach a broader audience and fine-tune the model further.</p>