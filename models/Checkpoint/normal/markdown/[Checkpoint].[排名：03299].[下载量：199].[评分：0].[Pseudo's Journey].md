## Pseudo's Journey
### 一、模型概述

- 标签：`base model`, `fine-tune`, `beautiful`, `high contrast`, `sfw`, `creative`, `2.1`, `midreal`, `midjourney v5`, `tuned text encoder`, `stable diffusion 2.1`
- 下载数：199
- 收藏人数：27
- 评论人数：0
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v2.0

- 统计数据
  - 发布时间：2023-06-04T22:09:50.079Z
  - 原始模型：SD 2.1 768
  - 下载数：199
  - 评分人数：0
  - 评分：0
- 下载地址
  - [pseudosJourney_v20.safetensors](https://civitai.com/api/download/models/78058)
  - [pseudosJourney_v20.yaml](https://civitai.com/api/download/models/78058?type=Config&format=Other)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d38b2001-a0d5-4df4-9448-332de396d99d/width=450/876978.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7f4275c8-5bd9-46b8-bb26-f06b8b4e8aec/width=450/877022.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ed239cd-72e9-40f1-9884-9827dd7c2e50/width=450/877049.jpeg" /> |
| ---- | ---- | ---- |


### 三、详情
<h1 id="heading-505">Disclaimer</h1><p><strong>This model applies Terminal SNR to its training noise schedule, as described </strong><a rel="ugc" href="https://huggingface.co/papers/2305.08891"><strong>here.</strong></a></p><p><strong>This will not work out-of-the-box (as of June 2023) with Automatic1111's Stable Diffusion WebUI.</strong></p><p></p><p>It works great using a Diffusers pipeline, such as InvokeAI, or a simple Diffusers python script using <strong><u>DDPMScheduler</u></strong><em><u>.</u></em> One such script is available, <a rel="ugc" href="https://github.com/bghira/SimpleTuner/blob/main/inference_ddpm.py"><strong>here</strong>.</a></p><p></p><p>I hope that Automatic1111's support for terminal SNR pipelines is improved someday, because SDXL will require it.</p>