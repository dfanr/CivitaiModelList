## DigitalRealityMix
### 一、模型概述

- 标签：`anime`, `digital art`, `cgi`, `fantasy`, `semi-realistic`
- 下载数：384
- 收藏人数：149
- 评论人数：4
- 评分人数：2
- 评分：3

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] v1

- 统计数据
  - 发布时间：2023-02-28T03:40:29.283Z
  - 原始模型：SD 1.5
  - 下载数：384
  - 评分人数：2
  - 评分：3
- 下载地址
  - [digitalrealitymix_v1.safetensors](https://civitai.com/api/download/models/15369?type=Model&format=SafeTensor&size=full&fp=fp16)
  - [digitalrealitymix_v1.safetensors](https://civitai.com/api/download/models/15369)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6dda47e7-a4ab-4e7f-fad9-410c982dce00/width=450/153367.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fd957073-89de-44c1-c41e-58a8db922900/width=450/153366.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a6ba92bf-19e5-4a89-00bf-1d0d191fad00/width=450/153365.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4a7aa267-4f91-4b3d-1051-da4e43937200/width=450/153364.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<p>Update: added 2 gig fp16 version in dropdown</p><p></p><p>My aim was to get away from the anime, cartoon look and get closer to realism but with a fantasy rendered cgi style.</p><p></p><p>Recipe was: 50/50 AOM2 and anything + 20 DreamShaper + 20 Experience<br /></p><p>My prompts are in the example images.<br />Useful prompt keywords:</p><pre><code>digital art, illustrated, realistic face, 3d rendered face, shaded face, best quality</code></pre><p>This goes in \stable-diffusion-webui\models\Stable-diffusion</p><p>VAE used (goes in \stable-diffusion-webui\models\VAE):<a target="_blank" rel="ugc" href="https://huggingface.co/stabilityai/sd-vae-ft-mse-original/tree/main"> vae-ft-mse-840000-ema-pruned.ckpt</a></p><p></p><p>Example images settings:</p><p>This Lora is used (goes in \stable-diffusion-webui\models\Lora): <br /><a target="_blank" rel="ugc" href="https://civitai.com/models/6638/samdoesarts-sam-yang-style-lora">Sam Yang </a>I keep it down at 0.3 as it can be overpowering.</p><p>These textual inversions are used (they go in \stable-diffusion-webui\embeddings):<br /><a target="_blank" rel="ugc" href="https://huggingface.co/datasets/Nerfgun3/bad_prompt/tree/main">bad_prompt_version2</a>, <a target="_blank" rel="ugc" href="https://huggingface.co/yesyeahvh/bad-hands-5/tree/main">bad-hands-5</a>, <a target="_blank" rel="ugc" href="https://huggingface.co/datasets/gsdf/EasyNegative/tree/main">EasyNegative</a>, <a target="_blank" rel="ugc" href="https://civitai.com/models/4629/deep-negative-v1x">ng_deepnegative_v1_75t</a></p><p>Clip skip: 2<br />Eta noise seed delta: 31337<br /><br />See more of my gens on <a target="_blank" rel="ugc" href="https://www.deviantart.com/realitybyte5">https://www.deviantart.com/realitybyte5</a></p>