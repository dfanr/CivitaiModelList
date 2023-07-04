## Cyberpunk Anime Diffusion
### 一、模型概述

- 标签：`anime`, `cyberpunk`
- 下载数：612
- 收藏人数：143
- 评论人数：7
- 评分人数：0
- 评分：0

### 二、下载地址（共1个版本）

#### [版本1/共1个版本] Cyberpunk Anime Diffusion V1

- 统计数据
  - 发布时间：2023-01-05T01:16:22.631Z
  - 原始模型：SD 1.5
  - 下载数：612
  - 评分人数：0
  - 评分：0
- 下载地址
  - [cyberpunkAnime_cyberpunkAnime.ckpt](https://civitai.com/api/download/models/4267?type=Model&format=PickleTensor&size=full&fp=fp16)
  - [cyberpunkAnime_cyberpunkAnime.safetensors](https://civitai.com/api/download/models/4267)
- 样例图像：

| <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/420a5ef1-96fb-485d-db9d-2af1d131cf00/width=450/28012.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/2546804e-79cf-4b3b-49bb-c2e6803b8300/width=450/28011.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fe9908c7-00aa-41ab-877b-20fffa609e00/width=450/28010.jpeg" /> | <img src="https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/16fed4d8-a8c7-4417-459f-0da673f16800/width=450/27984.jpeg" /> |
| ---- | ---- | ---- | ---- |


### 三、详情
<h1><strong>Cyberpunk Anime Diffusion</strong></h1><p>An AI model that generates cyberpunk anime characters!~</p><p>Based of a finetuned Waifu Diffusion V1.3 Model with Stable Diffusion V1.5 New Vae, training in Dreambooth</p><p>by <a target="_blank" rel="ugc" href="https://www.youtube.com/channel/UCzzsYBF4qwtMwJaPJZ5SuPg"><strong><u>DGSpitzer</u></strong></a></p><h3>🧨 Diffusers</h3><p>This repo contains both .ckpt and Diffuser model files. It's compatible to be used as any Stable Diffusion model, using standard <a target="_blank" rel="ugc" href="https://huggingface.co/docs/diffusers/api/pipelines/stable_diffusion"><strong><u>Stable Diffusion Pipelines</u></strong></a>.</p><p>You can convert this model to <a target="_blank" rel="ugc" href="https://huggingface.co/docs/diffusers/optimization/onnx"><strong><u>ONNX</u></strong></a>, <a target="_blank" rel="ugc" href="https://huggingface.co/docs/diffusers/optimization/mps"><strong><u>MPS</u></strong></a> and/or <a target="_blank" rel="ugc" href="https://huggingface.co/blog/stable_diffusion_jax"><strong><u>FLAX/JAX</u></strong></a>.</p><pre><code>#!pip install diffusers transformers scipy torch
from diffusers import StableDiffusionPipeline
import torch

model_id = "DGSpitzer/Cyberpunk-Anime-Diffusion"
pipe = StableDiffusionPipeline.from_pretrained(model_id, torch_dtype=torch.float16)
pipe = pipe.to("cuda")

prompt = "a beautiful perfect face girl in dgs illustration style, Anime fine details portrait of school girl in front of modern tokyo city landscape on the background deep bokeh, anime masterpiece, 8k, sharp high quality anime"
image = pipe(prompt).images[0]

image.save("./cyberpunk_girl.png")
</code></pre><h1>Online Demo</h1><p>You can try the online demo using HF space:</p><p><a target="_blank" rel="ugc" href="https://huggingface.co/spaces/DGSpitzer/DGS-Diffusion-Space">https://huggingface.co/spaces/DGSpitzer/DGS-Diffusion-Space</a></p><p>Or use Colab Notebook at here:</p><p><a target="_blank" rel="ugc" href="https://colab.research.google.com/github/HelixNGC7293/cyberpunk-anime-diffusion/blob/main/cyberpunk_anime_diffusion.ipynb">https://colab.research.google.com/github/HelixNGC7293/cyberpunk-anime-diffusion/blob/main/cyberpunk_anime_diffusion.ipynb</a></p><p><em>Buy me a coffee if you like this project ;P ♥</em></p><p><a target="_blank" rel="ugc" href="https://www.buymeacoffee.com/dgspitzer">https://www.buymeacoffee.com/dgspitzer</a></p><img src="https://huggingface.co/DGSpitzer/Cyberpunk-Anime-Diffusion/resolve/main/img/5.jpg" /><h1>Usage</h1><p>After model loaded, use keyword <strong>dgs</strong> in your prompt, with <strong>illustration style</strong> to get even better results.</p><p>For sampler, use <strong>Euler A</strong> for the best result (<strong>DDIM</strong> kinda works too), CFG Scale 7, steps 20 should be fine</p><p><strong>Example 1:</strong></p><pre><code>portrait of a girl in dgs illustration style, Anime girl, female soldier working in a cyberpunk city, cleavage, ((perfect femine face)), intricate, 8k, highly detailed, shy, digital painting, intense, sharp focus
</code></pre><p>For cyber robot male character, you can add <strong>muscular male</strong> to improve the output.</p><p><strong>Example 2:</strong></p><pre><code>a photo of muscular beard soldier male in dgs illustration style, half-body, holding robot arms, strong chest
</code></pre><p><strong>Example 3 (with Stable Diffusion WebUI):</strong></p><p>If using <a target="_blank" rel="ugc" href="https://github.com/AUTOMATIC1111/stable-diffusion-webui"><strong><u>AUTOMATIC1111's Stable Diffusion WebUI</u></strong></a></p><p>You can simply use this as <strong>prompt</strong> with <strong>Euler A</strong> Sampler, CFG Scale 7, steps 20, 704 x 704px output res:</p><pre><code>an anime girl in dgs illustration style
</code></pre><p>And set the <strong>negative prompt</strong> as this to get cleaner face:</p><pre><code>out of focus, scary, creepy, evil, disfigured, missing limbs, ugly, gross, missing fingers
</code></pre><p>This will give you the exactly same style as the sample images above.</p><img src="https://huggingface.co/DGSpitzer/Cyberpunk-Anime-Diffusion/resolve/main/img/ReadmeAddon.jpg" /><p><strong>NOTE: usage of this model implies accpetance of stable diffusion's </strong><a target="_blank" rel="ugc" href="https://huggingface.co/DGSpitzer/Cyberpunk-Anime-Diffusion/blob/main/LICENSE"><strong><u>CreativeML Open RAIL-M license</u></strong></a></p><img src="https://huggingface.co/DGSpitzer/Cyberpunk-Anime-Diffusion/resolve/main/img/1.jpg" /><img src="https://huggingface.co/DGSpitzer/Cyberpunk-Anime-Diffusion/resolve/main/img/4.jpg" /><img src="https://huggingface.co/DGSpitzer/Cyberpunk-Anime-Diffusion/resolve/main/img/6.jpg" />