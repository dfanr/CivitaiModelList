## mCQ
### 一、模型概述

- 标签：`character`, `photorealistic`, `sexy`, `female`, `general purpose`, `woman`, `fantasy`, `girls`, `realistic`, `nsfw`
- 下载数：520
- 收藏人数：90
- 评论人数：1
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1.0

- 统计数据
  - 发布时间：2023-04-05T02:38:05.506Z
  - 原始模型：SD 1.5
  - 下载数：520
  - 评分人数：0
  - 评分：0
- 下载地址
  - [mcq_v10.safetensors](https://civitai.com/api/download/models/36506)
  - [mcq_v10.safetensors](https://civitai.com/api/download/models/36506?type=Model&format=SafeTensor&size=full&fp=fp32)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8c4d7e76-f9d9-4bbc-4c45-6cdebb80a200/width=450/426537.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3073fb93-7466-40c0-d27e-ca8c45421000/width=450/489520.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e7e301e6-c9c3-43b5-a45e-9301d8760f00/width=450/489518.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a05f31c3-749c-4ee3-d30e-ce135e683800/width=450/426533.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Been tinkering with this for a while. Still trying to figure out what prompts work best, since it's a merge of a lot of models.</p><p>There's also the anime-style version of this model (more like 2.5D) <a target="_blank" rel="ugc" href="https://civitai.com/models/30382/mcq-ani">mCQAni</a></p><p>I'll update the description if this goes anywhere, including the recipe.</p><p>I used <a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt">vae-ft-mse-840000-ema-pruned.ckpt</a> for all image gens.</p><p><strong>Pruned Model fp16 has baked in VAE.</strong></p><p>Might be a good idea to include sfw/nsfw respectively into prompt/negative prompt depending on what you're looking for.</p><p>(note, I'm running macOS 13.3, python: 3.10.10, torch: 2.1.0.dev20230326 as of posting this)</p><p></p><p>Update (Apr 14):</p><p>Seems to work best if you include:<br />"((masterpiece, best quality)), highly detailed, photorealistic, photo of" at the beginning of the prompt, good results with "((perfect face, detailed iris, realistic pupils)),(high detailed skin:0.9), (visible pores:0.3)," at the end.</p><p>However, you should get good results with simple prompts as well. Check example images, there's a variety of samplers, prompting styles, with and without hires fix.</p>